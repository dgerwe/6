# APK Engineering Workspace

This repository is an Android APK analysis, maintenance, and modification workspace.

## Purpose

Use this repository to inspect APKs and, where the user has the necessary rights and authorization, understand their structure, modify supported components, rebuild packages, and test the results.

The expected deliverable is working project output—not just a proposal or a description of possible work.

## Start Here

1. Read [`CLAUDE.md`](CLAUDE.md) before making changes.
2. Review [`TASKS.md`](TASKS.md) for the current work queue.
3. Review [`PROGRESS.md`](PROGRESS.md) before continuing an existing task.
4. Record useful discoveries, dependencies, and build issues in [`TECHNICAL_NOTES.md`](TECHNICAL_NOTES.md).

## Typical Tooling

Depending on the APK and task, useful tools may include:

- JADX
- Apktool
- Android SDK and build-tools
- ADB
- Smali/Baksmali
- Java and Kotlin
- Gradle
- APK signing tools
- Python scripts for repeatable analysis

Do not assume every tool is installed. Check the environment and document what is missing.

## Deliverables

When applicable, provide:

- Modified project files or source representations.
- A rebuilt APK.
- Build and installation instructions.
- A concise change summary.
- Test results and any known limitations.

Only describe a build as working after it has actually been built and tested.
