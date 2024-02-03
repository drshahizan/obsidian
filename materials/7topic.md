<a href="https://github.com/drshahizan/obsidian/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/obsidian" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/obsidian/network/members"><img src="https://img.shields.io/github/forks/drshahizan/obsidian" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/obsidian/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/obsidian" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/obsidian"><img src="https://img.shields.io/github/issues/drshahizan/obsidian" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/obsidian/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/obsidian?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2obsidian&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

# Collaboration and Version Control

## Collaborative writing in Obsidian.md
Collaborative writing in Obsidian.md can be facilitated through various strategies and tools. While Obsidian itself does not have built-in collaborative features, you can use external services and practices to collaborate effectively. Here's a guide on collaborative writing in Obsidian.md:

### 1. **Version Control with Git:**
   - Initialize a Git repository within your Obsidian vault to enable version control.
   - Collaborators can clone the repository, make changes, and submit pull requests for review.

### 2. **Hosting on GitHub or GitLab:**
   - Host your Obsidian vault on GitHub or GitLab for easy collaboration.
   - Collaborators can clone the repository, make changes, and contribute to the shared knowledge base.

### 3. **Obsidian Sync (for Real-Time Collaboration):**
   - If using Obsidian Sync, collaborators can work on the same vault simultaneously.
   - This provides real-time collaboration, but conflicts may arise, and conflict resolution is manual.

### 4. **Shared Folder on Cloud Storage:**
   - Store your Obsidian vault in a shared folder on cloud storage services like OneDrive, Google Drive or Dropbox.
   - Collaborators can access and make changes to shared notes.

### 5. **Communication and Coordination:**
   - Use external communication tools (e.g., Slack, Discord, Microsoft Teams) for real-time discussion and coordination.
   - Discuss changes, resolve conflicts, and share updates through these platforms.

### 6. **Establish Collaboration Guidelines:**
   - Define clear collaboration guidelines, including version control procedures and communication protocols.
   - Document these guidelines in a shared document within your Obsidian vault.

### 7. **Use Markdown for Compatibility:**
   - Collaborators should be familiar with Markdown syntax for consistent formatting.
   - Markdown is plain text, ensuring compatibility across different platforms and editors.

### 8. **Collaborate on Specific Projects or Notes:**
   - Assign specific projects or notes to different collaborators to avoid conflicts.
   - Clearly define responsibilities and ownership of specific sections.

### 9. **Frequent Backups:**
   - Regularly back up your Obsidian vault, especially before major collaborative sessions.
   - This helps prevent data loss in case of conflicts or accidental deletions.

### 10. **Review Changes and Merge Carefully:**
   - When collaborating using version control, review changes made by collaborators before merging.
   - Resolve conflicts carefully to avoid data loss or inconsistencies.

### 11. **Include Timestamps or Author Tags:**
   - Consider including timestamps or author tags within your notes to track changes.
   - This provides visibility into who made specific edits and when.

### 12. **Regular Sync Meetings:**
   - Schedule regular sync meetings with collaborators to discuss progress, address concerns, and plan future work.

### 13. **Use Commenting Features (if available):**
   - Some cloud storage platforms offer commenting features.
   - Collaborators can leave comments on specific notes for discussions and feedback.

### 14. **Shared Reference Manager (if applicable):**
   - If using a reference manager, ensure collaborators have access to the shared reference library.
   - Coordinate on citation styles and bibliographic data.

### 15. **Community Support and Resources:**
   - Engage with the Obsidian community forums or other collaborative writing communities for insights and tips.

By implementing these strategies, you can enhance collaborative writing in Obsidian.md, whether working on shared projects, research, or knowledge management. Regular communication and a well-defined collaboration process are key to successful collaboration in a Markdown-based environment.

## Version control using GitHub and plugins

Version control using GitHub in combination with Obsidian.md can be achieved by utilizing Git for tracking changes and GitHub for hosting the repository. Additionally, community-developed plugins for Obsidian can enhance version control features. Here's a step-by-step guide:

### Setting Up Version Control with GitHub:

1. **Create a GitHub Repository:**
   - Create a new repository on GitHub to host your Obsidian vault.
   - Initialize the repository with a README file or other initial content.

2. **Clone the Repository:**
   - Copy the repository URL from GitHub.
   - Open a terminal or command prompt on your local machine.
   - Navigate to the directory where you want to clone the repository.
   - Run the following command:
     ```bash
     git clone <repository_url>
     ```

3. **Initialize Git within Obsidian Vault:**
   - Open Obsidian and navigate to your newly cloned repository.
   - Inside the Obsidian vault directory, initialize a Git repository:
     ```bash
     git init
     ```

4. **Stage and Commit Changes:**
   - Make changes to your notes within Obsidian.
   - Open the terminal/command prompt in the Obsidian vault directory.
   - Stage changes using:
     ```bash
     git add .
     ```
   - Commit changes using:
     ```bash
     git commit -m "Your commit message"
     ```

5. **Push Changes to GitHub:**
   - Push committed changes to the GitHub repository:
     ```bash
     git push origin main
     ```
   - Replace `main` with the branch you are working on if it's different.

### Enhancing Version Control with Obsidian Plugins:

6. **Install Git and Obsidian Plugin:**
   - Inside Obsidian, go to Settings > Community plugins.
   - Enable the "Git" and "Git Manager" plugins.

7. **Configure Git Settings:**
   - In the Git plugin settings, configure your Git user information.
   - Set your name and email to match your GitHub account.

8. **View Git Status and History:**
   - In the left sidebar, open the "Git" tab to view the status of your Git repository.
   - Use this tab to see changes, commit history, and manage branches.

9. **Commit Changes within Obsidian:**
   - Make changes to your notes in Obsidian.
   - Open the "Git" tab, stage changes, and commit directly from Obsidian.

10. **Pull and Push Changes within Obsidian:**
    - Use the "Git" tab to pull changes from the remote repository (GitHub) or push your local changes.
    - This provides a seamless integration of version control within Obsidian.

11. **Resolve Conflicts:**
    - If conflicts arise during pulls or merges, resolve them using the Git plugin.
    - Obsidian will display conflict markers, and you can use the Git tab to resolve conflicts.

12. **Branching and Merging:**
    - Create branches for different features or tasks within the Git plugin.
    - Merge branches when changes are ready to be incorporated into the main branch.

13. **Obsidian Sync (Optional):**
    - If using Obsidian Sync, synchronize your vault to keep it up-to-date across devices.
    - Note that Obsidian Sync is different from Git and serves a different purpose.

14. **Collaboration on GitHub:**
    - Collaborators can fork the repository, make changes, and submit pull requests on GitHub.
    - Use GitHub's collaboration features for discussions, code reviews, and collaboration.

15. **Regular Backups:**
    - Regularly back up your Obsidian vault, including the `.git` folder, to prevent data loss.

By combining GitHub for remote repository hosting with Obsidian and Git plugins, you can effectively implement version control for your Obsidian.md vault, enabling collaboration, history tracking, and seamless synchronization.

## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/obsidian/issues) for any improvements, suggestions or errors in the content.

You can also contact me using [Linkedin](https://www.linkedin.com/in/drshahizan/) for any other queries or feedback.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)


