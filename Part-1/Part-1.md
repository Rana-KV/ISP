# Assignment 3
## Table of Contents

- [Task](#task-perform-a-security-self-assessment-for-a-open-source-project)
- [Part 3.1](#part-31)
- [Stages](#stages)
  - [Stage-1](#stage-1-preparation)
  - [Stage-2](#stage-2-understanding-the-project)
  - [Stage-3](#stage-3-first-draft-of-the-self-assessment)
- [FAQs](#faqs)
- [Links]

## Part 3.1
- It should be submitted before you move to Stage 4 (Intiate discussions with project maintainers).
- The evaluation will be on the first draft of the security self-assessment you and your group create.
- The evaultion will be on the completeness of the threat modeling, understanding of the project and research on the project.

### *Task:* Create a first draft of Security Self-assessment for a open source project
- This assignment is a group project and the groups will be announced in the Class.
- Throughout the assignment you and your group will carry out the role of a *Security Pal* and perform Security Self-assessment for an open source project in CNCF.
- Create a first draft of Security Self-assessment for an open source project in CNCF.


## Stages
### Stage-1: **Preparation**
This marks the initial stage where Security Pals initiate a GitHub issue to monitor their work progress and concurrently 
establish a placeholder for the security self-assessment document.<br>

**Difficulty:** ⭐️☆☆☆☆ <br>
**Time:** ⭐️☆☆☆☆ <br>

- Create a GitHub issue:
  - Create a Github issue in CNCF TAG-Security Github repository to initiate the process.
  - Update the information in the Github issue.<br>

- Review the Project Information:
  - Review available project information and documentation.
  - This includes prior KubeCon talks, webpages, project documentation, etc.<br>
  **Note:** This initial review does not require interaction with project maintainers.

- Create draft security self-assessment document:
  - Fork the CNCF TAG-Security repository.
  - Create a new folder for your project in the assessments/projects folder.  
  - Create a draft document for the security self assessment in your project folder.
  - This document includes metadata details and placeholders for all sections.
  - Update the Metadata section of the document.<br>
  
### Stage-2: **Understanding the Project**
This is the most important part for all Security Pals to internalize and understand for a project.
If the project is interested in examining this portion of the self assessment, then it would also be
helpful for the Security Pals to make the project aware of it at this point. However, the Security
Pals need not wait for a response, and can safely continue to the next stage.<br>

**Difficulty:** ⭐️⭐️☆☆☆ <br>
**Time:** ⭐️⭐️⭐️☆☆ <br>
- Security Pals must understand the overall project at a sufficient level of detail. Before doing more detailed security work, one should understand:
  - Project functionality and typical usage.
  - Roles of involved parties (e.g., sidecar, central server, maintainers).
  - Actions performed (e.g., data collection, query language, software release).
  - Project's goals (e.g., access control, software source control).
  - Project's non-goals (e.g., preventing insider data leaks).
- Complete the following in the Overview section of the self assessment document:
  - About Project
  - Background
  - Actors
  - Actions
  - Goals
  - Non-Goals

**Note:** It is recommended you do this step independently and then compare notes with your teammates. 

### Stage-3: **First draft of the Self Assessment**
At this stage, the Security Pals should have a rough idea of the security goals, non-goals, actors, and actions. 
Now it is time to make a pass over the remaining sections with the existing context.<br>

**Difficulty:** ⭐️⭐️⭐️☆☆ <br>
**Time:** ⭐️⭐️⭐️⭐️⭐️ <br>
- Complete the following sections in the self assessment document:
  - Self assessment use
  - Security functions and features
  - Project compliance
  - Secure development practices
  - Security issue resolution
  - Appendix

It may be useful for the Security Pals to perform a Lightweight Threat Model based on the
[template](https://docs.google.com/document/d/1tuGtKrjcreDFlHcXYCTjLvy3mjyamdQzwCZr6uqFcR4/edit#heading=h.w0tawqz3390z). 
This can help to point out areas where the self assessment needs to be further refined. Other models like STRIDE,
etc. may also be useful here.

**Note:** It is a good practice to link back to the documentation when describing why a certain
item is believed to be true. This is especially important so when the project does a later
examination of this step, if they disagree or need to clarify something, they know where to do
so. So, repeatedly link back to project documentation.
<br>
**Note:** This stage can safely be divided amongst different Security Pals who can work parallelly. One Security Pal could focus on Project Compliance and Secure Development, another
could do Self assessment use and Security functions and features, and a third could complete the Appendix.

## FAQS
- **Note:** Use the template of provided in the resources section to create the Github issue.
- **Note:** Use the template of provided in the resources section to create the security self-assessment document.
