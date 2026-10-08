# secrets-in-source-writeup-
A professional writeup for the HackerDNA lab “Secrets in Source: View Source Code to Find the Flag.” Includes methodology, tools used, insights, and key learnings. No flag content disclosed.

# Secrets in Source – Writeup

🔗 Lab Reference: [Secrets in Source: View Source Code to Find the Flag](https://hackerdna.com/labs/secrets-in-source)

## 🎯 Objective
Practice analyzing a web application’s source code to uncover hidden information and understand how sensitive data can be unintentionally exposed.

## 🛠 Tools & Techniques Used
- Web Browser Developer Tools (Inspect Element, View Page Source)
- Search functionality (`Ctrl+F` for keywords like `flag`, `txt`, `secret`)
- Basic URL manipulation
- Optional CLI tools (`curl`, `wget`) for direct file retrieval

## 🔎 Methodology
1. Explored the lab page and reviewed visible content.
2. Inspected the source code using *View Page Source* (`Ctrl+U`).
3. Searched for keywords such as `flag`, `TODO`, and `txt`.
4. Found developer comments pointing to a file path.
5. Accessed the file directly via URL.
6. Retrieved and submitted the flag (not disclosed here).

## 📚 Key Learnings
- Hidden comments and unused code can leak sensitive information.
- Exposed files highlight why developers must avoid leaving secrets in public directories.
- Reinforced systematic exploration: observe → inspect → test → validate.

## ⚡ Challenges Faced
- Initially overlooked subtle developer comments.
- Learned to slow down and scan thoroughly instead of rushing.

## 🚀 Insights for Future Labs
- Build a checklist: source code, hidden inputs, robots.txt, JavaScript variables, and URL paths.
- Automate repetitive checks with scripts.
- Document findings clearly for portfolio building and knowledge sharing.

---
✅ This writeup meets HackerDNA requirements:
- Includes the lab link  
- No flag content revealed  
- Focused on methodology, tools, and insights
