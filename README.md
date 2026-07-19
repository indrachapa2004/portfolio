# Pure HTML Portfolio Layout & Guide

A semantic, content-first personal portfolio layout configured for **Indrachapa Jayasinghe**, designed specifically for Computer Science course modules emphasizing **Human-Computer Interaction (HCI)** and foundational web development. This implementation prioritizes logical **information architecture**, document **accessibility**, and semantic text structuring.

## 📌 Project Overview
This project presents an unstyled personal profile blueprint. It focuses entirely on how user content is sorted, logically parsed by digital user agents, and structurally weighted from top to bottom. Absent CSS structural blocks, this layout relies completely on native element definitions (`<h1>` through `<h4>`, `<ul>`, `<ol>`, and `<table>`) to present readable hierarchies.

---

## 🏗️ Core Portfolio Structure & Content Blueprint

### 1. Header & Introduction
*   **Structural Elements:** `<h1>`, `<h2>`, `<p>`
*   **Content Implementation:**
    *   `<h1>` Indrachapa Jayasinghe
    *   `<h2>` Computer Science Undergraduate & Aspiring Developer
    *   `<p>` **Introductory Profile:** 
        > *"Welcome to my portfolio! I am a Computer Science undergraduate at the University of Jaffna, focused on full stack web development and software engineering. Beyond my university coursework, I actively build practical applications to solve real world problems, blending robust backend logic with clean, user friendly design."*

### 2. About Me & Organized Skill Matrices
*   **Structural Elements:** `<h3>`, `<img>`, `<p>`, `<h4>`, `<ul>` (with nested `type="circle"` lists)
*   **Content Implementation:**
    *   `<h3>About Me</h3>`
    *   `<img>` Profile/Headshot source wrapper pointing to `img/profile.jpg` with a width of 250px and accessibility-compliant alternative labeling text (`alt="Profile Picture"`).
    *   `<p>` **Narrative Framework:**
        > *"I am a developer driven by a strong interest in software engineering, full stack web development, and algorithms. Currently, I am expanding my skills by building personal projects, such as a full stack Trading Journal application utilizing React and Supabase. My approach to coding is shaped by my previous professional experience in operational support at a local bank. Having spent time analyzing daily workflows and managing data entry, I understand firsthand how crucial software usability is for non-technical users. I combine that operational perspective with technical skills in HTML, Javascript, React, CSS and Java to build clean, efficient software from the ground up."*
    *   `<h4>Technical Skills</h4>`
    *   `<ul>` Strictly validated nested groupings defining specialized capabilities:
        *   **Languages & Frameworks:** HTML, CSS, JavaScript, React, Python, Java
        *   **Backend & Tools:** Git, GitHub, VS Code
        *   **Core Strengths:** Full Stack Development, Workflow Analysis, User Centric Design

### 3. Projects Showcase Matrix
*   **Structural Elements:** `<h3>`, `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`
*   **Content Implementation:**
    *   `<h3>Projects Showcase</h3>`
    *   A grid system using standard table structures (`border="1" width="1000" height="200"`) to uniformly position active programming environments without layout sheets.

| Project Name | Technologies | Description | Key Deliverable |
| :--- | :--- | :--- | :--- |
| **My Portfolio** | HTML, CSS, Javascript | A personal portfolio built with a foundation of valid, semantic HTML to prioritize information architecture and accessibility. This structure was designed to support the future implementation of CSS for layout and visual styling. | Link |
| **Full-Stack Trading Journal** | React, Supabase, Javascript | A personal web application designed to track and analyze market trades, featuring a secure database backend and customized developer shortcuts for efficient testing. | Link |

### 4. Education & Academic Chronology
*   **Structural Elements:** `<h3>`, `<ol>`, `<li>`, `<b>`, `<p>`
*   **Content Implementation:**
    *   `<h3>Education & Experience</h3>`
    *   `<ol>` Sequenced background history tracking milestones:
        1.  **B.S. in Computer Science** — University of Jaffna (Expected 2029)
            *   *Course Details:* Focusing on foundational software systems, data structures, and user interface design theories.
        2.  **Operational Support** — Local Bank (Previous Experience)
            *   *Workflow Details:* Analyzed daily operational workflows and handled data entry, gaining insight into how non-technical users interact with banking software systems.

### 5. Interaction Footer Elements
*   **Structural Elements:** `<hr>`, `<h3>`, `<p>`, `<ul>`, `<li>`, `<b>`
*   **Content Implementation:**
    *   `<hr>` Hard structural break line establishing boundaries for terminal text.
    *   `<h3>Get in Touch</h3>`
    *   `<p>` Closing communication prompt.
    *   `<ul>` Link references capturing primary communication pathways:
        *   **Email:** indrachapaholu19@gmail.com
        *   **Professional Profile:** Linked in
        *   **Code Sandbox:** Github link

---

## 💡 Key HCI Elements Maintained in the Code
When defending this submission for your HCI evaluations, note these exact structural successes present in your markup:

1.  **Perfect Heading Nesting:** Your code transitions smoothly from `<h3>About Me</h3>` into `<h4>Technical Skills</h4>`. This tells assistive machines and screen readers that your technical skill blocks belong as a subset of your overall profile identity.
2.  **Strictly Validated List Nesting:** The secondary item lists (`type="circle"`) are fully wrapped *within* their parent list items (`<li>`). This creates syntactically valid code that maps a clean data relationship tree.
3.  **Explicit Row Structures:** Using a dedicated `<thead>` and `<tbody>` mapping tells the user agent exactly which parts of your data grid are contextual labels and which rows represent individual structural records. 
4.  **Semantic List Architecture:** Utilizing ordered arrays (`<ol>`) for your career/academic path and standard bullet arrays (`<ul>`) for contact points clearly conveys a logical timeline versus an unordered collection of choices.