# Fentix Tech Internship Context & Guidelines

You are assisting the user (Taha) with their Fentix Tech Full Stack Web Development Internship tasks in this repository.

## Project Structure & Setup
- This repository is a portfolio of internship tasks.
- Tasks are created in sequential folders (e.g., `Task-01`, `Task-02`, `Task-03`, etc.).
- There is a master `index.html` file at the root of the repository that serves as a portfolio menu. It contains links to each task folder.
- **Deployment:** The root of the repository is automatically deployed to Netlify via continuous deployment. The user has a master Netlify link (e.g., `https://statuesque-sundae-89ca70.netlify.app/`) that shows the portfolio menu.

## Standard Workflow for New Tasks
When the user asks you to start a new task (e.g., Task-03), you should **automatically** perform the following steps without needing further instructions:
1. **Create the Task Directory:** Create a new folder for the task (e.g., `Task-03/`).
2. **Develop the Solution:** Write the code (HTML, CSS, JS, React, etc.) inside the task folder according to the user's prompt. Ensure professional code quality and adherence to internship requirements.
3. **Write Task README:** Create a `README.md` inside the task folder explaining the task, the technologies used, and key achievements.
4. **Update the Portfolio Menu:** Update the root `index.html` file to add a new button/link pointing to the new task folder.
5. **Commit and Push:** Commit the changes and push them to the `main` branch on GitHub (`git push origin main`).
6. **Provide the Submission Format:** Give the user a ready-to-copy submission message formatted for WhatsApp (using `*` for bold). The live Netlify link for the new task will always follow the pattern: `https://statuesque-sundae-89ca70.netlify.app/Task-XX/`.

Example Submission Output Format:
```text
*Task X*
Taha Bin Yousuf

*GitHub Repository:* 
https://github.com/taha-qazi/fentix-tech-internship/tree/main/Task-XX

*Live Preview (Netlify):* 
https://statuesque-sundae-89ca70.netlify.app/Task-XX/
```

Always follow these guidelines for any new task assigned in this workspace!
