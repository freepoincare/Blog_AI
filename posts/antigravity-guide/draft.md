# Master the CLI: A Complete Guide to Google Antigravity (agy)

## Introduction: Is Your Terminal Stuck in the Past?
The era of single-tasking AI is over. If you've been using the Gemini CLI, you know how powerful a terminal-based agent can be. But have you ever felt the need for speed—or wished your agent could handle multiple tasks at once without breaking a sweat? Meet **Antigravity CLI (`agy`)**, the high-performance, Go-based successor that turns your terminal into a multi-agent command center. Whether you're a seasoned dev or just starting, this guide will show you how to harness its full potential.

## Key Highlights: Why You Should Switch Today
1. **Parallel Orchestration**: Run complex goals that spin up multiple specialized subagents simultaneously.
2. **Lightning Performance**: Near-instant startup and low overhead thanks to its Go-based architecture.
3. **Seamless Extensibility**: Easily create custom tools using "Agent Skills" or connect to local servers via MCP.

## Deep Dive: Setting Up and Using Antigravity

### 1. Installation: Getting Started in Seconds
Installing Antigravity is a breeze. Open your terminal and run the command for your platform:

- **Windows (PowerShell)**:
  ```powershell
  irm https://antigravity.google/cli/install.ps1 | iex
  ```
- **macOS / Linux**:
  ```bash
  curl -fsSL https://antigravity.google/cli/install.sh | bash
  ```
After installation, restart your terminal and type `agy --version` to confirm everything is set up.

### 2. Terminal Mastery: Commands and Shortcuts
Once inside the `agy` environment, the terminal is your playground.
- **Run Shell Commands**: Prefix any command with `!` to execute it directly (e.g., `!npm install` or `!ls -la`).
- **Slash Commands**: Use commands like `/fork` to branch your conversation or `/inspect` to see what skills are active.
- **Asynchronous Workflows**: Use `/goal "Task"` for long-running projects. You can keep chatting or ask "By The Way" questions using `/BTW`.

### 3. Configuration: Say Goodbye to `.env`
No more manual editing of hidden files. Antigravity introduces an interactive **TUI (Terminal User Interface)** for settings. Simply type:
> `/config`
This opens a visual editor where you can manage permissions, themes, and model preferences. Your settings are stored safely in `~/.gemini/antigravity-cli/settings.json`.

### 4. Custom Tools: Creating Your Own Skills
Want to teach your agent new tricks? **Agent Skills** are simple Markdown files that define how an agent should behave.
- **Global Skills**: Place them in `~/.gemini/antigravity-cli/skills/`.
- **Project Skills**: Place them in your project's `.agents/skills/` directory.
Example: A `lint.md` file in your local directory automatically gives you a `/lint` command!

## Conclusion: Elevate Your Workflow
Migrating to Antigravity CLI isn't just an update; it's a complete workflow upgrade. From the speed of the Go binary to the power of parallel subagents, `agy` is designed to keep up with the pace of modern development. Start your migration today and experience the weightless efficiency of the next generation of AI orchestration.

## References
- [Official Antigravity CLI Documentation](https://antigravity.google)
- [Dev.to: Antigravity CLI Walkthrough](https://dev.to)
- [Medium: Migrating to Antigravity 2.0](https://medium.com)
- [Pasquale Pillitteri: Antigravity CLI Technical Guide](https://pasqualepillitteri.it)
