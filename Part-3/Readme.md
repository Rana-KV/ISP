# Assignment 3.3
For Assignment-3: Part-3, follow these steps:

- **Initiate Pull Request:**
  - Sync your Fork.
  - Squash your commits.
  - Add the contributors (you can add your team members).
  - Submit the work through a Pull Request.

- **Document Evolution:** Refine the document you have in Part-2. There are two types of feedback to anticipate: one from the project maintainers and the other from TAG-Security. Feedback from project maintainers will aim to accurately represent the project's security posture, while TAG-Security will focus on enhancing the document's coverage and quality. Since some of the project haven't completely provided their feedback, expect ongoing feedback from both these sources.

- **Fix feedback:** The main goal of Part-3 is to finalize the document by addressing all feedback received from both project maintainers and TAG-Security. Your Team has to implement any changes necessary to address the feedback.

- **Action Items:** Based on the insights from your team's Security Self-Assessment, determine and initiate necessary action items. This may include addressing security vulnerabilities or implementing suggested improvements in the project or development pipeline. Consider creating a GitHub Issue with the project maintainers to specifically address these issues you brought up.

> [!IMPORTANT]
> Don't open multiple PRs. Open only one PR per Project and follow the format mentioned in FAQs.


> [!NOTE]
> These steps are crucial for finishing your Assignment 3, security self-assessment document.


> [!IMPORTANT]
> Adding your team members as co-authors during your commit squash will be curcial to provide them credit for the PR. You can't do it later.
> Perform these steps carefully as you can't revert the changes.

Evaluation will be based on your team's proficiency in incorporating feedback and finalizing the document.
Your project maintainer's feedback will also be considered, we will send out feedback forms to project maintainers soon.

## FAQS
<details>
<summary> How do I sync my Fork? </summary>

- There are number of ways one can sync his fork to the main repository.

  - Can be done easily through GUI of Github.

  - The **"Sync Fork"** Option in the Github helps to Sync your fork with the main Repository.

  - Don't Submit your PR without Syncing your Fork.
  - A proper Fork sync would look something like the below image.
<p align="center">
  <img src="https://github.com/Rana-KV/ISP/blob/main/Part-3/Capture_513.PNG" alt="Deadlines">
</p>

</details>

<details>
<summary> How do I squash my commits? </summary>

- There are number of ways one can squash commit history using different tools.
  - Github desktop can also be used to do it. [Link](https://docs.github.com/en/desktop/managing-commits/squashing-commits-in-github-desktop)

- Once you squash the commit history it's gone for ever.

- You can add contributors to the squash commit while creating it

- Later submit the squashed commit for Pull Request.

</details>

<details>
<summary> What should be the Pull Request Name and content? </summary>

- Title of the Pull Request must be **"<Project_Name> Project Security Self-Assessment - Security Pals"**

- Keep the Pull Request contents simple, **"Created and added first draft for <Project_Name> Project Security Self-Assessment."**

- Additonally add a request for feedback, **"Please feel free to share your feedback on the security self-assessment."**

</details>

<details>
<summary> How should I add my Teammates as co-authors for the Pull Request? </summary>

- If you've already made a pull request but forgot to add co-authors in the commit, you'll need to update your commit history and then update the pull request. Here's a step-by-step guide on how to do it:

  - Rewrite the Commit History:
    - First, ensure you are on the correct branch where the commit was made.
    - Use the git commit --amend command to amend the previous commit. This allows you to edit the commit message where you can add the co-authors.
    - In the commit message editor that opens, add the co-author credits at the end of the commit message. The format for adding a co-author is: **"Co-authored-by: name <name@example.com>"**
    - Save and close the editor. This will amend your last commit to include the co-authors.

  - Force Push the Updated Commit:
    - Since you've amended a commit that's already been pushed, you'll need to force push to update the commit on the remote repository.
    - Use the command git push --force to force push the changes. This command rewrites the history on the remote branch.
    - Be aware that force pushing can potentially cause problems for others who are working on the same branch, so it's generally a good idea to communicate with your team before doing this.

  - Update the Pull Request:
    - If your pull request was made from the branch where you amended the commit, the pull request will automatically be updated with the new commit once you force push.
    - There's no need to create a new pull request as GitHub will recognize the updated commits.

  - Check the Pull Request:
    - After force pushing, check the pull request on GitHub to ensure that it reflects your changes, including the added co-authors. 
