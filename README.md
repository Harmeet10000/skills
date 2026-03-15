# Prompts Repository

> A curated collection of AI prompts, agent configurations, skills, and engineering resources for software development.

## Topics

- ai-prompts
- langchain
- langgraph
- agents
- software-engineering
- system-design
- microservices
- devops
- sre
- kubernetes
- terraform
- go
- python
- rust
- react
- typescript
- fastapi
- backend-development
- frontend-development
- product-management
- marketing-automation
- productivity-tools
- computer-science-books
- interview-preparation

## Contents

### Skills (`/skills`)
Specialized prompts and agent configurations organized by domain. All former agent configurations have been consolidated into the skills directory for better discoverability.

| Category | Count | Description |
|----------|-------|-------------|
| ai-ml | 18 | LangChain, LangGraph, RAG, AI agents |
| architecture | 9 | System design, microservices, patterns, API architecture |
| backend | 29 | Go, Python, Rust, Node, FastAPI, Linux experts |
| business | 1 | Sales engineering and business-specific skills |
| cloud-devops | 16 | Kubernetes, Terraform, DevOps, SRE |
| database | 3 | PostgreSQL, SQL optimization, DBA |
| design | 5 | UI/UX, diagrams, design systems, animation |
| engineering-tools | 5 | Code review, linting, development aids |
| frontend | 7 | React, TypeScript, Mobile, Shopify |
| legal | 1 | Legal advisory and compliance |
| marketing | 11 | SEO, lead generation, marketing psychology |
| productivity-tools | 12 | Agent orchestration, automation, skill-creator |
| product-management | 5 | PRD creation, project management, PM ideation |
| research-analysis | 10 | Data research, business analysis, risk management |
| security | 3 | Security auditing, penetration testing |
| testing | 5 | TDD, E2E testing, QA, test workflow agents |
| writing-docs | 6 | Technical writing, documentation, proposals |

**Total: 147 Skills & Agents**

### Programming Books (`/Programming Books`)
A comprehensive collection of 1,000+ technical books and resources organized across 15 categories:

- **AI Agents**: Agentic workflows and LLM applications
- **Algo Trading**: Quantitative finance and algorithmic strategies
- **Databases**: SQL, NoSQL, and data modeling
- **DevOps**: CI/CD, containerization, and infrastructure
- **Elixir**: Functional programming and concurrent systems
- **Go**: Cloud-native development and concurrency
- **Interviews**: Technical coding and architectural interview prep
- **Leadership**: Engineering management and team building
- **Linux**: Kernel internals and system administration
- **Microservices**: Distributed systems and service mesh
- **Networking**: Protocols, security, and infrastructure
- **Performance**: Systems optimization and low-latency code
- **Software Engineering**: Design patterns and clean code
- **SRE**: Reliability engineering and observability
- **System Design**: Large-scale architecture and scalability

## Usage

Skills can be loaded into AI coding assistants (like Gemini CLI or Claude Code) to provide specialized context and instructions for different development tasks. 

To use a skill, ensure it is in your `skills/` directory or add it via your CLI's install command.

## Contributing

Contributions are welcome! Here's how you can help:

1. **Add new skills** - Create a new folder in the appropriate category under `/skills/` with your skill definition (`SKILL.md` or `.agent.md`)
2. **Reorganize** - Propose better categorizations for existing skills
3. **Improve existing** - Submit improvements to current skill instructions
4. **Resources** - Suggest or add high-quality technical books to the collection

### Contribution Guidelines

- Use descriptive names for folders and files
- Follow existing file structure and naming conventions
- Include clear documentation within each `SKILL.md`
- Test your prompts before submitting

## Structure

```
prompts/
├── skills/           # Specialized prompts and agents by domain
│   ├── ai-ml/
│   ├── architecture/
│   ├── ...
├── Programming Books/  # Technical book references
│   ├── AI Agents/
│   ├── Algo Trading/
│   ├── ...
```

## License

MIT License - see [LICENSE](LICENSE) for details.
