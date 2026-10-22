# Starter project

Run `npm install` and `npm run dev`. Complete the tasks in the matching lab guide.
# Student Course Dashboard (Lab 1)

A React + Vite app practising JSX, components, props, arrays and conditional rendering.

## Setup
1. Install [Node.js](https://nodejs.org) and VS Code.
2. Open this folder in VS Code.
3. Run `npm install`
4. Run `npm run dev` and open the URL shown (usually http://localhost:5173).

## Structure
- `src/App.jsx` – page layout, summary, filter buttons, renders the list with `map()` and `key={course.id}`
- `src/components/CourseCard.jsx` – reusable card receiving `title`, `lecturer`, `progress` as props
- `src/data/courses.js` – course data array
- `src/styles.css` – responsive styling

## Component tree
`App` → `CourseCard` (one per course)

## Features
- Reusable `CourseCard` with props
- Array rendered with `map()` and stable keys
- Conditional badge: Completed / In progress
- Empty state message when no courses match
- Responsive grid (phone and desktop)
- **Extension:** status filter (All / In progress / Completed) plus summary stats (total, completed, average progress)

