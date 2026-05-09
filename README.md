# TaskFlow

TaskFlow is a React daily planner built for organizing real work across priorities, due dates, notes, and workflow stages. It is designed like a lightweight productivity dashboard instead of a simple checklist.

## Live Demo

Live link coming soon.

## Why This Project

This project focuses on practical task management patterns that people actually use: saving plans, importing task lists, filtering by context, and moving work through a board-style workflow. It shows React state management, form handling, local persistence, file import/export, derived stats, and responsive UI design.

## Key Features

- Create detailed tasks with title, notes, category, priority, due date, estimate, and status
- Move tasks through `Backlog`, `In Progress`, `Review`, and `Done`
- Search across task titles, notes, and categories
- Filter tasks by priority, category, and status
- Track planner stats including total tasks, open tasks, completed tasks, high-priority tasks, due-soon tasks, and completion percentage
- Highlight the next task that needs attention
- Save tasks automatically with `localStorage`
- Export the full planner as JSON
- Import a saved TaskFlow planner file
- Paste bulk task lists using a simple structured format
- Export a readable text summary
- Clear completed work when the board gets crowded
- Responsive dashboard layout for desktop and mobile

## User Workflow

1. Add tasks with notes, categories, due dates, and estimates.
2. Use filters or search to find the work that matters right now.
3. Move tasks through the workflow lanes as progress changes.
4. Export the planner when the user wants to save or move their planning data.

## Tech Stack

- React
- Vite
- CSS
- Local Storage
- Browser File APIs

## What I Practiced

- Component state and derived UI data
- Form-heavy React interfaces
- Conditional rendering
- Local persistence
- Import/export workflows
- Responsive dashboard layout
- Accessibility-minded labels and controls

## Run Locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```
