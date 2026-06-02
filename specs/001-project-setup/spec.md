# Specification: Project Setup

## Summary

Set up the starting point for the Shadow Protocol Unity project.

This setup creates the GitHub repository, documentation structure, Unity 6 3D project, first level scene, ground plane, player placeholder, camera position, prototype material, and AI guidance file.

This specification does not implement gameplay.

## Goals

The project setup must include:

- a GitHub repository called `shadow-protocol`;
- a local clone of the repository;
- a documentation folder structure;
- a specification folder structure;
- the Shadow Protocol Game Design Document stored as `shadow-protocol-gdd.md`;
- a Unity 6 3D project;
- a scene called `Level01`;
- a ground plane called `Ground`;
- an empty `Player` GameObject;
- a capsule child object used as the visible player placeholder;
- a prototype material applied to the player placeholder;
- a top down camera view;
- an `AGENTS.md` file;
- Git commits for the completed setup work.

## Non Goals

This setup does not include:

- player movement;
- camera follow behaviour;
- interaction;
- enemy patrols;
- vision cone detection;
- objective collection;
- extraction;
- win or loss states;
- UI;
- audio;
- animation;
- final art assets.

## Acceptance Criteria

The setup is complete when:

- the repository exists on GitHub;
- the repository has been cloned locally;
- the documentation and specification folders exist;
- `shadow-protocol-gdd.md` has been added;
- the Unity project opens in Unity 6000.3.8f1 LTS;
- the project uses a 3D template;
- `Level01` exists and is saved;
- the scene contains a ground plane named `Ground`;
- the scene contains a `Player` GameObject at position `(0, 0, 0)`;
- the `Player` GameObject has a capsule child object;
- the capsule is visible above the ground;
- the camera is positioned to show the scene from a top down angle;
- the player placeholder has a prototype material;
- `AGENTS.md` exists;
- the work has been committed and pushed to GitHub.