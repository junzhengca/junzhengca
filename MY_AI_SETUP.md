# My AI Agent Setup

> ⚠️ Note: This is not the AI setup for my work at Google, this is for my personal stuff. If you are looking for Google AI agents, Gemini CLI would be the closest tool.

## Models

| Model | Speed ⚡ | FE Engineering 🎨 | Complex Reasoning 🧠 | Computer Use 🖥️ | Document Writing 📝 | Instruction Following 🫡 | Price 💰 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Gemini 3 Pro** | 🟡 Moderate | 🏆 Elite | 🟢 Very High | 🔵 High | 🟢 Very High | 🔵 High | 🟡 Moderate |
| **Gemini 3 Flash** | 🟢 Very High | 🏆 Elite | 🔵 High | 🟢 Very High | 🟡 Moderate | 🔵 High | 🟢 Low |
| **GLM-4.7** | 🐢 Low | 🔵 High | 🏆 Elite | 🔵 High | 🔵 High | 🔵 High | 🏆 Best (Coding Plan) |
| **Claude Sonnet 4.5** | 🔵 High | 🟢 Very High | 🔵 High | 🏆 Elite | 🟢 Very High | 🟢 Very High | 🟡 Moderate |
| **Claude Opus 4.5** | 🐢 Low | 🔵 High | 🏆 Elite | 🟢 Very High | 🏆 Elite | 🏆 Elite | 🔴 Very High |
| **Cursor Composer 1** | 🟢 Very High | 🔵 High | 🟡 Moderate | 🔵 High (IDE) | 🔴 Low | 🔵 High | 🟡 Moderate |
| **GPT 5.2** | 🟡 Moderate | 🔵 High | 🟢 Very High | 🟢 Very High | 🏆 Elite | 🏆 Elite | 🔴 Very High |

🎨 For Frontend Engineering (React, UI/UX)
- Best Choice: Gemini 3 Family (Pro or Flash)
- Why: They are the only models rated "Elite" for frontend engineering. Use Flash if you want high speed and low cost, or Pro if you need a balance of reasoning power.

🧠 For Complex Reasoning & Architecture
- Best Value: GLM-4.7
- Why: It matches the "Elite" reasoning capabilities of the most expensive models but offers the Best Price via its coding plan. The trade-off is it is much slower.
- Premium Option: Claude Opus 4.5 if budget is not a concern and you need top-tier documentation alongside reasoning.

🖥️ For Agentic Work & Computer Control
- Best Choice: Claude Sonnet 4.5
- Why: It is the "Elite" leader for Computer Use, making it the best at autonomously navigating interfaces or complex multi-step workflows.

📝 For Documentation & Strict Instructions
- Best Choice: GPT 5.2 or Claude Opus 4.5
- Why: Both are "Elite" at writing documents and following strict instructions. Choose GPT 5.2 if you need slightly faster generation than Opus.

⚡ For "Flow State" Coding
- Best Choice: Cursor Composer 1 or Gemini 3 Flash
- Why: Their "Very High" speed ensures you aren't waiting around for code completions, keeping you in the zone.

## Model/Agent Harnesses

| Harness | Type | Core Philosophy | Autonomy Level | Key "Killer" Feature | Best For... |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Cursor** | **IDE** (Fork) | **"Flow State"** <br> Keep the dev coding, AI assists inline. | **Collaborative** <br> You drive, it navigates. | **Composer Mode** <br> Edit multiple files simultaneously with a single prompt while seeing a live diff. | **Getting Sh\*t Done.** <br> Daily production coding where you need speed and control. |
| **Google Antigravity** | **IDE** (Fork) | **"Mission Control"** <br> You manage agents, you don't just code. | **Fully Autonomous** <br> Parallel agents plan & execute tasks in background. | **Artifacts & Parallelism** <br> Spawns multiple agents to work on different tasks (e.g., one refactors, one updates docs) simultaneously. | **Vibe Coding / Architecture.** <br> Building prototypes or managing large refactors without touching every line. |
| **Oh My Opencode** | **Terminal** (TUI) | **"Hacker's Knife"** <br> Linux-style modularity & freedom. | **Scriptable Agent** <br> "Sisyphus" agent loops until the job is done. | **Multi-Model Orchestration** <br> Pipes data between Claude, Gemini, and GPT-5 automatically based on the task type. | **Power Users.** <br> Devs who live in `tmux` and want full control over their agent's logic. |
| **Claude Code** | **CLI** | **"Unix Philosophy"** <br> Unopinionated, pipeable, text-based. | **Task-Based** <br> "Do X, then stop." | **Deep Shell Integration** <br> Can execute bash commands, run tests, and fix errors directly in your terminal. | **DevOps & Scripting.** <br> Automating complex shell tasks, git workflows, or quick codebase queries. |
| **Gemini CLI** | **CLI** | **"Cloud Native"** <br> Direct line to Google's brain. | **ReAct Loop** <br> Reason -> Act -> Observe loops. | **Search Grounding** <br> Native access to Google Search to fetch real-time docs/libs while coding. | **Quick Answers & Cloud.** <br> When you need up-to-date info or are working heavily in the Google Cloud ecosystem. |
