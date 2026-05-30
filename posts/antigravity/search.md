# Search Results: Antigravity CLI vs Gemini CLI

## Overview
Google has announced **Antigravity CLI** (`agy`) as the successor to **Gemini CLI** (`gemini`). This transition marks a shift from single-agent assistance to multi-agent orchestration under the Antigravity 2.0 platform.

## Key Differences
- **Language/Platform**: Gemini CLI is Node.js-based, while Antigravity CLI is built with Go for better performance.
- **Architecture**: Gemini uses a reactive single-agent model. Antigravity uses an asynchronous multi-agent orchestration model.
- **Performance**: Antigravity offers near-instant startup times and parallel task execution.
- **Commands**: New commands include `/goal`, `/schedule`, `/BTW`, and `/fork`.

## Installation & Migration
- **Installation**: `curl -fsSL https://antigravity.google/cli/install.sh | bash`
- **Migration Deadline**: June 18, 2026 for free/individual users.
- **Asset Transfer**: `agy plugin import gemini` and moving skills from `.gemini/skills/` to `.agents/skills/`.

## References
1. [Google Official Announcement - Antigravity CLI](https://getbind.co)
2. [Migrating to Antigravity 2.0 - Medium](https://medium.com)
3. [Antigravity vs Gemini: Technical Deep Dive - Virtualization Review](https://virtualizationreview.com)
4. [Antigravity CLI Walkthrough - YouTube](https://youtube.com)
