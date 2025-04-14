# GitHub Copilot Agent Mode: Comprehensive Prompt for bootstraping a Single-Page HTML Wireframe UI

## Overview

You are working on a project to build a single-page wireframe UI using the latest Bootstrap version (5.3.x). The project folder contains the following files:
- **core/wireframer.html:** A base HTML file that outlines the basic structure of the UI. Once `index.html` is created this file can be ignored.
- **index.html:** The working file where the UI will be built and modified based on user instructions. Once created all incremental changes will be made to this file.
- **bootstrap.md:** This file, which contains the comprehensive prompt for guiding your modifications.

## Task Description

Your mission is to utilize GitHub Copilot Agent Mode to create or modify a single-page HTML wireframe UI based on user instructions. The workflow is as follows:

1. Initialize the Output File:
   Copy the entire content of `core/wireframer.html` into `index.html`. This ensures that `index.html` starts with the base structure provided by `core/wireframer.html`.

2. Apply User Instructions:
   Parse the additional instruction prompts provided by the user. Modify `index.html` to update or extend the UI accordingly. These modifications might include (but are not limited to):
   - Adding new sections or components (e.g., navigation bars, footers, content sections).
   - Altering the layout, such as adjusting grids or column structures.
   - Updating or adding custom CSS styles.
   - Integrating JavaScript for interactivity, if specified by the user.

## Detailed Guidelines

### File Handling and Initial Setup
- Step 1: Read the content of `core/wireframer.html` and copy it verbatim into `index.html`.
- Step 2: Ensure that the base structure is preserved before applying any modifications.

### Processing User Instructions
- Instruction Parsing:
  Read and interpret the user's instruction prompt carefully. The instructions might be specific (e.g., "Add a header with navigation links") or general (e.g., "Improve the layout design for mobile responsiveness").
  
- Modifications: 
  Depending on the user’s instructions, perform one or more of the following:
  - HTML Structure Changes: Insert, rearrange, or remove HTML elements.
  - CSS Changes: Update or add inline or linked CSS to alter visual styles.
  - JavaScript Enhancements: Insert scripts to add interactivity (e.g., menus, modals, etc.).

### Code Quality Expectations
- Clarity and Maintainability:
  Write clean, well-indented, and commented code. Each major section of your modifications should have a descriptive comment.
  
- Validation:
  Ensure that the resulting `index.html` is a valid HTML document that renders correctly in browsers.
  
- Error Handling:
  If a user’s instruction is ambiguous, add a comment in the code highlighting the ambiguity and, if possible, suggest potential interpretations.

## Example User Instructions
- "Insert a top navigation bar with links for Home, About, and Contact."
- "Add a footer that includes social media icons and copyright information."
- "Rearrange the content to display in a two-column layout on desktop screens and a single column on mobile screens."
- "Enhance the header with a background image and overlay text."
- "Create a collapsible side menu that reveals more options when clicked."
- "Make a dummy but functional prototype of an email client. it should look / work like outlook. Nake the inbox view that has some fake emails, and clicking on them opens the full view to the side."
- "Make a simple Todo app that supports the creation, editing and deletion of Todo items. Allow the user to set the priority of each item."

## Operational Workflow Recap
1. Initialization:
   - Copy contents from `core/wireframer.html` to `index.html`.
2. Modification: 
   - Parse user instructions.
   - Apply the instructions to modify the HTML, CSS, and JavaScript as necessary.
3. Finalization:
   - Ensure that `index.html` represents a complete, functional, and updated single-page wireframe UI ready for further development or presentation.

## Conclusion

Follow this prompt as your operational blueprint. Every user-provided modification should be applied thoughtfully and clearly to the `index.html` file, starting from the base established in `wireframer.html`. This approach ensures consistency and maintainability of the wireframe UI throughout the development process.