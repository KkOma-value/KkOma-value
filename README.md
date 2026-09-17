<div align="center">
  <a href="https://github.com/KkOma-value">
    <img src="assets/terminal.svg?v=3" width="580" alt="Terminal session: whoami, mirage status, harness list, mirage schedule trace" />
  </a>
</div>

## now

I build **Mirage**, HelloBike's internal agent harness. A harness is the layer
nobody sees in a demo and everybody feels in daily use: how tool calls are
scheduled, how context gets compacted before it overflows, how a skill loads
without polluting the prompt, how a failed edit surfaces instead of silently
passing. The model is a component. The harness decides whether that component
is usable every day by a whole engineering org or just impressive once.

Most of the work is not prompt engineering. It is plumbing, permissions,
verification loops, and deciding what an agent must never be allowed to do
unattended.

## harness

<div align="center">
  <img src="assets/harness-pipeline.svg?v=3" width="680" alt="Mirage Harness Pipeline Architecture" />
</div>

<br/>

<p align="center">
  <a href="https://anthropic.com"><img src="https://img.shields.io/badge/Claude_Code-Anthropic-D97706?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code" /></a>
  &nbsp;
  <a href="https://openai.com"><img src="https://img.shields.io/badge/Codex-OpenAI-10A37F?style=flat-square&logo=openai&logoColor=white" alt="OpenAI Codex" /></a>
  &nbsp;
  <a href="https://deepmind.google"><img src="https://img.shields.io/badge/Antigravity-Google-4285F4?style=flat-square&logo=google&logoColor=white" alt="Antigravity" /></a>
  &nbsp;
  <a href="https://github.com"><img src="https://img.shields.io/badge/Pi-Custom_Harness-E0A458?style=flat-square&logo=gnubash&logoColor=white" alt="Pi" /></a>
</p>

I run Claude Code, Codex, Antigravity, and Pi side by side, on purpose. They
disagree about where an agent's authority ends, and reading those disagreements
is the fastest way to learn what belongs in a harness.

- **Claude Code**: The reference for tool ergonomics. Its edit and search
primitives set the bar for what an agent should be able to do without shelling
out.
- **Codex**: The reference for staying in one loop long enough to finish.
- **Antigravity**: Worth watching for how far the IDE surface can absorb the agent
instead of sitting next to it.
- **Pi**: The one I actually bend. Extensions, custom tools, skills, prompt
templates, themes, its TUI, all of it is open at the seams, so a hypothesis
about harness design takes an afternoon to test instead of a quarter to
schedule. Most of what ends up in Mirage was a Pi experiment first.

## stack

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=java,ts,python,go,spring,nodejs,nextjs,react,mysql,docker,git&theme=dark" alt="Technical Stack" />
  </a>
</p>

| Category | Stack & Tools |
| :--- | :--- |
| **Agent Runtimes** | Claude Code · OpenAI Codex · Google Antigravity · Pi |
| **Core Languages** | Java · TypeScript · Python · Go |
| **Backend & Web** | SpringBoot · Node.js · Next.js · React |
| **Data & Infra** | MySQL · Docker · Git |

## projects

- **`Mirage`**: Internal agent harness at HelloBike. Not public.
- [**`Lovemaster`**](https://github.com/KkOma-value/Lovemaster): AI-driven
application, my own testbed for agent integration outside work.

## contact

<p align="left">
  <a href="mailto:lijinhang460@gmail.com"><img src="https://img.shields.io/badge/Email-lijinhang460%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Gmail" /></a>
  &nbsp;
  <a href="https://github.com/KkOma-value"><img src="https://img.shields.io/badge/GitHub-KkOma--value-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
</p>
