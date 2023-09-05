# Cloning a Bitbucket Repository and Setting Up in VSCode

Welcome to this guide, where we'll walk you through the process of cloning a Bitbucket repository and setting it up in Visual Studio Code.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Retrieve Repository URL](#retrieve-repository-url)
3. [Clone the Repository Locally](#clone-the-repository-locally)
4. [Access the Cloned Repository](#access-the-cloned-repository)
5. [Launching VSCode from the Terminal](#launching-vscode-from-the-terminal)
6. [Initial Git Setup](#initial-git-setup)

---

## Prerequisites

- Ensure both `git` and `VSCode` are installed on your local machine. If they aren't, refer to the Onboarding Document for installation guidance.

---

## Retrieve Repository URL

- Navigate to the desired repository's main page on Bitbucket.
- Locate and click the "Clone" button, typically found at the top right.
- From the dropdown, copy the entire URL listed under the HTTP protocol.

---

## Clone the Repository Locally

- Determine where you'd like the repository to reside on your local machine and navigate there.
- Right-click in the directory and choose "Git Bash Here" to open a Git terminal.
- Clone the repository by running:

\```bash
git clone [URL]
\```

Replace `[URL]` with the URL you previously copied. For instance:

\```bash
git clone https://bitbucket.org/yourusername/yourrepo.git
\```

---

## Access the Cloned Repository

- After the cloning process concludes, a new directory named after the repository will appear.
- Navigate to this directory with:

\```bash
cd repository_name
\```

- Congratulations, you're now in your local version of the Bitbucket repository and ready to begin work!

---

## Launching VSCode from the Terminal

- To open the cloned repository in VSCode directly from the terminal, use:

\```bash
code .
\```

---

## Initial Git Setup (Recommended for First-Time Users)

- Before making commits, it's advisable to configure your Git identity:

\```bash
git config --global user.name "Your Full Name"
git config --global user.email "your_email@example.com"
\```

This identity will be associated with your commits, so ensure accuracy.
