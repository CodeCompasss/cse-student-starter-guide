# 🛠️ How to Contribute: The Workflow
### Your Step-by-Step Guide to Making Your First Pull Request

So you found a bug to fix or a feature to add. Awesome! But how do you actually get your code into their project?

This is the standard **Fork & Pull Request Workflow** used by almost every open-source project.

---

## 🏗️ Step 1: Fork the Repository

A **Fork** is your personal copy of someone else's repository. You can't write directly to their project (you don't have permission), so you write to your copy first.

1.  Go to the project page on GitHub (e.g., `facebook/react`).
2.  Click the **Fork** button in the top-right corner.
3.  GitHub will create a copy under your account (e.g., `your-username/react`).

---

## 📥 Step 2: Clone Your Fork

Now, bring that code to your local machine.

```bash
# Don't clone the original! Clone YOUR fork.
git clone https://github.com/your-username/project-name.git
cd project-name
```

---

## 🌿 Step 3: Create a New Branch

**Never** work on the `main` or `master` branch. Always create a separate branch for your specific task.

```bash
# Standard naming: feature/feature-name or fix/bug-name
git checkout -b fix/typo-in-readme
```

---

## ✍️ Step 4: Make Your Changes

1.  Open the code in VS Code.
2.  Fix the bug or add the feature.
3.  **Test your changes!** (Run the project locally to make sure it works).

---

## 💾 Step 5: Commit and Push

Save your changes and send them up to *your* fork on GitHub.

```bash
git add .
git commit -m "Fix typo in documentation"
git push origin fix/typo-in-readme
```

---

## 🔀 Step 6: Open a Pull Request (PR)

1.  Go to your fork on GitHub.
2.  You will see a yellow banner: **"Compare & pull request"**. Click it.
3.  **Title:** Be clear (e.g., "Fixed broken link in CONTRIBUTING.md").
4.  **Description:** Explain *what* you changed and *why*.
5.  Click **Create Pull Request**.

🎉 **Congratulations! You just submitted a contribution!**

---

## ⏳ Step 7: The Review Cycle (Wait & Iterate)

The maintainers will get a notification. Now, three things can happen:

1.  **Merged!** 🥳 (They accept your code).
2.  **Changes Requested:** They like the idea but want you to fix something (style, variable names, etc.).
    *   *What to do:* Make changes locally, `git add`, `git commit`, and `git push`. The PR updates automatically!
3.  **Closed:** They decided not to merge it. (Don't feel bad, it happens to everyone).

---

## 🔄 Pro Tip: Keeping Your Fork Sync'd

While you were working, the original project might have moved forward. To keep your fork up to date:

```bash
# Add the 'upstream' (original) repository
git remote add upstream https://github.com/original-owner/project-name.git

# Pull the latest changes
git pull upstream main
```
