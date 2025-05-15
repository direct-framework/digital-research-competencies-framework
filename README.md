# DIgital REsearch CompeTencies (DIRECT) Framework

## About

This project aims to define a skills and competencies framework to help us classify and describe technical and non-technical skills we use in our different roles as researchers, RSEs, data specialists, RSE group leads, PIs, etc., along with lists of tools/methods/behaviours to demonstrate skills and training materials that can help us gain a particular skill.

A [sister project](https://github.com/direct-framework/direct-webapp) works on implementing a Django webapp to enable practical use of the framework - to browse the skills and competencies, self-assess and create individual skill profiles as “competency wheels”, compare profiles across a team, define template skills for different digital roles (e.g. a data archivist, a data scientists or an RSE with HPC specialism) and other use cases.

[![Watch the video of project lead Dave Horsfall describing the DIRECT Framework, how it identifies skills and defines development pathways for anyone working in research software, serving as an important tool to help with career progression](https://github.com/direct-framework/digital-research-competencies-framework/blob/main/images/promo-video-screenshot.png?raw=true)](https://www.youtube.com/watch?v=NpQFhwqBgg4)


## History

This repository was originally created from the work that happened at the Software Sustainability Institute's [Collaborations Workshop 2023](https://www.software.ac.uk/workshop/collaborations-workshop-2023-cw23-0) Hack Day.

The idea was to construct a resource on technical skills that is for the RSE community and curated by the RSE community, along with training materials that can help people gain a particular skill, and visualise people's individual skill profiles as "competency wheels".

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

## Competency framework

### Defining and classifying skills

Skills and competencies are described in the [framework file](./_data/skills-competencies-framework.json) and we have a [GitHub issue to track
suggestions](https://github.com/RSEToolkit/rse-competencies-toolkit/issues/39).

If you think skills are missing, needs clarification, or could be reorganised within the framework, please add your
feedback to the [GitHub issue to track suggestions](https://github.com/direct-framework/digital-research-competencies-framework/issues/39).

### Defining the skill levels

We have a [document defining skill
levels](./skill-levels.md) and a [GitHub issue to track
suggestions](https://github.com/direct-framework/digital-research-competencies-framework/issues/62).

The skill levels describe a scale to help measure/describe ability to demonstrate a particular skill (i.e. an individual’s competency level for a particular skill).

### Curating professional development resources

We have a file with [resources for professional development](./_data/resources.csv) mapped to skills in the framework.

If you would like to suggest resources to add to the collection, please add them to the [GitHub issue on
curation](https://github.com/direct-framework/digital-research-competencies-framework/issues/44).

### Related skills & competencies frameworks

We reviewed a number of related work into defining skills and competencies:

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


## Contributors

Current project team (in alphabetical order by first name):

- Adrian D'Alessandro
- Aleksandra Nenadic
- Aman Goel
- Becky Osselton
- Connor Aird
- Dave Horsfall
- Emma Hogan
- Eli Chadwick
- Gabriel Hanganu
- Matt Craddock
- Phil Reed
- Sam Bland
- Tamora James

### Past contributors

In alphabetical order by first name:

- Hannah Williams
- Diego Alonso Álvarez
- Matthew Bluteau

CW25 hack day team working on the project (in alphabetical order by first name):

- Adrian D’Alessandro
- Aleksandra Nenadic
- Andrew Gait
- Bryn Ubald
- Connor Aird
- Tamora James
- Patricia Loto
- Phil Reed
- Ryan Smith

CW25 workshop 2.4 saw additional contributions to the framework (in alphabetical order by first name):

- Ella Kaye
- Jonathan Cooper
- Samantha Wittke
- Sarah Gibson 
- Toby Hodges 

Original CW23 hack day team that started the project (in alphabetical order by first name):

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

## Contributing

Anyone is welcome to contribute suggestions, feedback, and/or PRs to address any open issues. You can also open a new
issue if your idea is not yet mentioned anywhere else.

## Contact

If you'd like to get in touch with the project team - write to us at [rse-competencies-toolkit@googlegroups.com](mailto:rse-competencies-toolkit@googlegroups.com).

We also use [#rse-competencies-toolkit channel](https://ukrse.slack.com/archives/C05CY0YFWEL) under RSE Community Slack (ukrse.slack.com).

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

The initial version of this repository was created during the Software Sustainability Institute Collaborations Workshop
2023 Hack Day. Subsequent development was guided by a number of unconference sessions and contributions by RSE community members during RSECon23, RSECon23 and CW25.

