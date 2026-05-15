# Claude Skills

A collection of agent skills compatible with any agent that supports the [Agent Skills](https://docs.anthropic.com/en/docs/claude-code) format (Claude Code, Claude Desktop, and other compatible agents).

## Skills

- **[grill-me](grill-me/)** — Interview the user relentlessly about a plan or design until reaching shared understanding, resolving each branch of the decision tree.
- **[humanizer](humanizer/)** — Remove signs of AI-generated writing from text and rewrite it in the user's personal voice. Based on Wikipedia's "Signs of AI writing" guide.
- **[plan-to-issues](plan-to-issues/)** — Convert a plan into issue files, either from the current conversation (e.g., after Plan mode) or from an existing plan file on disk.
- **[triage-issue](triage-issue/)** — Triage a bug or issue by exploring the codebase to find root cause, then create a markdown issue file with a fix plan.
- **[typescript-code-principles](typescript-code-principles/)** — Organization coding principles and standards for TypeScript/JavaScript. Enforces 10 core principles when writing, reviewing, or refactoring code.
- **[write-a-skill](write-a-skill/)** — Create new agent skills with proper structure, progressive disclosure, and bundled resources.

## Usage

Install a skill by copying its folder into your agent's skills directory, or reference it directly in your project configuration. Each skill activates automatically based on its description, and can also be triggered explicitly by name.
