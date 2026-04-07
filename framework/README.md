## DIRECT competency framework

Files contained in this folder represent the DIRECT framework dataset.

- [Definitions of terms](./terminology.md) - shared language for use across various user communities
- [Competency domains](./competency_domain.csv) - high-level thematic grouping of related competencies that together represent a broad area of professional capability.
- [Competencies](./competency.csv) - integrated set of skills - knowledge, behaviours and professional practices - required to perform effectively in a defined context.
- [Skills](./skill.csv) - specific, learnable and demonstrable behaviours or ability to perform tasks to an expected standard and guided by certain community values or practices.
- [Skill levels](./skill_level.csv) - degree of proficiency, autonomy or awareness demonstrated in applying a skill (performing a task or a behaviour).
- [Tools, methodologies and languages](./tool_methodology_language.csv) - demonstrators of skills.
- [Learning resources](./learning_resource.csv) - materials or activities that help individuals develop skills or learn to use tools, languages, and methodologies relevant to their role or specialty.

## Data model

The framework data model is shown below.

```mermaid
erDiagram
    direction LR
    competency ||--|{competency_domain : belongs
    skill ||--|{ competency : belongs
    skill }o--o{ tool_methodology_language : "demonstrated by"
    skill }o--o{ learning_resource: "learning and development"
    tool_methodology_language }o--o{ learning_resource : "learning and development"
    learning_resource ||--|{ provider : "provided by"

    competency_domain {
            string slug PK
	    string name
	    string description
    }

    competency {
	    string slug PK
	    string name
	    string description
	    string competency_domain_slug FK
    }

    skill {
	    string slug PK
	    string name
	    string description
	    string competency_slug FK
            string[] related_skills
            string[] tools_methodologies_languages
            string[] learning_resources
    }

    tool_methodology_language {
        string slug PK
        string name
        string description
        string url
        enum kind
        string[] learning_resources
    }

    learning_resource {
        string slug PK
        string name
        string provider_slug FK
        string lang
        string url
        string description
        string doi
    }

    provider {
        string slug PK
        string name
        string url
        string description
        string ror
    }

    skill_level {
	    string name
	    string short_description
	    string description
            enum level
		string focus
    }

    skill_level_values {
        string ZERO
		string '1'
        string '2'
        string '3'
        string '4'
    }

    tool_methodology_language_kind_values {
        string tool
		string methodology
        string language
    }
```
