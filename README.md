# Cloning a Bitbucket Repository and Setting Up in VSCode

Welcome to this guide, where we'll walk you through the process of cloning a Bitbucket repository and setting it up in Visual Studio Code.

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

\`
git clone [URL]
\`

Replace `[URL]` with the URL you previously copied. For instance:

- **git clone https://bitbucket.org/yourusername/yourrepo.git**

---

## Access the Cloned Repository

- After the cloning process concludes, a new directory named after the repository will appear.
- Navigate to this directory with:

\`
cd repository_name
\`

- Congratulations, you're now in your local version of the Bitbucket repository and ready to begin work!

---

## Launching VSCode from the Terminal

- To open the cloned repository in VSCode directly from the terminal, use:

\`
code .
\`

---

This identity will be associated with your commits, so ensure accuracy.

