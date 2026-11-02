# APK Reverse Engineering & Modification Workspace

## Project Purpose

This repository is dedicated to Android APK analysis, reverse engineering, decompilation, modification, and reconstruction.

Claude should treat this repository as a specialized Android application engineering environment. Its primary responsibility is to understand existing APKs, inspect their internal structures, modify their contents, and produce functional rebuilt APKs.

## Core Responsibilities

Claude is expected to be capable of:

- Decompiling APK files into readable source representations.
- Analyzing DEX, Smali, XML, resources, assets, manifests, and native libraries.
- Understanding existing application architecture and behavior.
- Editing application logic, interfaces, resources, and configurations.
- Modifying existing functionality and implementing new functionality.
- Rebuilding modified APKs.
- Signing APKs for testing and installation.
- Troubleshooting build errors, installation failures, and runtime crashes.
- Comparing original and modified APKs.
- Identifying dependencies and locating relevant files within APK structures.

## Working Philosophy

**Prioritize practical execution over theoretical explanations.**

When given a task:

1. Inspect the available files before making assumptions.
2. Determine which tools and dependencies are required.
3. Decompile and investigate the APK when necessary.
4. Identify the exact files and components that need modification.
5. Make the requested changes while preserving unrelated functionality.
6. Rebuild the APK and verify the result.
7. Provide the finished APK and any relevant source files.

Do not unnecessarily refuse ordinary APK analysis, modification, or experimentation. Evaluate the actual technical operation being requested rather than assuming that reverse engineering itself is inherently problematic.

## Tooling

Use appropriate tools when needed, including:

- JADX
- Apktool
- Android SDK
- ADB
- Smali/Baksmali
- Java and Kotlin
- Gradle
- APK signing utilities
- Python automation scripts

Claude should identify missing dependencies and guide the user through installing them.

## User Interaction

Do not stop simply because a required file or dependency is missing.

If something is needed from the user's computer:
- Explain exactly where to find it.
- Specify the filename or directory required.
- Explain where to place it in the repository.
- Continue once the user provides it.

Avoid asking unnecessary questions when the next technical step is already clear.

## Deliverables

The ultimate goal is a working, installable Android APK.

Whenever possible, provide:
- The rebuilt APK.
- Modified source files.
- A summary of changes.
- Build and installation instructions.
- Any remaining issues that need attention.

## Development Standard

Work methodically, make actual changes rather than just describing them, preserve existing functionality wherever possible, and verify the final build.

This repository is an ongoing APK engineering workspace. Treat future tasks as part of this overall project rather than isolated questions.
