# Leetcode Java Debug Enhancer

A toolkit and demonstration project to make debugging and understanding LeetCode algorithm solutions in Java easier. This repository contains the project deliverables for an advanced software engineering final project: source/binary artifacts (packaged in a ZIP), a project report (DOCX) and a presentation (PPTX).

## Table of contents
- [What it is](#what-it-is)
- [Why](#why)
- [Included files](#included-files)
- [Key features](#key-features)
- [Getting started](#getting-started)
- [Usage](#usage)
- [Project structure (expected)](#project-structure-expected)
- [How to contribute](#how-to-contribute)
- [License](#license)
- [Author / Contact](#author--contact)

## What it is
Leetcode Java Debug Enhancer is a collection of tools, examples and documentation intended to help students and developers better instrument, debug, and visualize common algorithmic patterns used in LeetCode problems implemented in Java.

## Why
Debugging algorithm solutions (especially for recursion, backtracking, and graph problems) can be difficult because of complex state changes and non-obvious intermediate data. This project demonstrates approaches and tooling to:
- Produce clearer debug traces
- Visualize intermediate states
- Reduce debugging time while solving or teaching LeetCode problems

## Included files
- [ADVANCED SOFTWARE ENGINEERING FINAL PROJECT.docx](https://github.com/SindhuraShankeshi/Leetcode-Java-Debug-Enhancer/blob/main/ADVANCED%20SOFTWARE%20ENGINEERING%20FINAL%20PROJECT.docx) — project report / write-up
- [Debugging-Enhancer-for-Leetcode-Algorithms-in-Java.pptx](https://github.com/SindhuraShankeshi/Leetcode-Java-Debug-Enhancer/blob/main/Debugging-Enhancer-for-Leetcode-Algorithms-in-Java.pptx) — presentation slides
- [LeetcodeJavaDebugEnhancer.zip](https://github.com/SindhuraShankeshi/Leetcode-Java-Debug-Enhancer/blob/main/LeetcodeJavaDebugEnhancer.zip) — packaged project (source / build artifacts). Extract to inspect the code and instructions inside.

## Key features (examples)
- Instrumentation helpers to print structured traces and snapshots of important variables
- Helpers for formatting and visualizing arrays, trees, and graphs during execution
- Sample LeetCode solutions with enhanced debug output
- Documentation and slides describing design choices and evaluation

## Getting started

Prerequisites
- Java 8+ (recommended: Java 11+)
- An IDE such as IntelliJ IDEA or Eclipse, or a command-line toolchain (javac/java)
- (Optional) Maven or Gradle if the project inside the ZIP uses a build system

Quick steps
1. Download and extract the ZIP:
   - Download: [LeetcodeJavaDebugEnhancer.zip](https://github.com/SindhuraShankeshi/Leetcode-Java-Debug-Enhancer/blob/main/LeetcodeJavaDebugEnhancer.zip)
   - Extract to a working directory.
2. Open the project in your IDE:
   - If a Maven/Gradle project is present, import it using the IDE wizard.
   - If it's a plain Java project, add the extracted folder as a project/module and ensure the Java SDK is configured.
3. Explore examples:
   - Look for sample classes (e.g., `Main`, `Example`, or `src/`) inside the extracted folder.
   - Run example classes from the IDE or use the command line.
4. If a runnable JAR is included in the ZIP:
   - Run: java -jar <name-of-jar>.jar
   - If no JAR exists, compile and run main classes via your IDE or javac/java.


## Usage notes
- The project focuses on improving the debugging experience. When running examples, expect more verbose, structured output that highlights intermediate states (stack frames, array snapshots, tree traversals, etc.).
- Use the provided helpers rather than ad-hoc prints to get consistent, readable traces.

## Project structure (expected)
The ZIP contains:
- src/ — Java source files (examples, utilities, instrumentation)
- lib/ or build/ — third-party libraries or build artifacts (optional)
- README / docs / examples — additional documentation
Open the ZIP and inspect `src/` to find the main classes and example solutions.

## How to contribute
- Open an issue with a clear description of the improvement or bug you want to address.
- Fork the repository, create a feature branch, make changes, and submit a pull request describing what you changed and why.
- Add tests or example runs demonstrating the change where appropriate.

## Author / Contact
Project author: Sindhura Patel Shankeshi  
GitHub: [SindhuraShankeshi](https://github.com/SindhuraShankeshi)

---
