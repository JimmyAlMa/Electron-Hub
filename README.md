# Electron Hub

Welcome to Electron Hub! This is a centralized repository (monorepo hub) designed to organize and document my learning journey and projects built using the Electron framework.

This repository leverages Git Submodules to link separate Electron project repositories under a single root project while preserving each project's individual commit history.

---

## Projects Included (Submodules)

Below are the Electron project repositories linked within this hub:

* Learn-Electron (1-2) - Exercises, feature experiments, and notes covering fundamental concepts of Electron development.
* Electron-Project-1 - The first desktop application project built using Electron.

---

## Prerequisites

Before running any project locally, ensure you have the following installed:

* Node.js
* Git

---

## Cloning the Repository

Because this repository uses Git Submodules, use the --recurse-submodules flag when cloning to automatically pull all nested projects:

```bash
# Clone the root repository along with all submodules
git clone --recurse-submodules [https://github.com/your-username/Electron-Hub.git](https://github.com/your-username/Electron-Hub.git)

# Navigate into the project folder
cd Electron-Hub