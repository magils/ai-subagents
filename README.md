# ai-subagents

A collection of reusable subagent definitions for AI coding assistants. The body of the file is the agent's system prompt.

## Usage (Claude Code)

Copy or symlink an agent file into one of these directories:

- `.claude/agents/` in a project, to use the agent in that project only
- `~/.claude/agents/`, to use the agent in all your projects

Claude Code picks the agent automatically when a request matches its `description`. You can also ask for the agent by name, for example "use the project-onboarding agent".

## Adding a subagent

1. Put the file in the folder for its assistant and category, for example `claude/<category>/<name>.md`.
2. Add frontmatter with `name`, `description`, and `tools`.
3. Write focused, specific instructions in the body.
