# Fihris (فهرس)

> 📎 **Project Name:**
> **Fihris (فهرس)**

> 📌 **Project Overview:**
> Fihris is a free, open-access course directory designed for self-taught developers and students.
>
> The platform collects and organizes learning resources from external sources such as YouTube, open-access course platforms, and web tutorials into a structured and distraction-free learning experience.
>
> Users can discover courses using multiple filters, follow structured lessons, track their learning progress, save courses to a personal library, take timestamped notes, and generate a completion certificate after finishing a course.

> 👥 **Team Members:**
>
> * **Developer 1:** Catalog & Discovery
> * **Developer 2:** Media Player & Interaction
> * **Developer 3:** User State & Rewards
> * **Developer 4:** Content & Administration

> 📎🎓 **Instructor:**
> **DEPI Instructor**
> *DEPI Version 5 — Graduation Project*

> 🎯 **Project Objectives:**
>
> * Provide a free and centralized directory for programming and development courses.
> * Make it easier for learners to discover courses based on technology, category, difficulty level, and provider.
> * Provide a structured learning experience for courses collected from multiple external sources.
> * Allow users to track their learning progress and completed lessons.
> * Allow users to save courses to a personal library.
> * Enable learners to create timestamped notes while studying.
> * Provide a client-side certificate generator when a course is completed.
> * Allow contributors to submit new courses through a structured submission form.
> * Validate and process external course URLs automatically.

> 📦 **Project Scope:**
>
> ### 1. Course Catalog & Multi-Criteria Discovery
>
> * Course cards with essential course information.
> * Search functionality.
> * Filtering by:
>
>   * Category
>   * Technology
>   * Difficulty level
>   * Course provider
> * Responsive catalog interface.
>
> **Responsible:** Developer 1
>
> ### 2. Structured Course Viewer & Multi-Source Player
>
> * Structured lesson tree.
> * Active lesson tracking.
> * Embedded YouTube/Vimeo videos.
> * Support for external course links.
> * Lesson completion status.
> * GitHub and documentation links.
>
> **Responsible:** Developer 2
>
> ### 3. Personal Library & Progress Tracking
>
> * Save courses to a personal library.
> * Mark lessons as completed.
> * Course progress bar.
> * Persistent client-side state using `localStorage`.
>
> **Responsible:** Developer 3
>
> ### 4. Course Submission & Universal Link Parsing
>
> * Course submission form.
> * URL validation.
> * YouTube/Vimeo URL parsing.
> * Regex-based extraction of video IDs.
> * Content administration functionality.
>
> **Responsible:** Developer 4
>
> ### 5. Timestamped Personal Notes
>
> * Create notes while watching a lesson.
> * Associate notes with a specific timestamp.
> * Quickly jump back to the referenced timestamp.
>
> **Responsible:** Developer 2
>
> ### 6. Client-Side Completion Certificate
>
> * Certificate generation after reaching 100% course completion.
> * Certificate displayed through a modal.
> * Include:
>
>   * Learner name
>   * Course name
>   * Platform
>   * Completion date
> * Generate the certificate using HTML Canvas / `html2canvas`.
>
> **Responsible:** Developer 3

> 📅 **Project Timeline:**
> **8 Weeks (2 Months)**

> 🏗️ **Architecture:**
> **Client-Side Single Page Application (SPA)**
>
> The application is built as a React-based Single Page Application, with client-side state management and persistent learning data stored locally using `localStorage`.

## 👨‍💻 Team Responsibility Matrix

| Developer       | Area                       | Main Responsibilities                                                          |
| --------------- | -------------------------- | ------------------------------------------------------------------------------ |
| **Developer 1** | Catalog & Discovery        | Home layout, search, category filters, platform filters, responsive shell      |
| **Developer 2** | Media Player & Interaction | Course viewer, embedded/external player router, lesson tree, timestamped notes |
| **Developer 3** | User State & Rewards       | Saved library, progress tracking, `localStorage`, certificates                 |
| **Developer 4** | Content & Administration   | Submission form, URL/ID parser, validation, admin data management              |

## 🛠️ Core Technologies

* **React**
* **JavaScript**
* **HTML5**
* **CSS3**
* **localStorage**
* **YouTube / Vimeo Embeds**
* **HTML Canvas / html2canvas**
* **Regex-based URL Parsing**

## 🎓 Expected Outcome

Fihris aims to provide learners with a simple and organized environment for discovering and completing programming courses without requiring the platform itself to host the educational content.

The project combines course discovery, structured learning, progress tracking, personal notes, and completion certificates into a single responsive React application.
