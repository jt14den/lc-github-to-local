---
title: GitHub Pull Requests
teaching: 20
exercises: 0
---
:::::::::::::::::::: questions
- What is a pull request, and why is it important?
- How do I create a pull request to propose changes in GitHub?
- How can I review and merge changes made by myself or others?
:::::::::::::::::::::::::::::

:::::::::::::::::::: objectives
- Understand the purpose of a pull request in GitHub.
- Create a pull request to propose changes to a repository.
- Review and merge changes using GitHub's pull request system.
:::::::::::::::::::::::::::::::

In the previous episode, you created a GitHub repository for ‘mythesis’ with folders and files through several commits. Now, we’ll create a pull request on the ‘mythesis.md’ file. Pull requests let others review changes you've made and allow for tracking and reversing them if needed.

1. Navigate to the ‘mythesis.md’ file and click the pencil icon in the header to edit the file.  
2. Change the no wrap selection to soft wrap for better readability.
3. Make an edit to the ‘mythesis.md’ file (e.g., replace `<text goes here>` with your content).
4. In ‘Commit Changes,’ add a short, imperative commit message (e.g., ‘Fix typo’) and a description if necessary. You can include more details, link issues, or use bullet points. Try to be brief but clear.

Next, select the option to ‘Create a new branch for this commit and start a pull request,’ and leave the default ‘patch’ name for now. Click the ‘Propose file change’ button.

On the following page, you’ll see the option to ‘Open a pull request.’ Click the green ‘Create pull request’ button. Your new pull request will be listed with a #number in the 'Pull requests' tab.

Before merging, you can review the changes by clicking the commit link. The changes will be highlighted in red (old) and green (new). If everything looks good, leave a comment (e.g., "Looks good to me") and click ‘Merge pull request.’ Finally, confirm the merge.

Congratulations, you’ve successfully created and merged your first pull request! You can view the merged request under the ‘Closed’ tab if needed.

::::::::::::::::::::: keypoints
- Pull requests allow others to review and suggest changes to a repository before merging.
- Commit messages should be brief and written in the imperative form (e.g., “Fix typo”).
- GitHub shows changes (diffs) between files in red (original) and green (modified).
- Pull requests can be discussed, reviewed, and merged through GitHub’s interface.
::::::::::::::::::::::::::::::::

