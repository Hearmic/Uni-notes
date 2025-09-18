# 🎓 Uni-notes

This repository contains university notes organized as an [Obsidian](https://obsidian.md) vault.  
They are structured, math-friendly, and ready to use both on **desktop** and **mobile**.

---

## ✨ Features
- 📂 Fully structured Obsidian vault
- 🔢 Math formulas (LaTeX / MathJax)
- 📈 Graphs stored as SVGs (render in Obsidian preview)
- 🔄 Easy to update with Git
- 📱 Works on desktop & mobile out of the box

---

## 🛠 Requirements
- [Obsidian](https://obsidian.md) (Desktop or Mobile)
- *(Optional, but recommended)* [Git](https://git-scm.com/downloads) for automatic updates

---

## 🚀 Setup Instructions

### Option 1: Quick Setup (no Git)
1. Download the repo as a ZIP:  
   Click **Code → Download ZIP** on [GitHub](https://github.com/Hearmic/Uni-notes).
2. Extract the folder.
3. In Obsidian → **Open folder as vault** → select the extracted folder.
#### If you would like to contribute to the repository after. You will need to link a folder to a remote repo.

1. Navigate to your local folder in your terminal or command prompt and initialize it as a Git repository. (You will need to [install Git](https://git-scm.com/download) for this)

```
cd /path/to/your/local/folder
git init
```

2. Add files and commit them. Stage all files in your local repository and then commit them with an initial message.

```
git add .
git commit -m "Initial commit"
```

3. Add the remote repository.
Fork this repository to your GitHub. Obtain the URL of your remote repository. Then, add it as a remote named `origin`.  

```
git remote add origin <remote_repository_URL>
```

Replace `<remote_repository_URL>` with the actual URL of your remote repository.

4. **Push your local repository to the remote:**

Push your committed changes from your local `main` (or `master`) branch to the `origin` remote.

Код

```
    git push -u origin main
```

If your default branch is `master`, use `git push -u origin master` instead. The `-u` flag sets the upstream branch, allowing you to use git push and git pull in the future simply.

5. Create a pull request (see CONTRIBUTE.md)

---


### Option 2: Git Setup (recommended)
This keeps your vault up to date automatically.

1. Install Git on your device:
   - [Windows](https://git-scm.com/download/win)
   - [Mac](https://git-scm.com/download/mac)
   - [Linux](https://git-scm.com/download/linux)
   - [Android (Termux)](https://wiki.termux.com/wiki/Git)
   - [iOS (Working Copy app)](https://apps.apple.com/us/app/working-copy-git-client/id896694807)

2. Clone the repo:
   ```bash
   git clone https://github.com/Hearmic/Uni-notes.git
   ```

3. Open the cloned folder as a vault in Obsidian:
   - **Desktop:** `File → Open folder as vault`
   - **Mobile:** Use file manager / Working Copy to link folder

4. To update your notes:
   ```bash
   git pull
   ```

---

## 📖 Using the Notes
- Use the **graph view** or folder structure to navigate.
- Math formulas are written in LaTeX and render in Obsidian preview.
- Graphs are stored as SVGs and display directly in notes.

---

## 🤝 Contributing
If you’d like to add or fix something, please read [CONTRIBUTING.md](./CONTRIBUTING.md).  
Pull requests are welcome!

---

## ⚠️ Disclaimer
These are personal study notes. While I try to keep them correct and organized,  
they may contain mistakes — use at your own discretion.
