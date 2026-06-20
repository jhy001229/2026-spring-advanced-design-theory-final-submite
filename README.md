# 2026 Spring Advanced Design Theory Assignment Submission

This repository is used for assignment submissions for **Advanced Design Theory, Spring 2026**.

Students will submit assignments through the standard GitHub workflow:

1. Fork this repository.
2. Add assignment files inside your own student folder.
3. Commit and push your changes.
4. Open a pull request to submit your assignment.

GitHub Classroom is not used for this course because GitHub has announced that new GitHub Classroom users can no longer create new classrooms.

## Repository Link

Use the course submission repository below:

```text
https://github.com/philipdekim-OnD01/2026-spring-advanced-design-theory-final-submite
```

## Before You Start

Each student must have:

- A GitHub account
- Git installed on their computer, or GitHub Desktop
- The official course submission repository URL

## Required Submission Folder Name

Create one folder for yourself using this format:

```text
student-id_full-name
```

Example:

```text
2026123456_Gildong-Hong
```

Use English letters for your name. Do not use spaces in the folder name.

## Recommended File Structure

Place all of your assignment files inside your own folder:

```text
.
|-- 2026123456_Gildong-Hong/
|   |-- README.md
|   |-- report.pdf
|   |-- source/
|   `-- figures/
`-- README.md
```

If the instructor gives a required file format, folder structure, or naming rule, follow that instruction first.

## How to Submit Your Assignment

### 1. Fork the Repository

1. Open the official course submission repository.
2. Click **Fork** in the upper-right corner.
3. Create the fork under your own GitHub account.

After this step, you will have your own copy of the repository.

### 2. Clone Your Fork

Open a terminal and run:

```bash
git clone YOUR_FORK_REPOSITORY_URL
cd YOUR_FORK_REPOSITORY_FOLDER
```

Replace `YOUR_FORK_REPOSITORY_URL` with the HTTPS URL of your fork.

### 3. Create Your Student Folder

Create a folder using your student ID and name:

```bash
mkdir 2026123456_Gildong-Hong
```

Replace `2026123456_Gildong-Hong` with your own student ID and English name.

### 4. Add Your Assignment Files

Put your final assignment files inside your own folder.

Example:

```text
2026123456_Gildong-Hong/report.pdf
2026123456_Gildong-Hong/source/main.py
2026123456_Gildong-Hong/figures/result.png
```

Do not edit or delete another student's folder.

### 5. Commit Your Work

Run:

```bash
git status
git add .
git commit -m "Submit assignment - student ID and name"
```

Example:

```bash
git commit -m "Submit assignment - 2026123456 Gildong Hong"
```

### 6. Push to Your Fork

Run:

```bash
git push
```

If Git asks you to log in, follow the GitHub authentication instructions shown in your terminal.

### 7. Open a Pull Request

1. Go to your fork on GitHub.
2. Click **Contribute**.
3. Click **Open pull request**.
4. Make sure the base repository is the official course submission repository.
5. Use this pull request title format:

   ```text
   [Assignment Submission] student-id full-name
   ```

   Example:

   ```text
   [Assignment Submission] 2026123456 Gildong Hong
   ```

6. Click **Create pull request**.

Your assignment is submitted when the pull request is created before the deadline.

## How to Update Your Submission

If you need to revise your work before the deadline:

```bash
git add .
git commit -m "Update assignment submission"
git push
```

The pull request will update automatically after you push new commits to the same branch.

## Submission Rules

- Submit by pull request only.
- Put your files only inside your own student folder.
- Do not modify, rename, or delete another student's files.
- Do not submit another student's work.
- Do not include unnecessary temporary files such as `.DS_Store`, `.ipynb_checkpoints`, or large unrelated datasets.
- The pull request creation time and commit history may be used to verify whether the assignment was submitted before the deadline.

## Confirming Your Submission

After opening the pull request, check that:

- The pull request is visible in the official course repository.
- Your student folder appears in the pull request file list.
- Your final files are included.
- The pull request title follows the required format.

## Common Problems

### I clicked Fork but cannot find my repository.

Go to your GitHub profile and open the **Repositories** tab. Your fork should appear there.

### I cannot push my changes.

Check that you cloned your own fork, not the instructor's repository. You usually do not have direct write permission to the instructor's repository.

### I made a mistake after opening the pull request.

Fix the files locally, commit again, and push to your fork. The pull request will update automatically.

### I edited someone else's folder by mistake.

Undo those changes before submitting. Your pull request should contain only your own student folder.

### I submitted to the wrong repository.

Contact the instructor immediately and include:

- Your name
- Your student ID
- The wrong repository URL
- The correct repository or pull request URL, if available

## Instructor Setup Notes

Recommended setup:

1. Create a public GitHub repository named:

   ```text
   2026-spring-advanced-design-theory-submissions
   ```

2. Add this README to the repository.
3. Use this official repository URL:

   ```text
   https://github.com/philipdekim-OnD01/2026-spring-advanced-design-theory-final-submite
   ```
4. Keep the repository public if students will fork it from personal accounts.
5. Tell students to submit by pull request before the deadline.
6. Review submissions from the **Pull requests** tab.
7. Do not merge pull requests until after grading if you want to keep submissions separate.

## Official References

- Fork a repository: <https://docs.github.com/en/get-started/quickstart/fork-a-repo>
- Creating a pull request: <https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request>
- Git basics: <https://docs.github.com/en/get-started/using-git/about-git>
