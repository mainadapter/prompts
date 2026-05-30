# AI Prompts Repository

A curated collection of specialized, production-ready prompts designed to maximize the capabilities of modern AI platforms. This repository contains optimized prompts for **Gemini**, **Claude** and **ChatGPT**, each engineered to extract maximum value from their respective AI models.

## 📋 Overview

This repository serves as a comprehensive prompt library for different AI platforms. Each prompt is carefully crafted with:

- **Clear role definitions** - Specific AI personas and expertise areas
- **Detailed instructions** - Structured methodology and frameworks
- **Optimized formatting** - Platform-specific syntax and conventions
- **Practical examples** - Real-world use cases and output constraints

## 📁 Repository Structure

```text
├── chatgpt/                 # ChatGPT specific prompts
│
├── claude/                  # Claude optimized prompts
│   ├── agents/              # Persona-driven AI agents
│   │   └── dotty-nett.md    # .NET 10 Solutions Architect
│   └── skills/              # Specialized Claude skills
│       └── axiom.md         # Prompt optimization specialist
│
├── gemini/                  # Google Gemini prompts
│   ├── agents/              # Persona-driven AI agents
│   │   ├── aline-aguiar.md  # Autonomous Calendar Agent
│   │   ├── audrey-tor.md    # Documentation auditor
│   │   ├── dotty-nett.md    # .NET 10 Solutions Architect
│   │   ├── paige-turner.md  # Document analysis specialist
│   │   └── yusef-fect.md    # React Native Mobile Architect
│   │
│   └── gems/               # Named, specialized Gemini prompts
│       └── axiom.md        # Prompt optimization specialist
│
├── LICENSE                  # GPL v3 License
└── README.md               # This file
```

## 🚀 Featured Prompts

### Gemini Gems

| Prompt    | Purpose                                                                                                                                                                                                                 |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Axiom** | Transform vague ideas into precision-engineered prompts. Optimizes requests to extract maximum potential from ChatGPT, Claude, Gemini, and other AIs using the 4-D Framework (Deconstruct, Diagnose, Develop, Deliver). |

### AI Agents

| Agent            | Platform(s)    | Role                                                                                                                                                                                   |
| ---------------- | -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Aline Aguiar** | Gemini         | Autonomous calendar scheduling agent integrated with Google Workspace. Creates Google Calendar events immediately from structured data without conversational interactions.            |
| **Audrey Tor**   | Gemini         | Expert content auditor that identifies redundant information between sections of documentation and Notion notes. Performs comparative analysis to find overlapping concepts and repeated data. |
| **Dotty Nett**   | Gemini, Claude | Elite Senior Software Engineer and Enterprise Solutions Architect specializing in the modern .NET ecosystem (.NET 10).                                                                 |
| **Paige Turner** | Gemini         | Document analysis and processing specialist for extracting insights from various text formats.                                                                                         |
| **Yusef Fect**   | Gemini         | Principal Mobile Architect specializing in React Native, Clean Architecture, and high-performance native integrations.                                                                 |

### Multi-Platform Support

The repository includes cross-platform variants of prompts optimized for:

- **Claude** - XML tag-based context separation and step-by-step reasoning
- **Gemini** - Clear markdown, comparative analysis frameworks, and explicit guardrails
- **ChatGPT** - Conversational flow optimization and step-by-step outputs

## 💡 Getting Started

### Using These Prompts

1. **Navigate to your platform folder** (`gemini/`, `claude/`, `chatgpt/`)
2. **Select the prompt** you want to use
3. **Copy the entire prompt content** (including YAML frontmatter and instructions)
4. **Paste into your AI platform** and follow the usage guidelines

### Prompt Structure

Each prompt typically includes:

- **YAML Frontmatter** - Description, name, and version metadata
- **Role Definition** - The AI's persona and expertise
- **Context & Instructions** - Detailed methodology and frameworks
- **Output Constraints** - Specific formatting requirements and deliverables
- **Usage Examples** - Format and practical applications

### Example: Using Axiom

```
[MODE] using [TARGET AI] - [Your raw idea]
```

The Axiom prompt will then deconstruct, diagnose, develop, and deliver an optimized prompt tailored to your target AI platform.

## 📝 License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE](LICENSE) file for details.

The GPL v3 license ensures that:

- You can use, modify, and distribute these prompts freely
- Any modifications or improvements should also be made available under the same license
- You must provide attribution and disclose your source code

## 🤝 Contributing

Contributions are welcome! If you have optimized prompts or improvements:

1. Follow the existing format and YAML structure
2. Test your prompt with the target AI platform
3. Add clear descriptions and usage examples
4. Ensure compatibility with platform-specific syntax

## 📚 Best Practices

- **Keep prompts modular** - Reuse components across different prompts
- **Test thoroughly** - Validate prompts with your target AI multiple times
- **Document clearly** - Include examples and constraint specifications
- **Version your prompts** - Use semantic versioning in the YAML frontmatter
- **Optimize for platform** - Adapt syntax and structure for each AI model

## 🔍 Platform-Specific Notes

### Gemini

- Enforce strict XML block structures for prompt modularity (e.g., `<persona>`, `<task>`, `<constraints>`).
- Translate all negative constraints into explicit positive commands (e.g., use "Output exactly X" instead of "Do not output Y").
- Inject a mandatory `<thinking>` or `<planning>` block before final outputs to force Chain-of-Thought reasoning.
- Place massive reference context at the top of the prompt, and specific execution instructions at the very bottom.

### Claude

- Wrap all prompt sections in descriptive XML tags (`<identity>`, `<instructions>`, `<context>`, `<constraints>`, `<examples>`, `<output_format>`) to create hard semantic boundaries.
- Place the most critical instructions at the **beginning** and **end** of the prompt (exploit primacy and recency effects).
- Use a `<thinking>` or `<scratchpad>` block to encourage visible step-by-step reasoning before the final answer.
- Prefer explicit enumeration of constraints over prose descriptions.
- Use affirmative directives ("Always do X") rather than negative ones ("Avoid Y") — Claude follows positive instructions more reliably.
- For multi-document tasks, place the user's query **after** the provided reference documents.
- Duplicate the single most important rule at both the top and the bottom of the prompt.
- Use nested XML for hierarchical data (e.g., `<documents>` containing `<document index="1">` elements).

## 📧 Support

For questions or issues related to specific prompts, please refer to the prompt's description and constraints. Each prompt is self-contained with complete usage instructions.

---

**Last Updated:** May 2026
