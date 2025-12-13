# Physical AI & Humanoid Robotics Book

A comprehensive guide to Physical AI and Humanoid Robotics built with Docusaurus using a specification-driven approach.

## About This Project

This book explores the fascinating intersection of artificial intelligence and physical systems, focusing on the design, control, and implementation of humanoid robots that can interact with the real world. The project uses a specification-driven approach to create educational content about Physical AI and Humanoid Robotics.

## Project Structure

```
.specify/                 # Specification toolkit configuration
├── memory/              # Project constitution and guidelines
│   └── constitution.md  # Project constitution
├── scripts/             # Automation scripts
└── templates/           # Specification templates
specs/                   # Project specifications
└── book-creation/       # Book creation specifications
    ├── spec.md          # Main specification
    ├── plan.md          # Implementation plan
    └── tasks.md         # Detailed tasks
history/                 # Historical records
├── prompts/             # Prompt history records
│   ├── constitution/    # Constitution-related prompts
│   └── book-creation/   # Book creation prompts
└── adr/                 # Architecture decision records
my-website/              # Docusaurus website (main book content)
├── docs/                # Documentation content
├── src/                 # Source code
├── static/              # Static assets
├── docusaurus.config.ts # Docusaurus configuration
├── sidebars.ts          # Navigation configuration
└── package.json         # Dependencies
```

## Deployment

The main book is located in the `my-website` directory and can be deployed to:

### Vercel (Recommended)
[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/your-username/final-book&project-name=physical-ai-book&repo-name=physical-ai-book)

### GitHub Pages
The project is also configured for GitHub Pages deployment.

For detailed deployment instructions, see the [Deployment Guide](./docs/deployment-guide.md).

## Getting Started

1. Review the [constitution](.specify/memory/constitution.md) for project guidelines
2. Examine the [main specification](specs/book-creation/spec.md) for requirements
3. Follow the [implementation plan](specs/book-creation/plan.md) for development
4. Check the [task list](specs/book-creation/tasks.md) for current work items

## Local Development

1. Navigate to the `my-website` directory:
   ```bash
   cd my-website
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

## Development Workflow

This project follows a specification-driven development approach:
1. Create/update specifications in `specs/`
2. Implement according to specifications
3. Validate against requirements
4. Document decisions in ADRs when necessary
5. Record prompt history for traceability

## Features

- 🤖 Comprehensive guide to Physical AI and Humanoid Robotics
- 📚 Well-structured chapters with clear learning objectives
- 🎨 Futuristic, premium UI with light/dark mode support
- 📱 Fully responsive design
- 🔍 Built-in search functionality
- 📖 Easy navigation and reading experience

## Contributing

Feel free to contribute to this project by submitting issues or pull requests.

## License

This project is open source and available under the [MIT License](./LICENSE)."# Physical-AI-Humanoid-Robotics-Book" 
