# DIgital Research CompeTencies (DIRECT) Framework

## About

This project aims to define a skills and competencies framework to help us classify and describe technical and non-technical skills we use in our different roles as researchers, RSEs, data specialists, RSE group leads, PIs, etc., along with lists tools/methods/behaviours to demonstrate skills and training materials that can help us gain a particular skill.

A [sister project](https://github.com/direct-framework/direct-webapp) works on implementing a Django webapp to enable practical use of the framework - to browse the skills and competencies, self-assess and create individual skill profiles as “competency wheels”, compare profiles across a team, define template skills for different digital roles (e.g. a data archivist, a data scientists or an RSE with HPC specialism) and other use cases.


## History

This repository was originally created from the work that happened at the Software Sustainability Institute's Collaborations Workshop 2023 Hack Day.

The idea was to construct a resource on technical skills that we use that is for the RSE community and curated by the RSE community, along with training materials that can help people gain a particular skill, and visualise people's individaul skill profiles as "competency wheels".

![Screenshot of competency visualisations](rse-forge-screenshot.png)

The project was added to the [RSE Competencies Toolkit organisation](https://github.com/RSEToolkit/) and as a resource to support RSEs (Research Software Engineers) in tracking and managing their professional development. We have now extracted the work into its own separate [GitHub organisation](https://github.com/direct-framework).

Note that, while we've focussed on RSEs during the early stages of development, this tool could be used for any roles that used digital skills for research (and we have now expanded the framework to reflect that). 

The project comprised:

1. An RSE competency framework, outlining a structured **set of skills** that are useful when working as an RSE, with
   examples of how these skills can be demonstrated at different **levels of experience**. Not all RSEs will or need to have
   all skills at all levels.
2. A curated set of training resources, linked to the skills and levels from the competency framework.
3. A tool to visualise and compare different competency profiles.

The project aimed to support the following uses:

1. Recording and visualising your competency profile as an individual RSE.
2. Comparing competency profiles across a group of RSEs (e.g. to show the commonalities and variety across RSEs doing
   the same role at the same level at the same organisation, or comparing across organisations).
3. Find high-quality training resources to improve skills in a particular competency.
4. Define aspirational competency profiles, illustrate the gap to your current profile and highlight training resources
   that could help bridge that gap.

The project won the 3rd prize at CW23 and we have carried on with the work on this project after the initial prototype. Since then, we have compared our 
work with many [related skill frameworks](#related-skills-&-competencies-frameworks) to make sure they are aligned and skills are not missed.

We have also consulted the wider RSE community at RSECon24 about the skills they use, where loads of non-technical/professional skills emerged. 

We have now expanded the remit of the framework to include non-technical as well as technical skills that are used in a wide variety of 
digital professional roles (and not just RSEs) such as researchers, data specialists (stewards, archivists, etc.), RSE group leads, PIs, etc.


### Current Status

- [x] Initial research
- [x] Initial development <-- We are here
- [x] Minimum viable product
- [ ] Alpha release
- [ ] Feature-complete release

#### RSE competency framework

##### Defining the skill set

We have a [draft framework](./_data/skills.json) and a [GitHub issue to track
suggestions](https://github.com/RSEToolkit/rse-competencies-toolkit/issues/39).

If you think skills are missing, needs clarification, or could be reorganised within the framework, please add your
feedback to the [GitHub issue to track suggestions](https://github.com/RSEToolkit/rse-competencies-toolkit/issues/39).

##### Defining the skill levels

We have a [draft document on skill
levels](./skill-levels.md) and a [GitHub issue to track
suggestions](https://github.com/RSEToolkit/rse-competencies-toolkit/issues/62).

#### Developing the website

The [website](https://rsetoolkit.github.io/rse-competencies-toolkit/) is currently a basic proof of concept developed
during the CW23 Hack Day. We need support to develop a website that can:

- Show descriptions of all the skills.
- Display and link the professional development resources curated for each skill.
- Allow people to score their own skills and view their skill wheels.

#### Curating professional development resources

We have a file with [resources for professional development](./_data/resources.csv) mapped to skills in the framework.

If you would like to suggest resources to add to the collection, please add them to the [GitHub issue on
curation](https://github.com/RSEToolkit/rse-competencies-toolkit/issues/44).

#### All GitHub issues

Anyone is welcome to contribute suggestions, feedback, and/or PRs to address any open issues. You can also open a new
issue if your idea is not yet mentioned anywhere else.

### More information

See the [all documents](./all_documents.md) page.

### Project team

See Contributors section below.

You can contact the team at [rse-competencies-toolkit@googlegroups.com](mailto:rse-competencies-toolkit@googlegroups.com).

## Built With

This section is intended to list the frameworks and tools you're using to develop this software. Please link to the home
page or documentatation in each case.

### Related Skills & Competencies Frameworks

- [CSCCE Skills Wheel](https://zenodo.org/record/4437294#.ZFO3F-zMIc1)
- [BCS SFIAplus IT Skills Framework](https://www.bcs.org/it-careers/sfiaplus-it-skills-framework/) and [SFIA v8, the
  current standard](https://sfia-online.org/en/sfia-8/sfia-views/full-framework-view?path=/glance)
- [NIH Competencies Proficiency Scale](https://hr.nih.gov/working-nih/competencies/competencies-proficiency-scale)
- [King's Digital Lab Research Software Careers Learnings](https://zenodo.org/record/2559235)
- [Job Descriptions and Framework for the UCL Centre for Advanced Research Computing (ARC) Research Software Engineer](https://rdr.ucl.ac.uk/articles/model/Job_Descriptions_and_Framework_for_Centre_for_Advanced_Research_Computing_ARC_Research_Software_Engineer/25196066?file=44484410)
- [Research Software Engineer at the Netherlands eScience Center: Job Description](https://zenodo.org/records/7805870)
- [Met Office's Science Professional Skills Framework](https://www.metoffice.gov.uk/research/approach/our-science-professional-skills)
- [Foundational Competencies and Responsibilities of a Research Software Engineer by the German RSE community](https://arxiv.org/pdf/2311.11457)
- [Skills Used by RSEs, by the US-RSE community](https://us-rse.org/wg/education_training/skills/)
- [Skills Base - Skills Management Framework](https://www.skills-base.com/)
- [JISC Digital Capability](https://digitalcapability.jisc.ac.uk/what-is-digital-capability/)
- [Civil Service Competency Framework](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/436073/cscf_fulla4potrait_2013-2017_v2d.pdf)
- [Competencies, training resources and career profiles in computational biology](https://competency.ebi.ac.uk/framework/iscb/3.0)
- [Australian Research Data Commons (ARDC) Digital Research Capabilities and Skills Framework: The Framework and Its Components](https://zenodo.org/records/14188836)
- [Lightcast skills taxonomy](https://lightcast.io/open-skills)
- [UNIVERSE-HPC project skills and pathways](https://www.universe-hpc.ac.uk//assets/slides/ISC24PathwaysBoF-DesignYourPathwayExerciseSheet-A3.pdf)

### Website

- [Jekyll](https://jekyllrb.com/)
- [Chart.js](https://www.chartjs.org/)

## Getting Started for Developers

### Prerequisites

- Latest version of [Ruby](https://www.ruby-lang.org/en/)

### Installation

How to build or install the application.

```sh
git clone git@github.com:RSEToolkit/rse-competences-toolkit.git
cd training
bundle install
```

### Running Locally

How to run the application on your local system.

```sh
bundle exec jekyll serve
```

### Running Tests

No tests as yet.

## Deployment

### Local

See [running locally](#running-locally) above.

### Production

Deployed automatically via GitHub actions.

## Usage

To come after the hack day

## License

Unless otherwise specified on particular materials, all material in this repository is licensed as follows:

- Code is licenced under the [3-clause BSD licence](https://opensource.org/license/bsd-3-clause/).
- Documentation, data and other written material is licensed under the [Creative Commons Attribution
  licence](https://creativecommons.org/licenses/by/4.0/) (CC-BY 4.0).

## Citation

Please cite this work as follows:

```{bibtex}
@article{RSECompetenciesToolkit2023,
  title={RSE Competencies Toolkit},
  author={RSE Competencies Toolkit team},
  journal={GitHub},
  year={2023}
}
```

## Acknowledgements

The initial version of this repository was created during a Software Sustainability Institute Collaborations Workshop
2023 Hack Day. Subsequent development was guided by a number of unconference sessions during RSECon23.

## Contributors

Contributors (in alphabetical order by first name). Collectively the "RSE Competencies Toolkit team".

- Aleksandra Nenadic
- Aman Goel
- Dave Horsfall
- Diego Alonso Álvarez
- Eli Chadwick
- Hannah Williams
- Iain Barrass
- Lieke de Boer
- Martin O’Reilly
- Matthew Bluteau
- Nadine Spychala
- Paul K Korir
- Sean Marshallsay

## Contact

If you'd like to get in touch with the project team - write to us at [rse-competencies-toolkit@googlegroups.com](mailto:rse-competencies-toolkit@googlegroups.com).
