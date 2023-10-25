# Assignment 3 - Part 3.1
## Table of Contents

- [Part 3.1](#part-31)
- [Task](#task-create-first-draft)
- [Stages](#stages)
  - [Stage-1](#stage-1-preparation)
  - [Stage-2](#stage-2-understanding-the-project)
  - [Stage-3](#stage-3-first-draft-of-the-self-assessment)
- [FAQs](#faqs)
- [Links]

## Part 3.1
- It should be submitted before you move to Stage 4 (Intiate discussions with project maintainers).
- You must submit your repository link to the updated security self-assessment document and Github issue.
- The evaluation will be on the first draft of the security self-assessment you and your group create.
- The evaultion will be on the completeness of the threat modeling, understanding of the project and research on the project.

### *Task:* Create first draft
- This assignment is a group project and the groups will be announced in the Class.
- Throughout the assignment you and your group will carry out the role of a *Security Pal* and perform Security Self-assessment for an open source project in CNCF.
- Create first draft of Security Self-assessment for an open source project in CNCF.


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

> [!NOTE]
> This initial stage does not require interaction with project maintainers.

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

> [!IMPORTANT]
> It is recommended you do this stage independently and then compare notes with your teammates. 

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

> [!IMPORTANT]
> It may be useful for the Security Pals to perform a Lightweight Threat Model based on the
[template](https://docs.google.com/document/d/1tuGtKrjcreDFlHcXYCTjLvy3mjyamdQzwCZr6uqFcR4/edit#heading=h.w0tawqz3390z). 
This can help to point out areas where the self assessment needs to be further refined.

> [!IMPORTANT]
> This stage takes up more time and effort, the work can be divided amongst different Security Pals who can work parallelly.

> [!NOTE]
> It's essential to link to the documentation when explaining why an item is considered true.
> This aids future project reviews and clarifications, allowing them to easily reference the documentation.

## FAQS
<details>
<summary> How should I create the Github issue? </summary>

  - Use the template of provided in the resources section to create the Github issue.

</details>

<details>
<summary> How should I create the security self-assessment document? </summary>

  - Use the template of provided in the resources section to create the security self-assessment document.

</details>


<details>
<summary> How can the work be divided among Security Pals for Stage-3? </summary>

  - For instance, one Security Pal could focus on Project Compliance and Secure Development, another could handle Self-assessment use and Security functions and features, and a third could complete the Appendix.

</details>

<details>
<summary> Can I use different threat modeling methods other than "Lightweight Threat Model" to evaluate the project? </summary>

  - Yes, you can use STRIDE, PASTA or anyother suitable threat modeling techniques. But make sure you document it properly and the analysis has to be holistic. 

</details>

<details>
<summary> When should I contact project maintainers during the assessment process? </summary>

  - Reach out to project maintainers as soon as you have a good first draft document. 

</details>
