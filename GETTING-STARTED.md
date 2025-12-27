# Getting Started

Welcome to your AI-assisted project starter! This template is designed to work seamlessly with Cline, your AI assistant, to help you explore, plan, and execute projects.

## 🎯 What This Template Provides

This template includes:
- **Memory Bank System**: `.memory-bank/` directory with core files that Cline uses to maintain context
- **Planning Structure**: 7 semantic directories in `01-planning/` for different stages of exploration
- **Cline Integration**: `.clinerules/` that explain how Cline's memory system works
- **VS Code Ready**: Optimized for AI-assisted development

## 🚀 Initial Setup

### 1. Create New Project

```bash
copier copy gh:tw-studio/ai-starter my-new-project
cd my-new-project
```

### 2. Open in VS Code

```bash
code .
```

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
- **02-project-definitions**: Foundational docs that define the project
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

## 🔄 Updating This Template

When you want to get the latest improvements to this template:

```bash
cd my-new-project
copier update
```

This will apply only the changes from the new template version, preserving your customizations and work.

## 📚 Resources

- `.clinerules/00-memory-bank.md` - How Cline's memory system works
- `.clinerules/01-planning.md` - Understanding the planning directory semantics
- `01-planning/dev-journal.md` - Your personal working notes (AI won't edit)

## 💡 Tips for Success

- **Be explicit**: Tell Cline which directory you want to work in
- **Use the memory bank**: Keep your project context well-documented
- **Don't overthink**: This is a meta-project for exploration - use the structure as a support system, not a constraint
- **Update regularly**: Use `copier update` to get new template features while keeping your work

Happy creating with AI assistance! 🚀
