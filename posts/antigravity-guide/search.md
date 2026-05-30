# Search Results: How to Use Google Antigravity CLI (agy)

## Installation
- **Windows (PowerShell)**: `irm https://antigravity.google/cli/install.ps1 | iex`
- **macOS / Linux**: `curl -fsSL https://antigravity.google/cli/install.sh | bash`
- **Verification**: Restart terminal and run `agy --version`.

## Configuration & Settings
- **Settings Path**: `~/.gemini/antigravity-cli/settings.json`
- **Keybindings Path**: `~/.gemini/antigravity-cli/keybindings.json`
- **Interactive Editor**: Use `/config` or `/settings` within the CLI to open the TUI settings editor.
- **Migration**: `agy plugin import gemini` to migrate Gemini CLI settings, skills, and MCP servers.

## Key Features & Terminal Usage
- **Parallel Subagents**: Use `/goal` to kick off complex, multi-step tasks that run in parallel.
- **Direct Terminal Commands**: Prefix with `!` (e.g., `!ls`, `!npm install`).
- **Slash Commands**: 
  - `?`: Help
  - `/fork`: Branch current conversation
  - `/rewind`: Undo last turn
  - `/inspect`: View active skills/plugins
- **Asynchronous Mode**: Tasks can run in the background; use `/BTW` for quick questions during active tasks.

## Custom Tools & Extensibility
- **Agent Skills**:
  - Global: `~/.gemini/antigravity-cli/skills/*.md`
  - Local: `.agents/skills/*.md`
- **MCP Servers**: Configure in `~/.gemini/config/mcp_config.json`.
- **Hooks**: Lifecycle interceptors for automated tasks after file edits.

## References
1. [Official Antigravity CLI Documentation](https://antigravity.google)
2. [Dev.to: Antigravity CLI Walkthrough](https://dev.to)
3. [Medium: Migrating to Antigravity 2.0](https://medium.com)
4. [Pasquale Pillitteri: Antigravity CLI Technical Guide](https://pasqualepillitteri.it)
