# Task Manager CLI 📝 

## Overview
The Task Manager CLI is a pure Node.js command-line application that allows users to manage their daily tasks directly from the terminal. Built entirely without third-party npm packages, it relies strictly on built-in Node.js modules (`fs`, `path`, `events`) to manage data and demonstrate fundamental backend architecture.

## Core Features(Still-Working on it tho):
*   **Task Creation:** Add tasks with titles, priority levels, and tags. The app uses a `Set` to automatically remove duplicate tags.
*   **Querying & Filtering:** List all tasks or filter them by specific attributes (like status or priority level).
*   **State Management:** Mark specific tasks as done or permanently delete them using their unique IDs.
*   **Data Persistence:** All state changes are instantly serialized and written to a local JSON database, ensuring data survives terminal restarts.
