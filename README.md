# Day-77-100-Days-challenge-in-cybersecurity
## Day 77: JavaScript Foundation for Client-Side Security

**Date:** [Insert Date]
**Focus:** Understanding core JavaScript mechanics to identify client-side vulnerabilities (e.g., XSS, Logic Flaws).

### 📝 Overview
Today's focus was on the fundamentals of JavaScript. Rather than learning JS to build applications, the goal was to understand how JS executes in the browser to manipulate the DOM, handle variables, and process logic. This foundation is critical before moving into advanced client-side attacks like Cross-Site Scripting (XSS).

### 🔑 Key Concepts Covered:
* **The Role of JS:** Understanding that JS is the "nervous system" of a webpage, running entirely client-side.
* **Security Principle:** Client-side logic can never be trusted for secure operations (like price validation or access control) because it can be bypassed or manipulated by the user.
* **Script Implementation:** * External (`<script src="script.js"></script>`) vs. Inline (`<script>...</script>`).
  * Crafting basic XSS proof-of-concept payloads (`alert()`).
* **Information Disclosure via Console:** Utilizing `console.log()` to find sensitive data, API keys, or developer notes left behind in production environments.
* **Variable Scope & Security:**
  * `var`: Function/Global scope. Prone to hoisting and global pollution.
  * `let`: Block scope. The standard for mutable variables.
  * `const`: Block scope. Immutable reference. 
  * *Insight:* Understanding scope is necessary for tracking how data flows through an application and identifying where manipulation is possible.

### 🖼️ Resources
* *(Upload your generated infographics to an `images/` folder in your repo and link them here)*
* `![JS Purpose](images/day77-js-purpose.png)`
* `![JS Variables](images/day77-js-variables.png)`
