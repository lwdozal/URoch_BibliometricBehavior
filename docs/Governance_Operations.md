# dplPy-for-FOSS Governance and Operations Document

*This is a living document. Changes are expected throughout the life of the project.*

### Table of Contents

1. [Introduction](#introduction)
    - [Project Overview and Objectives](#project-overview-and-objectives)
        - [dplPy](#dplpy)
        - [FOSS Reference Hub](#foss-reference-hub)
    - [Our Team](#our-team)
        - [Organizational Structure](#organizational-structure)
2. [Operations](#operations)
    - [Communications](#communications)
    - [Procedures](#procedures)
3. [Community Practices](#community-practices)
    - [Open Science Commitment](#open-science-commitment)
    - [Land Acknowledgement](#land-acknowledgement)
    - [Diversity Statement](#diversity-statement)
    - [Code of Conduct](#code-of-conduct)
4. [Attribution, Authorship, and Ownership](#attribution-authorship-and-ownership)

## Introduction

This Project Governance document defines operating procedures and rules aimed to clarify and support the involvement of dplPy in FOSS and the FOSS reference hub.

### Project Overview and Objectives

This section highights the dplPy project on its own and its implementation in the FOSS Reference Hub.

#### dplPy

[dplPy](https://opendendro.org/python/) is the Python implementation of the [OpenDendro](https://opendendro.org/) project, an open-source framework that aims to provide [dendrochronologists](https://en.wikipedia.org/wiki/Dendrochronology) with the required analytical software necessary for tree-ring related research. The majority of the code for dplPy was developed by Ifeoluwa Ale, a student Computer Scienctist at the University of Arizona, and supervised by Michele Cosi, Dr. Tyson Swetnam, and Dr. Kevin Anchukaitis. OpenDendro is supervised by Dr. Kevin Anchukaitis, Andy Bunn, Dr. Tyson Swetnam and Dr. Edward Cook.

#### FOSS Reference Hub

The FOSS reference hub is a reference repository for the [Foundational Open Science Skills (FOSS)](https://foss.cyverse.org/) workshop series. Together with dplPy, the aim of this repository is to serve as a reference for the [capstone](https://foss.cyverse.org/final_project/overview/), which FOSS attendees are expected to complete within the duration of the FOSS workshop.

The dplPy project was selected to enhance the FOSS Reference Hub with a reliable codebase, ensuring it mirrors a genuine repository that participants can use as a model when attempting to replicate similar setups for their individual projects.

The goals of the FOSS Reference Hub are to:
- Serve as an exemplary reference for a well structured research object.
- Guide FOSS attendees through weekly exercises designed to progressively enhance their project repositories.

### Our Team

Meet the education team at CyVerse/Data Science Institute:

- **Tyson Swetnam**: Co-PI of CyVerse and Director of Open Science, Institute for Computation and Data-enabled Insight (ICDI) at the University of Arizona
- **Jeff Gillan**: Data Scientist for CyVerse with relative research in the field of GIS/remote sensing.
- **Carlos Lizarraga**: Educator in Computational and Data Science at the University of Arizona Data Science Institute. Carlos' background is in applied research scientist as a Professor from the Physics Department at the University of Sonora, where he taught Computational Physics.
- **Michele Cosi**: Science Analyst for CyVerse with a background in genetics and genomics of rice.
- **Tina Lee**: Head of User Engagement at CyVerse.

With the collaboration of the dplPy team: 

- **Andy Bunn**: Environmental scientist interested in climate and energy from the College of Environment at Western Washington University, founding director of the Institute for Energy Studies, and main writer of OpenDendro software [dplR](https://cran.r-project.org/web/packages/dplR/index.html) and [xDateR](https://andybunn.shinyapps.io/xDateR/). 
- **Edward Cook**: expert in the dendrochronology field and main writer of the tool [ARSTAN](https://www.ltrr.arizona.edu/~sheppard/presession/arsreadme_135.doc). 
- **Kevin Anchukaitis**: Climate scientist, paleoclimatologist, dendrochronologist, faculty member  in Geosciences and the Laboratory of Tree-Ring Research at the University of Arizona, leading the efforts behind the [OpenDendro](https://opendendro.org/) platform.
- **Ifeuwa Ale**: Junior Computer Science student at the University of Arizona and main contributor to the dplPy codebase for OpenDendro.

FOSS will also be hosting the following guest speakers:

- [**Jason Williams**](https://dnalc.cshl.edu/about/staff-bio.html#williams): Assistant Director, Diversity and Research Readiness at the 
DNA Learning Center of Cold Spring Harbor.
- **Wade Bishop**: Professor in the School of Information Sciences at the University of Tennessee-Knoxville. He is the Director of Graduate Studies as well as the Research Data Management Certificate Coordinator

#### Organizational Structure

```
FOSS
├── CyVerse/Data Science Institute
│   ├── Tyson Swetnam 
│   ├── Jeff Gillan
│   ├── Carlos Lizarraga
│   ├── Tina Lee
│   └── Michele Cosi
├── FOSS Reference Hub
│   └── dplPy
│        ├── Kevin Anchukaitis
│        ├── Edward Cook
│        ├── Andy Bunn
│        └── Ifeuwa Ale
└── Guest Speakers
    ├── Jason Williams
    └── Wade Bishop
```

## Operations

In order to ensure well distributed work loads across FOSS and the FOSS teaching materials including the FOSS Reference Hub, we have outlined communications and procedure components in order to maximize effectiveness and efficiency.

### Communications

**Internal communications**: communications within the CyVerse/Data Science Institute team is carried out through private Slack channels (CyVerse, CyVerseLearning, Data7) and Zoom meetings.

**External communications**: communications to the dplPy team is carried out through a private Slack channel (openDendro), whilst communication to the guest speakers is done through email (Wade Bishop) and the CyVerse/CyverseLearning Slack Channel (Jason Williams).

**Note keeping & attendees**: communications to FOSS attendees is achieved through the CyVerseLearning Slack channel. This will allow attendees to share thoughts and notes on lectures and materials during and after the workshop. Note keeping during the workshop is carried out through [HackMD](https://hackmd.io/), which links are shared during the workshop sessions. All workshops will be done through Zoom, creating a virtual classroom environment allowing remote attendees to take part to the workshop. Recordings of these workshop sessions will be made available to attendees through a private YouTube playlist. 

### Procedures

All of the code base required for FOSS, the FOSS Reference Hub and the dplPy project is stored in their respective GitHub repositories:

- [FOSS](https://github.com/CyVerse-learning-materials/foss)
- [FOSS Reference Hub](https://github.com/CosiMichele/foss-reference-hub)
- [dplPy](https://github.com/OpenDendro/dplPy) 

All of these repositories can only be modified by the CyVerse/Data Science Institute team (or the dplPy team regarding the dplPy repository) or through a reviewed [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests). Websites for FOSS ([foss.cyverse.org](https://foss.cyverse.org/)) and OpenDendro ([opendendro.org](https://opendendro.org/)) are created using [MkDocs-Material](https://squidfunk.github.io/mkdocs-material/) and hosted on [GitHub Pages](https://pages.github.com/), built through automated [GitHub Actions](https://github.com/features/actions).

## Community Practices

### Open Science Commitment 

We are committed to Open Science as we operate through transparency, collaboration, and accessibility, guided by the[FAIR (Findable, Accessible, Interoperable, Reusable)](https://www.nature.com/articles/sdata201618) and [CARE (Collective Benefit, Accountability, Responsibility, Equity)](https://www.gida-global.org/care) principles.

Our educational materials and publications are thoughtfully curated to align with Open Science ideals. We seek to empower others to adopt and implement Open Science practices, making research more accessible and reproducible.

### Land Acknowledgement

As part of the University of Arizona, we acknowledge and respect the land and territories on which we are able to perform our duties as educators with the following statement: *We respectfully acknowledge the University of Arizona is on the land and territories of Indigenous peoples. Today, Arizona is home to 22 federally recognized tribes, with Tucson being home to the O’odham and the Yaqui. Committed to diversity and inclusion, the University strives to build sustainable relationships with sovereign Native Nations and Indigenous communities through education offerings, partnerships, and community service.*

### Diversity Statement

We encourage everyone to participate and are committed to building a community for all. 
Although we will fail attimes, we seek to treat everyone as fairly and equally as possible. Whenever a participant has made a mistake, we expect them to take responsibility for it. If someone has been harmed or offended, if you are a witness to an event of this nature, it is your responsibility to both listen carefully and respectfully to the victims, as well as to take action to bring attention to the behaviour, and to make every effort to stop the behaviour. 

It is also our responsibility to do our best to right the wrong. 
Although this list cannot be exhaustive, we explicitly honor diversity in age, gender, gender identity or expression, culture, ethnicity, language, national origin, political beliefs, profession, race, religion, sexual orientation, socioeconomic status, and technical ability. We will not tolerate discrimination based on any of the protected characteristics above, including participants with disabilities.

### Code of Conduct

In conjunction with for using CyVerse cyberinfrastructure, this Code of Conduct applies to all Event participants and their activities while using CyVerse resources and/or attending the Event.

CyVerse is dedicated to providing professional computational research and educational experiences for all of our users, regardless of domain focus, academic status, educational level, gender/gender identity/expression, age, sexual orientation, mental or physical ability, physical appearance, body size, race, ethnicity, religion (or lack thereof), technology choices, dietary preferences, or any other personal characteristic.

When using CyVerse or participating at an Event, we expect you to:

Interact with others and use CyVerse professionally and ethically by complying with our Policies.
Constructively critize ideas and processes, not people.
Follow the Golden Rule (treat others as you want to be treated) when interacting online or in-person with collaborators, trainers, and support staff.
Comply with this Code in spirit as much as the letter, as it is neither exhaustive nor complete in identifying any and all possible unacceptable conduct.
We do not tolerate harassment of other users or staff in any form (including, but not limited to, violent threats or language, derogatory language or jokes, doxing, insults, advocating for or encouraging any of these behaviors). Sexual language and imagery are not appropriate at any time (excludes Protected Health Information in compliance with HIPAA). Any user violating this Code may be expelled from the platform and the workshop at CyVerse's sole discretion without warning.

To report a violation of this Code, directly message a trainer via Slack or email info@cyverse.org with the following information:

Your contact information
Names (real, username, pseudonyms) of any individuals involved, and or witness(es) if any.
Your account of what occurred and if the incident is ongoing. If there is a publicly available record (a tweet, public chat log, etc.), please include a link or attachment.
Any additional information that may be helpful in resolving the issue.

## Attribution, Authorship, and Ownership

FOSS teaching materials and FOSS Reference Hub are made available under the CC BY 4.0 License: https://creativecommons.org/licenses/by/4.0/legalcode.

dplPy and OpenDendro are made available under the GNU General Public Licence v3.0: https://creativecommons.org/licenses/by/4.0/legalcode

We kindly ask to respect the Licences by which this material is developed.