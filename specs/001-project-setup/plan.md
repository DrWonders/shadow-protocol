# Plan: Project Setup

## Summary

This plan describes how the initial Shadow Protocol project setup is created.

The setup prepares the repository, documentation, specification files, Unity project, first scene, and basic prototype objects. It provides a clean starting point for later gameplay development.

## Implementation Plan

1. Create a GitHub repository called `shadow-protocol`.
2. Clone the repository locally.
3. Add the initial documentation and specification folders.
4. Add the Shadow Protocol Game Design Document as `shadow-protocol-gdd.md`.
5. Create a Unity 6 3D project inside the repository.
6. Save a new scene called `Level01`.
7. Add a ground plane called `Ground`.
8. Add an empty `Player` GameObject.
9. Add a capsule child object as the visible player placeholder.
10. Position the camera to give a top down view of the scene.
11. Create a prototype material for the player placeholder.
12. Create `AGENTS.md`.
13. Commit and push the completed setup work.

## Design Notes

The Unity project is created as a 3D project because Shadow Protocol uses a top down camera but still uses 3D scene objects.

The player is represented by an empty `Player` GameObject with a capsule child object. This separates the logical player object from the temporary visual placeholder.

Unity folders are created only when they are needed. 

## Risks

| Risk | Response |
|---|---|
| Unity generated files are committed accidentally | Use a Unity `.gitignore` and ignore generated folders such as `Library`, `Temp`, `Obj`, `Build`, `Builds`, `Logs`, and `UserSettings`. |
| The Unity project is created outside the repository | Create the repository first, then create the Unity project inside it. |
| The player placeholder is confused with final art | Make clear that the capsule is temporary prototype geometry. |
| The camera view does not show the player | Check the camera position and rotation in the Inspector. |
| The project grows too much too early | Add folders and systems only when the current task requires them. |

## Manual Checks

After setup, check that:

- the Unity project opens without major Console errors;
- the `Level01` scene opens correctly;
- the ground plane is visible;
- the player placeholder is visible in the Game view;
- the camera gives a top down view;
- Git status is clean after committing and pushing.