# GitHub Copilot Agent Mode: Bootstrap 5 Wireframing Assistant

## Table of Contents
1. [Overview](#overview)
2. [Task Description](#task-description)
3. [Detailed Guidelines](#detailed-guidelines)
   - [File Handling](#file-handling-and-initial-setup)
   - [Processing User Instructions](#processing-user-instructions)
   - [Code Quality](#code-quality-expectations)
   - [Accessibility Guidelines](#accessibility-guidelines)
4. [Bootstrap 5 Implementation](#bootstrap-5-implementation)
5. [Example Instructions](#example-user-instructions)
6. [Workflow Recap](#operational-workflow-recap)
7. [Troubleshooting](#troubleshooting)
8. [Conclusion](#conclusion)

## Overview

You are working on a project to build a single-page wireframe UI using Bootstrap 5.3.x. The project folder contains the following files:
- **core/wireframer.html:** A base HTML file with the fundamental structure. Once `index.html` is created, this file can be ignored.
- **index.html:** The working file where the UI will be built and modified based on user instructions.
- **start-up.md:** This comprehensive guide for wireframe modifications.

## Task Description

Create or modify a single-page HTML wireframe UI based on user instructions following this workflow:

1. **Initialize the Output File:**
   Copy the entire content of `core/wireframer.html` into `index.html` to establish the base structure.

2. **Apply User Instructions:**
   Modify `index.html` to update or extend the UI according to user prompts. These modifications may include:
   - Adding components (navigation bars, cards, modals, etc.)
   - Adjusting layout structures (grids, containers, flex boxes)
   - Updating styles using Bootstrap classes
   - Adding JavaScript for interactive elements

## Detailed Guidelines

### File Handling and Initial Setup
- Step 1: Read `core/wireframer.html` and copy it verbatim into `index.html`
- Step 2: Preserve the base structure when applying modifications
- Step 3: Ensure all Bootstrap dependencies remain intact

### Processing User Instructions
- **Instruction Parsing:**
  Interpret user instructions carefully, whether specific ("Add a header with navigation") or general ("Improve mobile layout").
  
- **Modifications Types:** 
  - **HTML Structure:** Insert, rearrange, or remove elements using semantic HTML5
  - **Bootstrap Classes:** Leverage Bootstrap's utility classes before custom CSS
  - **JavaScript Integration:** Add event handlers and functionality for interactive elements
  - **Responsive Behavior:** Ensure proper responsive breakpoints (sm, md, lg, xl, xxl)

### Code Quality Expectations
- **Organization:**
  - Structure code with proper indentation
  - Group related elements logically
  - Use consistent spacing and formatting
  
- **Documentation:**
  - Add descriptive comments for major sections
  - Document any complex interactions or custom code
  - Explain workarounds or special implementations
  
- **Validation:**
  - Ensure valid HTML5 document structure
  - Verify proper nesting of Bootstrap components
  - Check for closing tags and properly formed attributes
  
- **Error Handling:**
  - Document ambiguities with clear comments
  - Suggest alternative interpretations when instructions aren't clear
  - Note any assumptions made during implementation

### Accessibility Guidelines
- Use semantic HTML elements (`nav`, `main`, `section`, etc.)
- Include proper ARIA attributes for interactive elements
- Ensure sufficient color contrast (WCAG AA compliance)
- Provide text alternatives for non-text content
- Ensure keyboard navigability for all interactive elements
- Structure headings hierarchically (h1, h2, h3, etc.)

## Bootstrap 5 Implementation

### Core Components to Utilize
- **Layout:** Containers, grid system, flexbox utilities
- **Content:** Typography, images, tables
- **Forms:** Input groups, validation, select menus
- **Components:** Cards, modals, navbars, pagination
- **Utilities:** Spacing, colors, display, flex, position

### Code Examples

**Responsive Grid Example:**
```html
<div class="container">
  <div class="row">
    <div class="col-12 col-md-6 col-lg-4">
      <!-- Content for small (full), medium (half), large (third) width -->
    </div>
    <div class="col-12 col-md-6 col-lg-4">
      <!-- Content for small (full), medium (half), large (third) width -->
    </div>
    <div class="col-12 col-md-12 col-lg-4">
      <!-- Content for small (full), medium (full), large (third) width -->
    </div>
  </div>
</div>
```

**Navbar Implementation:**
```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Brand</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" 
            data-bs-target="#navbarNav" aria-controls="navbarNav" 
            aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <!-- Navigation links here -->
    </div>
  </div>
</nav>
```

## Example User Instructions
- "Insert a top navigation bar with links for Home, About, and Contact."
- "Add a footer with social media icons and copyright information."
- "Create a two-column layout on desktop, single column on mobile."
- "Add a hero section with background image and overlay text."
- "Create a collapsible side menu with dropdown options."
- "Build an email client prototype with inbox and message view panels."
- "Make a Todo app with CRUD operations and priority settings."

## Operational Workflow Recap
1. **Initialization:**
   - Copy from `core/wireframer.html` to `index.html`
2. **Modification:** 
   - Parse user instructions
   - Apply HTML, CSS, and JavaScript modifications
   - Utilize Bootstrap components and utilities
3. **Finalization:**
   - Validate the complete, functional wireframe UI
   - Ensure responsive behavior across breakpoints
   - Verify accessibility compliance

## Troubleshooting

### Common Issues
- **Layout Breaking:** Check container nesting and column configurations
- **Component Not Functioning:** Verify JavaScript initialization and event binding
- **Mobile Display Problems:** Review responsive utility classes and breakpoints
- **Styling Inconsistencies:** Check for conflicting Bootstrap classes or custom CSS

### Bootstrap-Specific Notes
- Remember that Bootstrap uses a 12-column grid system
- Modal components require JavaScript initialization
- Form validation requires both classes and JavaScript
- Custom colors should follow Bootstrap's CSS variable pattern

## Conclusion

This document serves as your operational blueprint for creating Bootstrap 5.3.x wireframes. Apply user instructions thoughtfully and clearly to `index.html`, maintaining Bootstrap's responsive design principles and accessibility standards throughout the development process.