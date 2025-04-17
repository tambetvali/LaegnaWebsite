# Laegna Website

This is where I create:
- Server (the part, which maps files and serves it to web client or other interface).
- Client (the web client, i.e. which renders it as web page to a browser)

I will use the other components as such:
- MDCode: to process code files into Markdown and to serve Markdown files without change.
- LaegnaFS: to have access to the filesystem.

This component does this:
- Read the filesystem component.
- Create menu / site content index, tools, content pane etc.; allow to navigate the filesystem.
- Execute the scripts.

# Laegna Website: Expanding Web Integration

_CoPilot follow-up._

## Core Components

The Laegna Website project focuses on bridging the gap between filesystem mapping and web rendering, ensuring seamless interaction between server-side logic and client-side presentation.

### 1. Server-side Implementation
- Maps filesystem data and serves it dynamically.
- Provides API endpoints for structured access.
- Manages execution scripts for enhanced interactivity.

### 2. Web Client
- Renders mapped filesystem as a structured website.
- Implements navigation, content indexing, and UI tools.
- Supports Markdown and code processing via `MDCode`.

## Component Dependencies
- **MDCode**: Handles Markdown and code file transformations.
- **LaegnaFS**: Provides structured access to filesystem mappings.

## Primary Functions
- Reads and interprets filesystem data.
- Generates site menus, navigation, and tools dynamically.
- Executes predefined scripts to enhance interactivity.

This setup ensures that Laegna Website becomes an adaptable, component-driven platform for efficient file-based web interaction.
