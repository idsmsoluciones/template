## Workflow for Contributing to the Project

1. **Create an Issue:**
   - Always create an issue before starting any task. Clearly explain what you want to do or change and provide a rationale for it.
   - Use the issue to discuss the task with other team members and gather feedback.

2. **Create a Branch:**
   - Once the issue is approved, create a new branch from the "dev" branch. Name the branch with the issue number and a short description of the task.
   - Example: `git checkout -b 123_add-new-feature dev` for issue #123 related to adding a new feature.
   - Keep your branch focused on a specific task to maintain clarity and ease of review.

3. **Implement the Task:**
   - Work on the task in the created branch, following the guidelines and requirements mentioned in the issue.
   - Keep the commits concise, logical, and well-documented to ensure easy understanding during review.
   - For each commit, start the commit message with the issue number followed by a brief comment on the change.
   - Example: `123 Implement new feature XYZ` for issue #123 related to implementing a new feature.

4. **Testing and Local Review:**
   - Before merging, test the changes locally to verify that the implemented task is working as expected.
   - Review the changes locally to ensure they meet the project's standards and requirements.

5. **Create a Pull Request (PR):**
   - Once the task is complete, create a Pull Request (PR) to merge your branch into the "dev" branch.
   - In the PR description, reference the related issue and provide a brief overview of the changes.
   - Request reviews from team members to ensure the quality of your code.

6. **Rebase and Clean Up:**
   - Address the feedback received during the review process and make any necessary changes in your branch.
   - Before the final merge, rebase your branch on the latest "dev" branch to keep it up to date.
   - Squash or clean up your commits to maintain a clean commit history.

7. **Review Process:**
   - The PR must undergo at least one review by another team member before it can be merged.
   - Reviewers will provide feedback, suggestions, and any necessary changes to improve the code quality.

8. **Merge to Dev:**
   - Once the PR has been reviewed and approved, it can be merged into the "dev" branch.
   - Ensure that the "dev" branch is updated to reflect the latest changes.

9. **Release to Main:**
   - Periodically, when the "dev" branch contains a set of completed and tested features, create a Pull Request to merge "dev" into "main" for a release.
   - The release Pull Request should be well-documented with all the new features and changes included in the release.

10. **Close the Issue:**
   - After the PR is successfully merged, close the related issue to mark it as resolved.
   - Optionally, add any relevant additional notes or documentation.

### Additional Notes:
- Encourage communication and collaboration among team members during the entire process.
- Consider setting up automated tests to ensure code quality and functionality.
- Use code linting and formatting tools to maintain a consistent code style.
- Document the workflow and guidelines for newcomers to ease the onboarding process.

Remember, you can customize and expand this workflow to fit your project's specific needs. Good luck with your contributions!
