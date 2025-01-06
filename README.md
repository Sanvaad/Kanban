# Kanban Task Manager - A Frontend Mentor Challenge Solution  

This is my  solution for the [Kanban Task Management App Challenge on Frontend Mentor]

---

## Table of Contents  

- [Overview](#overview)  
  - [Challenge Details](#challenge-details)  
  - [Key Features](#key-features)  
  - [Screenshots](#screenshots)  
  - [Project Links](#project-links)  
  - [Tech Stack](#tech-stack)  
  - [Additional Resources](#additional-resources)  
- [Creator](#creator)  

---

## Overview  

### Challenge Details  

The goal was to develop a fully functional Kanban task management app that provides a seamless user experience across devices.  

### Key Features  

The app allows users to:  
- Experience an intuitive layout optimized for all screen sizes.  
- Interact with hover states for actionable UI elements.  
- Create, read, update, and delete boards and tasks.  
- Receive real-time form validation during board/task creation or edits.  
- Mark subtasks as complete and shift tasks between columns.  
- Toggle the visibility of the board sidebar.  

#### Detailed Behaviors  

- **Boards**:  
  - Switching boards updates the view dynamically.  
  - The "Create New Board" button opens a modal for adding a board.  
  - An "Edit Board" option in the dropdown allows board modification.  
  - Users can add or remove columns within the Add/Edit Board modal.  
  - A board deletion requires confirmation and clears all related columns and tasks.  

- **Columns**:  
  - At least one column must exist before tasks can be added.  
  - If no columns exist, the "Add New Task" button is disabled.  
  - New columns are added via the "Edit Board" modal.  

- **Tasks**:  
  - Newly created tasks appear at the end of the relevant column.  
  - Task status updates automatically move the task to the correct column.  

**Bonus Feature**:  
- Drag-and-drop functionality for tasks within columns.  

---

### Screenshots  

![Kanban Task Manager Screenshot](<./public/screenshots/Screen%20Shot%202023-03-29%20at%201.40.56%20PM%20(2).png>)  

---

### Project Links  

- **Live Demo**: [Kanban Task Manager](https://kanban-task-management-react-tailwind.vercel.app/)  

---

### Tech Stack  

This project was built using:  
- [React](https://reactjs.org/) - A powerful JavaScript library for UI development  
- [Redux](https://redux.js.org/) - For state management  
- [TailwindCSS](https://tailwindcss.com/) - For rapid styling  
- Drag-and-Drop API - For an interactive task management experience  

---

## Creator  

- **LinkedIn Profile**: Sanvaad Shende (https://www.linkedin.com/in/sanvaad/)  

---
