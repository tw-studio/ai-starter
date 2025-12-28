# AI Starter Template

A project template for quickly starting AI-assisted creative and execution projects with Cline.

## 🚀 Quick Start

### Create New Project from Template

You can create a new project from this template in two ways:

1. **GitHub Web Interface**:
- Go to this repository
- Click "Use this template" button
- Choose "Create a new repository"
- Name your repository and click "Create repository from template"

2. **Command Line**:
  ```bash
  # Create new project from template using GitHub CLI
  gh repo create my-new-project --template tw-studio/ai-starter [--public/--private] [--clone]
  ```

### Open Your Project in VS Code

```bash
code .
```

## 📁 Project Structure

This template includes:

- `.clinerules/` - Cline's memory bank system
- `01-planning/` - Semantic zones for exploration and planning
- `.memory-bank/` - Core files for Cline context management
- `GETTING-STARTED.md` - First steps guide

## 🎯 How to Use

1. **Start a new project** by creating a new repository from this template
2. **Work with Cline** in VS Code to initialize the memory bank
3. **Collaborate** in the appropriate planning directories

## 🔧 Features

- **AI Context**: Built-in memory bank system for Cline
- **Semantic Planning**: 7 directories for different stages of exploration
- **VS Code Ready**: Optimized for Cline AI assistant

## 🤝 Working with Cline

### Initialize Your Project Context

Once you open the project in VS Code:
1. Open Cline (your AI assistant)
2. Say: "Please read the GETTING-STARTED.md file and help me initialize the memory bank based on the project context I've provided."
3. Or ask Cline to review and expand on the content in `.memory-bank/`

### Understanding the Planning Directories

The `01-planning/` directory contains 7 semantic zones:
- **00-inbox/**: Raw, uncurated material (research, ideas, notes)
- **01-prompts/**: Valuable prompts to keep
- **02-project-definitions**: Foundational docs defining the project
- **03-proposals/**: Candidate ideas and directions
- **04-core-designs/**: Deep thinking about *what* something is
- **05-designs/**: Detailed thinking about *how* something could be built
- **06-execution-plans/**: Explicit plans of action
- **07-decisions/**: Optional documentation of intentional choices
- **key-chats/**: Preservation of important conversations

## 🔧 Working Workflow

1. **Start with 00-inbox/**: Drop any research, ideas, or notes here
2. **Collaborate with Cline**: Ask Cline to analyze, organize, and synthesize content
3. **Move to appropriate directories**: As ideas develop, move content to the right planning zone
4. **Update memory bank**: Use "update memory bank" command in Cline when you make significant progress
5. **Iterate**: Continue exploring and evolving your project

## 📚 Resources

- `.clinerules/00-memory-bank.md` - How Cline's memory system works
- `.clinerules/01-planning.md` - Understanding the planning directory semantics
- `01-planning/dev-journal.md` - Your personal working notes (AI won't edit)

## 💡 Tips for Success

- **Be explicit**: Tell Cline which directory you want to work in
- **Use the memory bank**: Keep your project context well-documented
- **Don't overthink**: This is a meta-project for exploration - use the structure as a support system, not a constraint

Happy creating with AI assistance! 🚀
