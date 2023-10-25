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
- As part of the assignment you and your group will carry out the role of a *Security Pal* and perform Security Self-assessment for an open source project in CNCF.
- You can't work on security Self-assessment for open source projects which are not listed in the project list.
- The opensource project must be a CNCF Project in Graduated, Inccubated or Sandbox stage.

## Timeline
<p align="center">
  <img src="https://github.com/Rana-KV/ISP/blob/main/Assignment_3-Timeline.png" alt="Timeline Image">
</p>

## Assignment-3 Parts
Assignment contains 3 major parts where it will be evaluated:
### Part 3.1
- It should be submitted before you move to Stage 4 (Iteration with the project).
- The evaluation will be on the first draft of the security self-assessment you and your group create.
- The evaultion will be on the completeness of the threat modeling, understanding of the project and research on the project.

### Part 3.2
- It should be submitted before you move to Stage 5 (Finailization).
- It will be evaluated after you have discussed with the project maintainers and fixed or improved your security self-assessment.
- The evaluation will be on the feedback from the project maintainers and maturity of the security self-assessment document.
- The evaultion will be on the completeness of the threat modeling, understanding of the project and research on the project.

### Part 3.3
- It should be submitted after completing Stage 5 (Finailization).
- It will be evaluated after you have discussed with the TAG-Security Team and fixed or improved your security self-assessment.
- The evaluation will be on the feedback from the project maintainers and maturity of the security self-assessment document.
- The evaultion will be on the completeness of the threat modeling, understanding of the project and research on the project.
## Stages
### Stage-1: **Preparation**
This marks the initial stage where Security Pals initiate a GitHub issue to monitor their work progress and concurrently 
establish a placeholder for the security self-assessment document.<br>

**Difficulty:** ⭐️☆☆☆☆ <br>
**Time:** ⭐️☆☆☆☆ <br>

<details>
<summary> More Details </summary>

- Create a GitHub issue:
  - Create a Github issue in CNCF TAG-Security Github repository to initiate the process.
  - Update the information in the Github issue.<br>

- Review the Project Information:
  - Review available project information and documentation.
  - This includes prior KubeCon talks, webpages, project documentation, etc.<br>

- Create draft security self-assessment document:
  - Fork the CNCF TAG-Security repository.
  - Create a new folder for your project in the assessments/projects folder.  
  - Create a draft document for the security self assessment in your project folder.
  - This document includes metadata details and placeholders for all sections.
  - Update the Metadata section of the document.<br>
</details>

### Stage-2: **Understanding the Project**
This is the most important part for all Security Pals to internalize and understand for a project.
If the project is interested in examining this portion of the self assessment, then it would also be
helpful for the Security Pals to make the project aware of it at this point. However, the Security
Pals need not wait for a response, and can safely continue to the next stage.<br>

**Difficulty:** ⭐️⭐️☆☆☆ <br>
**Time:** ⭐️⭐️⭐️☆☆ <br>

<details>
<summary> More Details </summary>

- Security Pals must understand the overall project at a sufficient level of details like:
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

</details>

### Stage-3: **First draft of the Self Assessment**
At this stage, the Security Pals should have a rough idea of the security goals, non-goals, actors, and actions. 
Now it is time to make a pass over the remaining sections with the existing context.<br>

**Difficulty:** ⭐️⭐️⭐️☆☆ <br>
**Time:** ⭐️⭐️⭐️⭐️⭐️ <br>

<details>
<summary> More Details </summary>

- Complete the following sections in the self assessment document:
  - Self assessment use
  - Security functions and features
  - Project compliance
  - Secure development practices
  - Security issue resolution
  - Appendix

</details>

### Stage-4: **Iteration with the project**
At this stage, the Security Pals need to interact with the project maintianers to refine the document
and resolve points which need clarification. This will consist of a few rounds of iteration where
project maintainers provide further information which makes its way into the self assessment.<br>

**Difficulty:** ⭐️⭐️☆☆☆ <br>
**Time:** ⭐️⭐️⭐️☆☆ <br>


<details>
<summary> More Details </summary>

 - Discuss and resolve open questions with project maintainers.
 - Take their inputs into the self-assessment.
 - Finalize the self-assessment.
 - Submit Pull Request to CNCF TAG-security with a finalized security self-assessment document.

The real goal of this process is to accurately document the project’s state. Ideally the project
will also fix documentation issues that arose during the self assessment process, but the focus
on the Security Pals is on getting this clarity, instead of pushing for security changes. (Those
changes and recommendations are handled in the joint assessment which comes after this
process.)
<br>

**Note:** This process usually will go on for multiple iterations.

</details>

### Stage-5: **Finailization**
At this stage, the Security Pals need to interact with the TAG-Security reviewers to further refine the document
and resolve points which need clarification. This will consist of a few rounds of iteration where
TAG-Security reviewers provide feedback which needs to be implemented in the self assessment.<br>

**Difficulty:** ⭐️⭐️☆☆☆ <br>
**Time:** ⭐️⭐️⭐️☆☆ <br>

<details>
<summary> More Details </summary>

- Fix self assessment based on feedback from TAG-Security reviewers
- Merge the Pull Request.

</details>
