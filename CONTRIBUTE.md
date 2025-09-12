
Here’s your complete **CONTRIBUTING.md** file in one piece, ready to drop into your repo:
# Contributing Guidelines

Thank you for being so interested in contributing to **Uni-notes** 🎓.  
This repository is an Obsidian vault designed to store and organize lecture notes, examples, and study materials for university courses.  
We welcome contributions from anyone who wants to add to, improve, or expand the knowledge presented here.  

---

## 📚 What You Can Contribute
- **New notes** for your courses (organized in the existing folder structure).
- **Improvements to existing notes**, including:
  - Adding explanations, proofs, examples, or diagrams.
  - Fixing mistakes or clarifying text.
  - Updating formatting for better readability.
- **Course/Professor information** (structured consistently with existing notes).
- **Ideas or examples** from your own studies.

---

## 📝 Formatting Guidelines
To keep everything consistent, please follow the style of the existing notes:

### 📂 Folders and File Naming
- Put your notes in the **respective subject folder** and inside the folder for the specific course.  
- If the course folder does not exist, create it.  
- Name your courses as they appear on **eClass** (without the department name).  
- For easier search, start every note heading with the **shortened course code**.  

**Example**:  
If you want to create a note for **SC/CHEM 1000 – Chemical Structure**, the path will look like this:  

Uni-notes/Chemistry/CHEM 1000 – Chemical Structure/C 1000 Note 1.md

---

### 🔗 Linking Notes
- To connect notes in **graph view**, always use Obsidian’s linking format:  
```

[[Linked file name|Display name]]

```
Example:  
```

[[C 1000 Note 1|Atomic Bonds]]

````

---
### ➗ Math (LaTeX)
Always use LaTeX for mathematical expressions.  
Example:  
```
$f(x) = \sqrt{2x+1}$  
$x \geq -\frac{1}{2}$  
$D = \{ x \in \mathbb{R} \mid x \geq -\tfrac{1}{2} \}$
````
$f(x) = \sqrt{2x+1}$  
$x \geq -\frac{1}{2}$  
$D = \{ x \in \mathbb{R} \mid x \geq -\tfrac{1}{2} \}$

Be aware of 2 spaces after each line or in GitHub it will render as one single line.

### **📈 Graphs**

- For Obsidian: use desmos-graph code blocks with desmos extention.
- For GitHub: export .svg files into the graphs/ folder and embed with Markdown:
```
![Graph of y=x^2](graphs/parabola.svg)
```

---

### **⚠️ Important Notes**

Use inline color styling for emphasis:

```
<span style="color:rgb(255, 50, 50)">Important: Do not simplify equations before computing the domain.</span>
```

<span style="color:rgb(255, 50, 50)">Important: Do not simplify equations before computing the domain.</span>

---

## **💻 Workflow**

1. **Fork** the repository to your GitHub account.
    
2. **Clone** your fork locally:
    

```
git clone https://github.com/YOUR_USERNAME/Uni-notes.git
```

    
3. Open the folder in **Obsidian**.
    
4. Create/edit notes inside your fork.
    
5. Commit your changes with a short description:
    
```
git add .
git commit -m "Added CHEM 1000 Note 1 on Atomic Bonds"
```
    
6. **Push** your changes:
    
```
git push origin main
```
    
7. Open a **Pull Request** to this repo. [How to create a pull request from a fork?](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)

---

## **🔄 Keeping Your Fork Updated**

To avoid conflicts, keep your fork in sync with the main repository:

```
git remote add upstream https://github.com/Hearmic/Uni-notes.git
git fetch upstream
git merge upstream/main
```

If you’re using the **Obsidian Git plugin**, you can also request the repo access code from the maintainer for direct syncing.

---

## **✅ Review Process**

- All contributions will be reviewed by the maintainers (me and my team).
    
- We may request changes to ensure consistency.
    
- Once approved, your changes will be merged into the main vault.
    

---

## **👤 Credit**

- You may add your name/username at the end of your note.
    
- Alternatively, mention it in your PR description.

---

## **⚠️ Important**

- Please **do not upload copyrighted textbooks or scans**.
    
- Stick to lecture notes, your own examples, or summaries.


---

Thank you for making **Uni-notes** better for everyone 🚀

Happy note-taking! ✨
