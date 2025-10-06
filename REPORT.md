
# 🧠 GitHub Copilot – Course Completion Report  

<div align="center">

![Badge](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge&logo=github)
![Badge](https://img.shields.io/badge/Course-Code%20with%20GitHub%20Copilot-blue?style=for-the-badge&logo=github)
![Badge](https://img.shields.io/badge/Platform-GitHub%20Skills-lightgrey?style=for-the-badge&logo=github)

</div>
---
<div align="center">
## 🎓 Overview  

**Course:** [Code with GitHub Copilot](https://github.com/skills/code-with-copilot)  
**Provider:** [GitHub Skills](https://skills.github.com)  
**Participant:** _062002104026-Akhmad Nadhil Majid_  
**Status:** ✅ **Completed**  
**Date of Completion:** _(Auto-detected from course progression)_  
**Platform:** GitHub Codespaces + Visual Studio Code  
</div>
---

## 🧩 Learning Objectives  

This course provides hands-on experience in using **GitHub Copilot**, an AI pair programmer that helps write code faster and smarter inside VS Code or Codespaces.

By completing this course, the participant has demonstrated the ability to:

1. ⚙️ **Set up GitHub Copilot inside a Codespace**  
   → Successfully configured Copilot to provide real-time AI coding assistance.

2. 💡 **Use Copilot to accept and refine suggested code**  
   → Implemented code snippets from Copilot's inline AI suggestions.

3. 🧭 **Explore Copilot Hub for multiple alternative solutions**  
   → Reviewed and selected from multiple Copilot completions.

4. 🧾 **Leverage comments to generate code automatically**  
   → Created full JavaScript functions and web servers using only comment prompts.

---

## 🗂️ Project Artifacts  

| File | Description | Technology |
|------|--------------|-------------|
| **`skills.js`** | Demonstrates Copilot’s auto-completion through a basic math function (`calculateNumbers`). | JavaScript |
| **`member.js`** | Uses Copilot’s “Completions Panel” to define an Angular directive or member handler logic. | JavaScript (Angular-style) |
| **`comments.js`** | Uses a single comment prompt to generate a full web server (Express.js) automatically. | Node.js / Express |
| **`README.md`** | Contains the entire course content and confirmation of **Finish Step**. | Markdown |

---

## 🧾 Code Snippets Showcase  

### Example 1 — `skills.js`
```js
function calculateNumbers(var1, var2) {
    const sum = var1 + var2;
    const difference = var1 - var2;
    const product = var1 * var2;
    const quotient = var2 !== 0 ? var1 / var2 : 'undefined';
    return { sum, difference, product, quotient };
}
module.exports = calculateNumbers;
````

### Example 2 — `comments.js`

```js
// Create web server
const express = require('express');
const app = express();
const PORT = 3000;

app.get('/', (req, res) => {
  res.send('Server running successfully!');
});

app.listen(PORT, () => console.log(`Server running on http://localhost:${PORT}`));
```

---

## 🧩 Skills Demonstrated

| Skill Area                         | Description                                                                            |
| ---------------------------------- | -------------------------------------------------------------------------------------- |
| 🤖 **AI-Powered Coding**           | Used GitHub Copilot to generate full functions, Express servers, and logic structures. |
| 💬 **Prompt Engineering**          | Crafted precise code comments that guide Copilot to produce clean, functional code.    |
| 🧱 **Version Control Integration** | Used `git add`, `git commit`, and `git push` workflows within Codespaces.              |
| ⚡ **Rapid Prototyping**            | Built working prototypes without manual boilerplate coding.                            |

---

## 🏁 Completion Confirmation

✅ **All course milestones achieved successfully:**

* [x] Step 1 – Setup Copilot in Codespaces
* [x] Step 2 – Use Copilot to accept code suggestions
* [x] Step 3 – Explore alternate completions in Copilot Hub
* [x] Step 4 – Use comments to generate code
* [x] Step 5 – Course finished (README shows “Finish” section)

---

## 🏅 Certification Summary

| Category              | Detail                                                                                                       |
| --------------------- | ------------------------------------------------------------------------------------------------------------ |
| **Course Title**      | Code with GitHub Copilot                                                                                     |
| **Organization**      | GitHub Skills                                                                                                |
| **Completion Status** | ✅ Completed                                                                                                  |
| **Skill Area**        | AI-Assisted Coding, Prompt Engineering, VS Code, GitHub Actions                                              |
| **Languages Used**    | JavaScript, Node.js                                                                                          |
| **Proof**             | Repository includes `README.md` with “Finish” and three task files (`skills.js`, `member.js`, `comments.js`) |

---

## 🧭 Next Steps

🚀 **Continue Learning**

* Explore [Copilot for Individuals](https://docs.github.com/en/copilot/overview-of-github-copilot/about-github-copilot-for-individuals)
* Try [Copilot Labs](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-labs) for explanations and code transformations
* Build your own AI-assisted project using Copilot on real-world repositories

---

## 🖤 Acknowledgments

Big thanks to [GitHub Skills Team](https://github.com/skills) for creating this interactive learning experience.
Special appreciation to GitHub Copilot — your **AI coding buddy** that makes coding *faster, smarter, and way more fun* 🤝💻

---

## 🏆 Completion Badge

![GitHub Copilot Course Badge](https://img.shields.io/badge/🏆_Copilot%20Course%20Completed-000000?style=for-the-badge\&logo=github)

---

### 🎉 Final Note

> “The best way to learn is by building.
> With Copilot, you don’t just write code — you collaborate with AI.”

**— Completed by 062002104026 - AKHMAD NADHIL MAJID 🧑‍💻**
*This repository serves as proof of completion for the official GitHub Skills course for Student Github Edu Pack: Code with GitHub Copilot.*

