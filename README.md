# Markdown for GitHub READMEs

An interactive web-based guide for first-year computing students. It covers the core Markdown syntax used to write README files on GitHub, with live examples and practice exercises.

## Overview

Students work through nine reference sections covering key Markdown elements, then complete twelve interactive exercises with immediate right/wrong feedback. A starter README template with a copy button and rendered preview is included so students have a working starting point for their own projects.

## Features

- Nine reference sections covering headings, text formatting, lists, code blocks, links, images, tables, blockquotes, and horizontal rules
- Split-pane examples showing Markdown syntax alongside the rendered GitHub output
- Twelve practice exercises with case-sensitive answer checking and instant feedback
- Score tracker with a summary message at the end of the exercises
- Starter README template with a one-click copy button
- Toggle preview button that renders the template as it would appear on GitHub
- GitHub-inspired dark theme
- No dependencies — runs as a single HTML file in any browser

## How to Use

1. Open `markdown-guide.html` in a browser
2. Work through sections 01–09 to learn the syntax
3. Complete the practice exercises in section 10
4. Use the starter template in section 08 as the base for your own README

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling and layout |
| Vanilla JavaScript | Exercise logic, copy and preview functions |
| Google Fonts (DM Sans, JetBrains Mono) | Typography |

## Files

```
markdown-guide.html    — the complete guide (single file, no build step needed)
README.md              — this file
```

## Intended Audience

First-year computing students who are new to GitHub and need a practical introduction to writing README files using Markdown.

---

## Further Reading and Resources

The resources below give you extra support as you develop your Markdown skills.

### Daring Fireball – Markdown Basics

https://daringfireball.net/projects/markdown/basics

This is the original reference written by John Gruber, the creator of Markdown. It gives a clear, concise introduction to the core syntax with before-and-after examples showing what you type alongside the HTML it produces. It covers paragraphs, headings, blockquotes, phrase emphasis (bold and italic), ordered and unordered lists, links, images, and inline code. Worth bookmarking as a reliable, no-frills reference that covers everything you need at this stage.

### The Markdown Guide

https://www.markdownguide.org/

A free, open-source reference site that covers Markdown from beginner to advanced level. It is organised into clear sections:

- **Getting Started** — a gentle introduction for anyone new to Markdown
- **Basic Syntax** — covers all the core elements you will use day to day
- **Extended Syntax** — goes further with tables, fenced code blocks, footnotes, and more
- **Cheat Sheet** — a single-page summary you can refer to when writing
- **Tools** — a directory of apps and editors that support Markdown, including VS Code

It is well maintained and written in plain language, making it a practical first stop when you need to check a syntax rule quickly.

### Adam Pritchard's Markdown Cheatsheet

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

A widely used community reference that covers Markdown with rendered examples for every element. It includes everything in the basic syntax plus several GitHub-specific features, including:

- All six heading levels
- Bold, italic, strikethrough, and combined emphasis
- Ordered and unordered lists, including nested lists
- Inline and fenced code blocks with syntax highlighting
- Tables with column alignment
- Blockquotes and horizontal rules
- Links, images, and footnotes

A practical reference to keep open in a browser tab while writing your README files.

---

## VS Code Extensions for Markdown

VS Code includes built-in Markdown support. Open a preview with **Ctrl+Shift+V** or split the editor with **Ctrl+K V** to see your rendered output alongside your code. The following extensions add extra functionality.

### Recommended Extensions

**Markdown Editor v2** (free)
The extension covered in the video above. Adds keyboard shortcuts, clipboard image insertion, IntelliSense, and automatic table of contents generation. The best starting point for students using VS Code.

**Markdown All in One** (free)
Adds keyboard shortcuts for common formatting tasks such as bold, italic, and headings. It also generates and auto-updates a table of contents based on your headings, formats tables automatically, and opens a preview panel.

**Markdown Preview Enhanced** (free)
Extends the default preview with additional features including support for diagrams, mathematical notation, and export to PDF or HTML. Useful if your projects grow beyond simple README files.

**markdownlint** (free)
Checks your Markdown for style and formatting errors as you type, underlining problems in the editor. It flags common mistakes such as inconsistent heading levels, trailing spaces, and missing blank lines around headings. Useful for developing good habits early.

**Markdown Preview GitHub Styling** (free)
Changes the VS Code preview so it matches the way GitHub renders Markdown. What you see in VS Code will be closer to what your repository visitors see.

**Prettier – Code Formatter** (free)
Automatically formats your Markdown files on save, handling indentation, line length, and spacing consistently.

---

## Standalone Markdown Editors

If you want to write Markdown outside of VS Code, these two tools are worth knowing about.

### MarkdownPad (free, Windows)

A desktop editor with a real-time HTML preview panel so you see the rendered output as you type. Key features:

- Real-time HTML preview
- Customisable themes and CSS
- Export to HTML and PDF
- Pro version adds tables and auto-save

### StackEdit (free, browser-based)

A browser-based Markdown editor with a live preview that works in any browser with no installation required. Key features:

- Live preview in the browser
- Sync with Google Drive, Dropbox, and GitHub
- Supports LaTeX, UML diagrams, and publishing to blogs
- Works offline after the initial load
