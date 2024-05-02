Github Issues:
GitHub Issues is a robust project management feature integrated into the GitHub platform, designed to
streamline collaboration, communication, and issue tracking within software development projects.
It serves as a centralized hub for tracking tasks, enhancements, bug reports, and other project-related
activities within a GitHub repository. It provides a structured and organized way for development teams
to manage their workflow, ensuring that issues are identified, discussed, and resolved efficiently.

Steps to Create and Address GitHub Issues
1. Create a new issue in your repository:
i. Go to your GitHub repository.
ii. Click on the "Issues" tab.
iii. Click the "New issue" button.
iv. Fill in the issue title and description.
v. Optionally, assign the issue to a collaborator, apply labels, and set milestones.
2. Assign the issue to a collaborator:
i. Within the issue, use the "Assignees" section to assign the issue to a collaborator.
ii. The assigned collaborator will receive notifications about the issue.
3. Label the issue with appropriate tags:
i. Apply labels to categorize and prioritize issues.
ii. Create and use labels like "bug," "feature," or any relevant labels for your project.
iii. Labels can be added when creating the issue or edited later.
4. Close the issue using a commit message:
i. Make changes to the codebase to address the issue.
ii. In your local repository, commit the changes with a commit message that references the
issue number:
git commit -m "Fix #1: Resolve issue with feature X"
Replace "1" with the actual issue number.
iii. Push the changes to GitHub:
git push origin main
The issue will be automatically closed when the commit is pushed.

5. Optional: Comment and Discuss:
i. Encourage collaboration by adding comments to the issue.
ii. Mention collaborators using @username to notify them.
iii. Discuss the issue, provide additional information, or ask for feedback.
