# Assignment 1.5 — GitHub Essentials II

## Aim
To upload a local project to GitHub using Git commands.

## Procedure

**1. Create a GitHub Account**

Visit [https://github.com](https://github.com) and create an account or log in to an existing account.

**2. Create a New Public Repository**

- Click on the "+" icon on GitHub.
- Select "New Repository".
- Enter a repository name.
- Select "Public".
- Click "Create Repository".

**3. Connect the Local Repository to GitHub**

Open the terminal in your project folder and execute the following commands:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY-NAME.git
```

**4. Upload Files Using Git Push**

Execute the following command to upload your project files to GitHub:

```bash
git push -u origin main
```

**5. Add a New File and Push the Second Commit**

Create a new file named `second.txt` and add some content to it.

Execute the following commands:

```bash
git add .
git commit -m "Added second file"
git push
```

**6. Verify Commit History on GitHub**

- Open your GitHub repository.
- Check whether all project files are uploaded successfully.
- Click on the commit history to verify both commits.

## Result

Successfully uploaded the local project to a public GitHub repository using Git commands and verified the commit history.

## Submission

GitHub Repository Link: https://github.com/USERNAME/REPOSITORY-NAME