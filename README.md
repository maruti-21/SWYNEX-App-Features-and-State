# FocusFlow — App Features and State

## SWYNEX Technologies Internship — Task 3

FocusFlow is an Android productivity application designed to help users organize daily tasks, monitor progress, and manage focused work sessions.

## Task Objective

Implement core application features with input validation, appropriate empty states, and persistent or local state management.

## Core Feature: Task Management

The task management feature allows users to create, view, edit, and manage tasks through the FocusFlow interface.

### Features

- Create tasks with a title and description
- Assign categories: Study, Work, Personal, and Other
- Set task priority and due-date information
- Display saved tasks in the task list
- View task details
- Edit and delete tasks
- Mark tasks as completed

### Validation

- Prevent saving a task when its required title is empty
- Display a clear validation message
- Keep the user on the task form until the required information is corrected

### Empty State

When no tasks exist, display a helpful message explaining that the user has not created any tasks yet, along with an action to create the first task.

### State Management

The application uses local persistence and state management to maintain task information. Persistence behavior will be verified through application testing.

## Technology Stack

- Kotlin
- Jetpack Compose
- Android Studio
- Android SDK
- DataStore
- Material 3

## Testing Plan

1. Verify the empty state when no tasks exist.
2. Verify that an empty task title triggers validation.
3. Verify that a valid task appears in the task list after saving.
4. Verify editing, completion, and deletion.
5. Verify that saved task information remains available after restarting the app.

## Repository

**Project:** FocusFlow  
**Internship:** SWYNEX Technologies  
**Task:** Task 3 — App Features and State

*Implementation and testing status should be updated to reflect the actual results.*
