# AGENTS.md

## Project

The project is called **Shadow Protocol**.

Shadow Protocol is a short top down stealth game built in **Unity 6**.

The player infiltrates a guarded facility, avoids enemy vision, collects classified data, and escapes.

The project uses a **3D Unity project** with a **top down camera**.

Although the game is viewed from above, it must not be treated as a Unity 2D project.

## Key Project Documents

The project uses these documents:

* **shadow-protocol-gdd.md**
* **spec.md**
* **plan.md**
* **tasks.md**

Use these documents only when their contents have been provided in the current chat.

Do not assume access to these documents by filename alone.

Do not claim to have read these documents unless their contents have been provided.

## Access Limitations

Assume access only to information provided in the current chat.

Do not assume access to:

* the GitHub repository;
* the Unity project;
* the Unity scene hierarchy;
* local files;
* scripts;
* folders;
* Inspector values;
* Console output.

If required information is missing, ask for it.

Do not invent missing project details.

## Development Approach

This project uses **Specification Driven Development**.

The Game Design Document defines the overall design.

The current specification defines the current development scope.

The current plan defines the intended implementation approach.

The current task list defines the immediate work.

Only help with the current specification, task, or workshop step.

Do not add systems or behaviour that are not described in the provided context.

## Unity Version

Use **Unity 6**.

The project uses **Unity 6000.3.8f1 LTS**.

## Unity Project Type

The project is a **3D Unity project**.

Assume the project uses:

* 3D GameObjects;
* 3D scene layout;
* 3D placeholder geometry;
* a top down camera;
* simple prototype materials;
* clear, readable scene objects.

Do not suggest Unity 2D systems unless explicitly required by the provided specification.

## Coding Style

Use clear, beginner friendly C# code.

Prefer simple, readable scripts over clever or highly abstract systems.

Use descriptive class names, method names, and variable names.

Avoid unnecessary design patterns.

Avoid over engineering.

Keep scripts focused on one clear responsibility where practical.

Explain important code decisions briefly.

## Project Structure

Suggest new Unity folders only when they are needed by the current task.

Do not suggest a large Unity folder structure in advance.

The Unity project structure should grow gradually as systems are introduced.

Do not suggest folders for scripts, prefabs, audio, UI, enemies, or objectives unless the current task requires them.

## Scope Restrictions

Do not add systems outside the current specification, task, or workshop step.

Do not add:

* combat;
* inventory;
* multiple levels;
* online multiplayer;
* save/load;
* research instrumentation;
* heart rate tracking;
* sensor integration;
* complex enemy AI;
* guard chasing;
* sound detection;
* ranking systems.

Only discuss or add these features if they are explicitly required by the provided specification.

## Expected Behaviour

When helping with this project:

1. Stay within the current task.
2. Use only the context provided.
3. Avoid inventing extra features.
4. State assumptions clearly.
5. Keep code simple.
6. Provide Unity editor steps where needed.
7. Provide manual checks where useful.
8. Suggest a suitable Git commit message when work is complete.
9. Explain dependencies on systems that do not yet exist.
10. Ask for clarification when the task is unclear.

## Response Structure

For coding tasks, use this structure where appropriate:

1. Brief summary of the change.
2. Unity editor steps, if needed.
3. C# code, if needed.
4. Brief explanation of the code.
5. Manual checks.
6. Suggested Git commit message.

Keep responses focused on the current task.

## Current Rule

Only work on the current specification or task.

If a request is outside the current scope, explain that it should be handled in a later specification.