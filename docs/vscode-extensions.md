# VS Code Extensions for OctoFit Tracker Development

This document describes the VS Code extensions configured in the devcontainer for the OctoFit Tracker project.

## Core Extensions

### GitHub Copilot
- **Extension ID**: `github.copilot`
- **Purpose**: AI-powered code completion and chat assistance
- **Usage**: Essential for this workshop, provides intelligent code suggestions and agent mode

### Markdown Linting
- **Extension ID**: `markdown-lint.markdownlinter`
- **Purpose**: Ensures consistent markdown formatting
- **Usage**: Validates documentation files for proper markdown syntax

## Python Development Extensions

### Python
- **Extension ID**: `ms-python.python`
- **Purpose**: Core Python language support
- **Usage**: Syntax highlighting, IntelliSense, debugging for Django backend

### Pylance
- **Extension ID**: `ms-python.vscode-pylance`
- **Purpose**: Fast, feature-rich Python language server
- **Usage**: Advanced type checking, auto-imports, and IntelliSense for Python

### Python Debugger (debugpy)
- **Extension ID**: `ms-python.debugpy`
- **Purpose**: Python debugging support
- **Usage**: Set breakpoints and debug Django applications

## JavaScript/React Development Extensions

### ESLint
- **Extension ID**: `dbaeumer.vscode-eslint`
- **Purpose**: JavaScript/React linting
- **Usage**: Identifies and fixes problems in JavaScript/React code, ensures code quality

### Prettier
- **Extension ID**: `esbenp.prettier-vscode`
- **Purpose**: Code formatter
- **Usage**: Automatically formats JavaScript, JSON, CSS, and HTML for consistency

### ES7+ React/Redux/React-Native Snippets
- **Extension ID**: `dsznajder.es7-react-js-snippets`
- **Purpose**: React code snippets
- **Usage**: Quickly scaffold React components with shortcuts like `rafce`, `rfc`, `useState`

### TypeScript and JavaScript Language Features
- **Extension ID**: `ms-vscode.vscode-typescript-next`
- **Purpose**: Enhanced TypeScript and JavaScript support
- **Usage**: Advanced IntelliSense and type checking for JavaScript/TypeScript files

### Auto Rename Tag
- **Extension ID**: `formulahendry.auto-rename-tag`
- **Purpose**: Automatically renames paired HTML/XML tags
- **Usage**: When editing JSX, renaming opening tag automatically renames closing tag

### Auto Close Tag
- **Extension ID**: `formulahendry.auto-close-tag`
- **Purpose**: Automatically closes HTML/XML tags
- **Usage**: Speeds up HTML/JSX editing by auto-completing closing tags

## Database Extensions

### MongoDB for VS Code
- **Extension ID**: `mongodb.mongodb-vscode`
- **Purpose**: MongoDB database management
- **Usage**: Connect to MongoDB, run queries, view collections directly from VS Code

## Version Control Extensions

### Git Graph
- **Extension ID**: `mhutchie.git-graph`
- **Purpose**: Visual git history
- **Usage**: View repository history as an interactive graph, making it easier to understand branch structure

### GitLens
- **Extension ID**: `eamodio.gitlens`
- **Purpose**: Enhanced Git capabilities
- **Usage**: Inline blame annotations, commit history, and repository insights

## Optional/Future Extensions

### Tailwind CSS IntelliSense
- **Extension ID**: `bradlc.vscode-tailwindcss`
- **Purpose**: Tailwind CSS autocomplete and preview
- **Usage**: If the project adopts Tailwind CSS for styling, provides autocomplete for utility classes

## Extension Benefits

These extensions provide:
1. **Better Code Quality**: ESLint and Prettier ensure consistent, high-quality code
2. **Faster Development**: Snippets and auto-completion speed up coding
3. **Easier Debugging**: Python debugger and enhanced error detection
4. **Database Management**: Direct MongoDB access from the editor
5. **Better Version Control**: Visual git tools for easier collaboration
6. **Enhanced IntelliSense**: Better autocomplete and type checking across all languages

## Using Extensions

All extensions are automatically installed when the Codespace is created. They are pre-configured and ready to use without any additional setup required.

### Key Features to Try

1. **GitHub Copilot**: Use `Ctrl+I` (or `Cmd+I` on Mac) to open Copilot Chat
2. **React Snippets**: Type `rafce` and press Tab to create a React arrow function component
3. **ESLint**: Problems will be automatically highlighted in your code
4. **Prettier**: Right-click and select "Format Document" or use `Shift+Alt+F`
5. **MongoDB**: Click the MongoDB icon in the sidebar to connect to your database
6. **GitLens**: Hover over any line to see git blame information
7. **Git Graph**: Click the Git Graph icon to visualize your repository history
