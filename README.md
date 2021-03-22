# Guide-to-publishing
This Guide is for CoST Secretariats, their partners, and development teams to facilitate the documentation process of digital tools that have proven to work in specific contexts and have the potential to be replicated.

# Table of Contents

- [Introduction](#introduction)
- [Documentation on GitHub](#Documentation-on-GitHub)
  - [What is the documentation used for?](#What-is-the-documentation-used-for?)
  - [Whom is the documentation aimed at?](#Whom-is-the-documentation-aimed-at?)	
  - [Where is the documentation saved, and what format should I use?](#Where-is-it-saved,-and-what-format-should-I-use?)	
  - [What information should I include in the README file?](What-information-should-I-include-in-the-README-file?)	
- [Template for CoST Digital Tools](#Template-for-CoST-Digital-Tools)	
  - [Description and Context](#Description-and-Context)	
  - [User Guide](#user-guide)	
  - [Installation Guide](#installation-guide)	
  - [How to Contribute](#how-to-contribute)
  - [Code of Conduct](#code-of-conduct)
  - [Authors](#authors)
  - [Additional Information](#additional-information)
  - [License](#license)
  - [Limitation of responsibilities](#limitation-of-responsibilities)

## Introduction 
 [Infrastructure Disclosure Platforms (IDP)](https://github.com/infrastructure-disclosure-platforms) is a CoST- The Infrastructure Transparency Initiative- effort to bring in open-source software that meets the needs of governments, private sector, and civil society to improve transparency and accountability in public infrastructure.

CoST International Secretariat has established a repository in GitHub to share and simplifyreuse of digital solutions created by CoST members. IDP grants access to a set of tools that work complementary including disclosure platforms and analytical dashboards.

In this context, this Guide is intended to CoST Secretariats, their partners and IT developer
teams to facilitate the documentation process of digital solutions that have proven to work inspecific contexts and have the potential to be replicated.

By creating the IDP, CoST seeks ultimately to promote knowledge sharing and learning across its membership and beyond to and improving lives.
help delivering quality infrastructure, strengthening economies, and improving lives.


## Documentation on GitHub

### A guide for CoST Members and other potential contributors
The documentation is a section of the CoST GitHub Repository that presents the tool that has been uploaded. This section should explain what the tool is, how it is used, and how it can be reused or adapted. The main file is in README.md format, where all documentation must be listed and developed.

### What is the documentation used for?

The documentation is used to explain to new developers what the tool is, how it can be used, and how to install it. It is generally the first technical document another developer will turn to reuse the digital tool. It is recommended to clearly and concisely document digital tools created by CoST Members to increase their reuse. The documentation should answer the following questions:
  - What does the digital tool do?
  - How does it work?
  - How the digital tool can be reinstalled?
  - Under what terms this tool can be used?

A common practice is to create a text document in the root directory named README.txt. This file is the main document that contains documentation or directs users to other documentation resources.

### Whom is the documentation aimed at?

The documentation’s main audience is developers. However, the user guide section is aimed at the tool’s end users. If this section is very complex, it is good practice to dedicate a specific document to it, although the README file should specify the existence of this extra documentation.

### Where is the documentation saved, and what format should I use?

It is saved in a file named README.md. It should be visible in the digital tool’s main folder, as well as in markdown format. If there is extensive documentation aimed less tech- confidence users, it is recommended to save this documentation in a separate document, although it is always good practice to mention and refer to it in the README.md file.

### What information should I include in the README file?	

The README file should contain the information required to use and install the tool. There is no predefined format, but to have a complete README file, CoST Members should at least include the most common sections listed below (*Attribution: Adapted from the Code for Development*).

- ***Description and context***: Description of its features, the context in which it was developed, and the development problems it helped solve.
- ***User guide***: Step-by-step guide aimed at showing the end user how to start using the digital tool. This information can go in a separate document if it is too long, but it is good practice to mention it in the documentation.

- ***Installation guide***: Installation instructions for reusing and configuring the digital tool. This section is aimed at developers. In another subsection, documentation related to other digital tools (libraries, frameworks, database access and licenses for each resource) should be specified, if necessary.
- ***Creators***: Section crediting those who collaborated on creating the tool.
- ***License***: Permissions granted to third parties to reuse the digital tool. CoST Members or other partners should specify the type of license and refer to the license.txt or licencia.txt file with the license content.
- ***How to contribute***: Section which explains the process for contributing to projects to new developers.
- ***Code of conduct***: The code of conduct establishes the social norms, rules, and responsibilities that individuals and organizations must follow when interacting with the IDP or its community in any way. The GitHub platform rewards and helps repositories that have this file This can be started from a template they suggest when creating CODE_OF_CONDUCT.md. based on the content suggested by Contributor Covenant.
- ***Badges***: Badges are small images embedded in README.md which clearly and concisely specify the tool’s status. There are badges for development status, number of downloads, version, social media, etc.
- ***Version***: Indicates a list of the versions of the digital tool, as well as the features
added to each version.


## Template for CoST Digital Tools	

### Description and Context	
 >Start the README file with a brief description of the functionality and the context for use of the digital tool. Be specific and concise.
 
### User Guide	

>Explain the basic steps of how to use the digital tool. This is a great place to share screen captures or GIFs 
which could help others understand handling the tool.


### Installation Guide	

>Provide a step-by-step guide for how to install the digital tool. In this section, it is recommended to explain the file structure and all the modules included in the system.
Depending on the kind of digital tool CoST members can have, the level of complexity for installation may vary. It might be necessary to install additional components upon which the tool is dependent. If this is the case, be sure to add the next section.

> *Dependencies*
Describe any external resources which create a dependency for the reuse of the digital tool, such as libraries, frameworks, access to databases, and the corresponding licenses required to access each of these. Listing the latest version of these external resources that has been
tested for use together with the digital tool is considered a best practice.
You can use this style format to differentiate the installation commands.

>[This tool](https://github.com/EL-BID/SmartMap) offers a good example of a description of dependencies.


### How to Contribute	
Infrastructure Disclosure Platforms (IDP) is CoST- the Infrastructure Transparency Initiative- effort to support CoST Members and other partners to contribute, explore and reuse open- source digital tools, which can be used in the design and implementation of the CoST disclosure journey aiming to improve transparency and accountability in the infrastructure sector around the world.
CoST believes that open-source codes developed by our members or partners should be publicly available to help us to contribute to delivering quality infrastructure, strengthening economies, and improving lives.
 
Therefore, CoST encourages those who contribute to the improvement of these digital tools, to share them with the IPD manager. If when reusing this digital tool, you consider that:
  - Have added some new functionality with which you add value for more people to reuse,
  - Have made the tool more versatile to support new updates,
  - Have fixed some existing bugs,
  - Or have simply improved the user interface or documentation of it.
 CoST encourages you to return the progress made to the repository. Follow these steps to contribute to the digital tool:
1. Fork the repository.
2. Develop the new functionality or make the changes you create that add value to
the tool.
3. Make a "pull request" documenting in detail the proposed changes in the
repository.
4. In such case, your name will be registered in the list of attributions.
If you have not contributed to the repository, but the tool has been helpful to you, we at CoST would love to hear the experience. Tell us about your experience in an Issue or via email to opencode@infrastructuretransparency.org.

#### Attributions
Tell us in the "pull request" your username and organization to add it to the list of contributions in the Readme.md.

### Code of Conduct	
#### Our Pledge
In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to making participation in our portal and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual
identity and orientation.

#### Our Standards
Examples of behaviour that contributes to creating a positive environment include:
- Using welcoming and inclusive language
- Being respectful of differing viewpoints and experiences
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards other community members

Examples of unacceptable behaviour by participants include:

- The use of sexualized language or imagery and unwelcome sexual attention or advances
- Trolling, insulting/derogatory comments, and personal or political attacks
- Public or private harassment
- Publishing others' private information, such as a physical or electronic address, without explicit permission
- Other conduct which could reasonably be considered inappropriate in a professional setting.

#### Our Responsibilities
IDP maintainers and contributors are responsible for clarifying the standards of acceptable behaviour and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behaviour.

The IDP maintainers have the right and responsibility to remove, edit, or reject comments,
commits, code, wiki edits, issues, and other contributions that are not aligned to this Code of Conduct, or to ban temporarily or permanently any contributor for other behaviours that they deem inappropriate, threatening, offensive, or harmful.

#### Scope
This Code of Conduct applies both within IDP and CoST repositories spaces and in public spaces when an individual is representing CoST or its community. Examples of representing CoST or community include using an official e-mail address, posting via an official social media account, or acting as an appointed representative at an online or offline event. Representation of a CoST may be further defined and clarified by the IDP maintainers.

#### Enforcement
Instances of abusive, harassing, or otherwise unacceptable behaviour may be reported by contacting this repository's maintainer or at opencode@infrastructuretransparency.org

All complaints will be reviewed and investigated and will result in a response that is deemed necessary and appropriate to the circumstances. The CoST team is obligated to maintain confidentiality regarding the reporter of an incident.

The IDP maintainers who do not follow or enforce the Code of Conduct may face temporary or permanent repercussions as determined by CoST.

*Attribution: This Code of Conduct is adapted from the Contributor Covenant, version 1.4, available at http://contributor-covenant.org/version/1/4.*

### Authors

> Name the original authors of the tool here. Please consult with all parties before publishing their name or contact information, such as email addresses. Some may also choose to direct contacts or questions to their social media profiles.

### Additional Information	
>  This section can offer more information about the context of the creation of the digital tool, additional links or other resources mentioning the tool, related projects, or case studies where the technology has been used.

### License	
GNU GPLv3
Permissions of this strong copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights.

### Limitation of responsibilities	
CoST is not responsible, under any circumstance, for damage or compensation, moral or patrimonial; direct or indirect; accessory or special; or by way of consequence, foreseen or unforeseen, that could arise:
1. Under any concept of intellectual property, negligence, or detriment of another part theory.
2. Following the use of this Digital Tool, including, but not limited to defects in the Digital Tool, or the loss or inaccuracy of data of any kind. The foregoing includes expenses or damages associated with communication failures and / or malfunctions of computers, linked to the use of this Digital Tool.

