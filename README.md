# Assignment 3
## Table of Contents

- [Task](#task-perform-a-security-self-assessment-for-a-open-source-project)
- [Timeline](#timeline)
- [Assignment Parts](#assignment-3-parts)
  - [Part 3.1](#part-31)
  - [Part 3.2](#part-32)
  - [Part 3.3](#part-33)
- [Stages](#stages)
  - [Stage-1](#stage-1-preparation)
  - [Stage-2](#stage-2-understanding-the-project)
  - [Stage-3](#stage-3-first-draft-of-the-self-assessment)
  - [Stage-4](#stage-4-iteration-with-the-project)
  - [Stage-5](#stage-5-finailization)

## *Task:* Perform a Security Self-assessment for a open source project
- This assignment is a group project and the groups will be announced in the Class.
- As part of the assignment you and your group will perform the role of a *Security Pal* and carry out a Security Self-assessment for a open source project in CNCF.
- You can't work on security Self-assessment for open source projects which are not listed in the project list.
- The opensource project must be a CNCF Project in Graduated or Inccubated or Sandbox stage.

## Timeline
<p align="center">
  <img src="https://github.com/Rana-KV/ISP/blob/main/Assignment_3-Timeline.png" alt="Timeline Image">
</p>

## Assignment-3 Parts
Assignment contains 3 major parts where it will be evaluated:
### Part 3.1
- It should be submitted before you move to Phase 4 (Intiate discussions with project maintainers).
- The evaluation will be on the first draft of the security self-assessment you and your group create.
- The evaultion will be on the completeness of the threat modeling, understanding of the project and research on the project.

### Part 3.2
- It should be submitted before you move to Phase 5 (Submit your Pull Request).
- It will be evaluated after you have discussed with the project maintainers and fixed or improved your security self-assessment.
- The evaluation will be on the feedback from the project maintainers and maturity of the security self-assessment document.
- The evaultion will be on the completeness of the threat modeling, understanding of the project and research on the project.

### Part 3.3
- It should be submitted after completing Phase 5 (Merging your Pull Request).
- It will be evaluated after you have discussed with the TAG-Security Team and fixed or improved your security self-assessment.
- The evaluation will be on the feedback from the project maintainers and maturity of the security self-assessment document.
- The evaultion will be on the completeness of the threat modeling, understanding of the project and research on the project.

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

### Stage-4: **Iteration with the project**
At this stage, the Security Pals need to interact with the project maintianers to refine the document
and resolve points which need clarification. This will consist of a few rounds of iteration where
project maintainers provide further information which makes its way into the self assessment.<br>

**Difficulty:** ⭐️⭐️☆☆☆ <br>
**Time:** ⭐️⭐️⭐️☆☆ <br>
 - Discuss and resolve open questions with project maintainers.
 - Take their inputs into the self-assessment.
 - Finalize the self-assessment.
 - Submit Pull Request to CNCF TAG-security with a finalized security self-assessment document.

The real goal of this process is to accurately document the project’s state. Ideally the project
will also fix documentation issues that arose during the self assessment process, but the focus
on the Security Pals is on getting this clarity, instead of pushing for security changes. (Those
changes and recommendations are handled in the joint assessment which comes after this
process.)
<br><br>
**Note:** This process usually will go in multiple rounds.

### Stage-5: **Finailization**
At this stage, the Security Pals need to interact with the TAG-Security reviewers to further refine the document
and resolve points which need clarification. This will consist of a few rounds of iteration where
TAG-Security reviewers provide feedback which needs to be implemented in the self assessment.<br>

**Difficulty:** ⭐️⭐️☆☆☆ <br>
**Time:** ⭐️⭐️⭐️☆☆ <br>

- Fix self assessment based on feedback from TAG-Security reviewers
- Merge the Pull Request.
