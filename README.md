# Pure HTML Portfolio Template & Guide

A semantic, content-first personal portfolio template designed specifically for Computer Science students navigating **Human-Computer Interaction (HCI)** or introductory web development courses. This blueprint prioritizes **information architecture**, **accessibility**, and **semantic structural hierarchy** over styling, making it an excellent resource for pure HTML assignments.

## 📌 Project Overview
This project serves as a highly structured content blueprint. It forces a complete focus on how data is organized, parsed by screen readers, and prioritized logically from top to bottom. Because pure HTML lacks structural layouts (like side-by-side grids or flexboxes), this template relies strictly on semantic tags (`<h1>` to `<h3>`, `<ul>`, `<ol>`, and `<table>`) to establish a clear visual and structural hierarchy.

---

## 🏗️ Core Portfolio Structure & Content Guide

### 1. Header & Introduction (The "Hook")
*   **Structural Elements:** `<h1>`, `<h2>`, `<p>`, `<strong>`
*   **Purpose:** Establish professional identity and primary objectives immediately.
*   **Content Blueprint:**
    *   `<h1>` Your Full Name
    *   `<h2>` Professional Title (*Computer Science Student & Aspiring Developer*)
    *   `<p>` **Introduction Bio:** 
        > *"Welcome to my portfolio! I am a Computer Science undergraduate at the University of Jaffna, focused on full-stack web development and software engineering. Beyond my university coursework, I actively build practical applications to solve real-world problems, blending robust backend logic with clean, user-friendly design."*

### 2. About Me & Technical Skills (The Core Context)
*   **Structural Elements:** `<h3>`, `<img>`, `<p>`, `<ul>`, `<strong>`
*   **Purpose:** Provide deeper context on background experiences, personal software philosophy, and direct technical toolkits.
*   **Content Blueprint:**
    *   `<h3>About Me</h3>`
    *   `<img>` Profile/Headshot placeholder (Ensure a meaningful `alt="..."` attribute is supplied for HCI accessibility compliance).
    *   `<p>` **Detailed Narrative:**
        > *"I am a developer driven by a strong interest in software engineering, full-stack web development, and algorithms. Currently, I am expanding my skills by building personal projects, such as a full-stack Trading Journal application utilizing React and Supabase.*
        >
        > *My approach to coding is shaped by my previous professional experience in operational support at a local bank. Having spent time analyzing daily workflows and managing data entry, I understand firsthand how crucial software usability is for non-technical users. I combine that operational perspective with technical skills in JavaScript, React, Python, and Java to build clean, efficient software from the ground up."*
    *   `<h3>Technical Skills</h3>`
    *   `<ul>` Semantic technical stack list:
        *   **Languages & Frameworks:** JavaScript, React, HTML5, Python, Java
        *   **Backend & Tools:** Supabase, Git, GitHub, VS Code
        *   **Core Strengths:** Full-Stack Development, Workflow Analysis, User-Centric Design

### 3. Projects Showcase (The Data Grid)
*   **Structural Elements:** `<h3>`, `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`, `<a>`
*   **Purpose:** Present completed and ongoing software implementations cleanly. A standard HTML table is utilized to align data perfectly in the absence of CSS.
*   **Content Blueprint:**
    *   `<h3>Selected Projects</h3>`
    *   `<table>` structured explicitly with columns for **Project Name**, **Technologies**, **Description**, and **Key Deliverable**.

| Project Name | Technologies | Description | Key Deliverable |
| :--- | :--- | :--- | :--- |
| **Full-Stack Trading Journal** | React, Supabase, JavaScript | A personal web application designed to track and analyze market trades, featuring a secure database backend and customized developer shortcuts for efficient testing. | Link to GitHub Repository |
| **Adaptive Portfolio Site** | Semantic HTML5 | A personal portfolio built with a foundation of valid, semantic HTML to prioritize information architecture and accessibility. This structure was designed to support the future implementation of CSS for layout and visual styling. | Link to Portfolio Source Code |

### 4. Education & Experience (The Chronological Flow)
*   **Structural Elements:** `<h3>`, `<ol>`, `<li>`, `<p>`, `<strong>`
*   **Purpose:** Provide a structural chronological sequence of academic and professional background history.
*   **Content Blueprint:**
    *   `<h3>Education & Experience</h3>`
    *   `<ol>` Chronological ordered list items:
        1.  **B.S. in Computer Science** — University of Jaffna *(Expected)*
            *   *Details:* Focusing on foundational software systems, data structures, and user interface design theories.
        2.  **Operational Support** — Local Bank *(Previous Experience)*
            *   *Details:* Analyzed daily operational workflows and handled data entry, gaining insight into how non-technical users interact with banking software systems.

### 5. Contact & Footer (The Action Items)
*   **Structural Elements:** `<hr>`, `<h3>`, `<ul>`, `<a>`, `<small>`
*   **Purpose:** Cleanly close the page, isolate actions, and house meta-information.
*   **Content Blueprint:**
    *   `<hr>` Component break to segregate the document footer area.
    *   `<h3>Get in Touch</h3>`
    *   `<ul>` standard anchor links wrapping email (`mailto:`) and external profile endpoints (LinkedIn, GitHub).
    *   `<p><small>` Copywrite context: *“© 2026 [Your Name]. Built from scratch with pure semantic HTML.”*

---

## 💡 Key HCI Principles to Keep in Mind
When translating this layout blueprint directly into code for an HCI or introductory web course submission, maintain these design constraints:

1.  **Strict Document Hierarchy:** Always ensure your headings sequence perfectly (`<h1>` followed by sequential `<h2>` and `<h3>` tags). Never skip levels (e.g., jumping from `<h1>` directly to `<h4>`) merely to alter browser font sizing. Headings map structural weight, not visual styles.
2.  **Accessibility and Semantics:** 
    *   Always supply descriptive text to the `alt` property of an `<img>` tag so visually impaired users utilizing screen readers can accurately interpret your layout.
    *   Utilize structural structural wrappers like `<thead>` and `<tbody>` inside your projects table. This indicates to modern user agents exactly where descriptive definitions end and user data collections begin.
3.  **Future-Proof Planning:** The description for the portfolio site explicitly points out its current semantic-first nature while ensuring scalability for cascading stylesheets down the road. This reflects strong planning methodologies highly sought after in system development workflows.
