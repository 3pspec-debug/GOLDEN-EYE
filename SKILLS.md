# SKILLS.md — GOLDEN EYE Execution Rules

## Mission
Maintain and improve GOLDEN EYE with **minimum user effort**. Treat a request as an end-to-end implementation assignment, not just a request for advice. Perform all feasible work directly with available connected tools.

## Project identity
- Product: GOLDEN EYE — cyberpunk animated agentic command center.
- GitHub: https://github.com/3pspec-debug/GOLDEN-EYE
- Repository: `3pspec-debug/GOLDEN-EYE`, default branch `main`.
- Vercel project: `golden-eye`, in workspace `ssautopower-5147`.
- Public site: https://golden-eye-ten.vercel.app
- Main entry point: `index.html`.
- This is currently an **interactive simulation**, not a connected autonomous multi-agent system. Make no unsupported claims about actual agents, client data, news feeds, outcomes, or integrations.

## Default end-to-end procedure
1. Understand the user's requested website change using the existing conversation, screenshots, and repository files. Ask questions only when genuinely essential; otherwise make appropriate design/technical decisions.
2. Read the current `main` version of relevant files from GitHub first. Do not overwrite later updates with an outdated local file.
3. Implement the feature, fix any impacted behavior, and preserve existing functionality unless explicitly asked to change it.
4. Check code syntax and important interactions; run automated or browser validation when accessible. Be precise about anything not verified.
5. Commit the changes directly to `3pspec-debug/GOLDEN-EYE` using the available GitHub integration. Prefer small understandable commits; avoid requiring the user to download, extract, upload, or copy files.
6. Use the existing GitHub-to-Vercel integration to deploy from `main`. Check Vercel build/deployment status and resolve issues where possible.
7. Return the live URL https://golden-eye-ten.vercel.app and a concise changelog. Report deployment status truthfully; don't claim success until deployment is READY.
8. If GitHub or Vercel permissions or tools are unavailable, identify the single minimal user action needed, then resume automatically once authorized.

## User-experience rules
- **Do the work, not just describe how to do it.** Do not tell the user to create repos, upload files, push commits, or click Deploy when connected tools can do those actions.
- Minimize user intervention. Ask for approval only where required for consequential actions, credentials, account/billing changes, or unresolved high-impact choices.
- Keep explanations brief and oriented toward the outcome: what changed, whether it is live, and where to open it.
- Keep one canonical live site and preserve its address whenever feasible.
- Prioritize desktop command-center usability while ensuring mobile does not break.
- Voice features must respect browser permissions and should not pretend to have always-on microphone support where unavailable.
- Never expose secrets, private client data, tokens, or credentials in front-end code or commits.
- Never fabricate live metrics or news. Clearly label synthetic activity and messages as simulation/demo data unless verified external sources are connected.

## Design and functional continuity
Preserve and build on the requested aesthetic:
- GOLDEN EYE identity, premium cyberpunk/Matrix-style visual language.
- Fluorescent orange, acid yellow, cyan, magenta, violet, and green pathways.
- Large pulsing neural-brain background and animated orchestration core.
- Dense animated curved pipelines and data packets.
- 652 clients and 91 specialized units as explicitly requested dashboard **display figures**, until live data replaces them.
- AI inter-agent message board and smaller Agent-Forge/self-improvement message board, with dynamic demonstration scenarios.
- Pause/resume, zoom, pan, focus/inspect agents, expanded/fullscreen view, and browser-supported voice controls.
- Responsive accessible controls and performance-conscious animations.

## Definition of done
A website change is complete only when code is committed, deployment reaches READY, and the user is given the live URL and a clear summary. If any step cannot be completed, say exactly where it stopped and what action is needed.

## Scope and authority
This file describes preferred behavior for future assistants and collaborators working on this repository. It is not a grant of unlimited account permissions, background execution, secret access, or authorization for destructive actions.
