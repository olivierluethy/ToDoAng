# ToDoAng

A minimal to-do list app built with Angular — add tasks, see them in a list, and
remove them. A small project for learning Angular fundamentals (components,
two-way binding with `ngModel`, and `*ngFor`).

## Features

- Add a task from the input field (button or Enter key).
- Render all tasks in a list.
- Remove any task individually.

Tasks live in component state only, so the list resets on page reload.

## Tech

- [Angular](https://angular.io) 15 (standalone Angular CLI project)
- TypeScript
- Bootstrap utility classes for layout

## Getting started

Requires Node.js and the Angular CLI.

```bash
npm install
npm start        # ng serve
```

Then open <http://localhost:4200/>. The app reloads automatically when you edit a
source file.

## Build

```bash
npm run build    # outputs to dist/
```

## Project structure

```
src/app/
├── app.component.ts     # tasks array, addTask() / removeTask()
├── app.component.html   # input, add button, task list
└── app.module.ts        # root module (imports FormsModule for ngModel)
```
