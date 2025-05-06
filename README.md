# Wireframer

## A Wireframe Generator with GitHub Copilot Agent Mode

This repo provides an environment where you can quickly create UI wireframes by leveraging GitHub Copilot’s Agent Mode to automate and streamline the code-generation process.

## Table of Contents

- [Overview](#overview)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation)  
- [Usage](#usage)

## Overview

This repo simplifies the process of creating basic UI layouts (wireframes) by using [**GitHub Copilot Agent Mode**](https://code.visualstudio.com/docs/copilot/chat/chat-agent-mode) and the [**Bootstrap**](https://getbootstrap.com/) frontend toolkit. It provides an easy way to "bootstrap" your design or prototype flows, giving you a playground to build and share early UI explorations.

Key goals:
1. Speed up product ideation and design exploration.
2. Use 
2. Provide a consistent, integrated workflow within Visual Studio Code.
3. Demonstrate the capabilities of GitHub Copilot’s Agent Mode to create and modify wireframes interactively.

## Prerequisites

1. [Visual Studio Code Insiders](https://code.visualstudio.com/insiders/)
2. [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) extension:
   - Make sure you have a GitHub Copilot license or subscription.
   - Install and enable the GitHub Copilot extension from the VS Code Marketplace.
   - Access to [Agent Mode](https://code.visualstudio.com/blogs/2025/02/24/introducing-copilot-agent-mode)

## Installation

1. Clone the Repository
   ```bash
   git clone https://github.com/agoldbe/wireframer.git
   cd wireframer
   ```

2. Open in VS Code
   - Launch Visual Studio Code and open this repository’s folder.

## Usage

1. Enable GitHub Copilot
   - Make sure Copilot is installed, signed in, and enabled in your VS Code Insiders environment.

2. Access Agent Mode
   - In VS Code Insiders, open the Copilot Edits view (⇧⌘I), select Agent from the mode dropdown.

3. Generate Initial Wireframe
   - Type a descriptive prompt. Below are some prompt examples:
     ```
     Generate a header with navigation, a hero banner, and a three-column grid for feature highlights.
     ```

     ```
     Create a minimalist personal decision tracker. A visually clean, compact interface designed to help users document and revisit important personal or career decisions. Users enter short entries for decisions they've made (e.g., job changes, moving cities, investments), along with the brief reasoning behind each choice. The app elegantly visualizes these decisions on a simple timeline. Clicking a decision expands its details, showing the initial reasoning and offering a concise reflection field to revisit later, encouraging thoughtful personal growth.
     ```

     ```
     Make a simple Todo wireframe that supports the creation, editing and deletion of Todo items. Allow the user to set the priority of each item.
     ```

4. Iterate and Refine
   - Iterate on your wireframe by providing additional prompts or instructions i.e. “Refactor the layout to have a sticky header and sidebar navigation”.
   - Preview changes in a browser or with live preview extensions like the [Microsoft Edge Tools](https://marketplace.visualstudio.com/items?itemName=ms-edgedevtools.vscode-edge-devtools) extension.