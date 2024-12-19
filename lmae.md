GitGitter

GitGitter is a powerful Visual Studio Code extension designed to enhance your coding workflow by providing detailed tracking and logging of code changes. With GitGitter, you can monitor your Git commits, capture relevant metadata, and organize this information in a structured manner. Whether you're a solo developer or part of a team, GitGitter ensures that you stay productive, organized, and well-informed about your project's history.

Features

Detailed Commit Logs

Track commit messages, authors, timestamps, and associated file changes.

Fetch metadata directly from your Git repository to maintain an up-to-date history.

Task Log Management

Create and manage task logs to document your coding tasks and progress.

Ensure your development process is well-documented and easy to reference.

Repository Insights

Access detailed file change information, including file names, paths, and commit IDs.

Automatically link commit details to the corresponding remote repository.

Streamlined Workflow

Enhance productivity with features tailored to make code tracking effortless.

Keep a comprehensive overview of your development timeline.

Insert GIF/Video Demo: Showcase detailed commit logs and task management in action.

Data Collected and Usage

GitGitter requires access to specific data to function effectively:

GitHub Username: Used to identify the user and associate commits with their GitHub profile.

Remote Repository and Files: Accessed to fetch commit metadata and file change details.

Git Token: Used to create and update a single repository for commit tracking purposes.

Local Repository: Analyzed to retrieve commit logs and changes in the current working folder.

What GitGitter Does with This Data:

Commit Tracking:

Executes Git commits with user-provided messages.

Retrieves commit logs from the local repository.

Repository Management:

Creates a dedicated repository to store commit history.

Updates the repository with structured commit data, including:

File names and paths.

Links to the remote repository's commit history.

Commit metadata such as timestamps and authors.

Data Stored in the Dedicated Repository:

Names of files changed in each commit.

URLs linking to the files in the remote repository.

Commit IDs and their corresponding remote repository links.

Insert GIF/Video Demo: Highlight how GitGitter creates and updates the dedicated repository.

Installation

Open the Extensions view in Visual Studio Code (Ctrl+Shift+X).

Search for "GitGitter".

Click "Install".

Insert GIF/Video Demo: Show the installation process and initial setup.

Getting Started

Open a Git-enabled project in Visual Studio Code.

Use GitGitter commands from the Command Palette (Ctrl+Shift+P).

Follow the prompts to configure your GitHub token and repository.

Insert GIF/Video Demo: Demonstrate the initial configuration and first commit tracking.

Limitations

GitGitter will only create and update one dedicated repository for commit tracking.

It requires a GitHub token to push data to the repository.

Local repository access is necessary to retrieve commit and file change information.

Privacy and Security

GitGitter is designed with privacy and security in mind:

Minimal Data Usage: Only collects data necessary for commit tracking.

Dedicated Repository: All collected data is stored in a single repository created by the extension.

Secure Access: Uses your GitHub token to securely create and update repositories.

Support and Feedback

If you encounter any issues or have suggestions for improvement, please visit our GitHub Issues page.

Insert GIF/Video Demo: Provide a walkthrough of submitting feedback or issues.

License

This extension is licensed under the MIT License.

Release Notes

v1.0.0

Initial release with core features including commit tracking, repository creation, and task log management.

Insert GIF/Video Demo: Showcase new features in this release.