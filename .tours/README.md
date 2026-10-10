# ADAgentAI code tours

Written for commit 4f30889 (Feb 11, 2026). Check yours with `git log -1 --format=%h`.

## Core story
- 01 - Start here (13 steps)
- 02 - Next.js basics on your app (18 steps)
- 03 - React basics on your chat page (15 steps)
- 04 - Sending a message (19 steps)
- 05 - The API inside Next.js (19 steps)
- 06 - The agent server (16 steps)
- 07 - The LangGraph graph (16 steps)
- 08 - Router and entity loader (16 steps)
- 09 - The specialist (17 steps)
- 10 - Tools and MCP (17 steps)
- 11 - The approval pause (17 steps)
- 12 - The answer on screen (14 steps)

## Production and systems
- 13 - Production (10 steps)
- 14 - Login and OAuth (11 steps)
- 15 - What's saved where (12 steps)
- 16 - Tests and observability (11 steps)
- 17 - Billing, invites and admin (8 steps)
- 18 - The design system (8 steps)

## Traces
- 19 - Trace: a read request (15 steps)
- 20 - Trace: a write request (14 steps)

## Interview
- 21 - Interview prep (14 steps)

## Function atlas (look things up)
- A01 - Atlas: agent graph (14 files)
- A02 - Atlas: agent server, streaming and tools (23 files)
- A03 - Atlas: MCP tool servers (7 files)
- A04 - Atlas: the API (29 files)
- A05 - Atlas: chat UI (57 files)
- A06 - Atlas: pages (52 files)
- A07 - Atlas: hooks, lib and contexts (44 files)
- A08 - Atlas: design system components (51 files)
- A09 - Atlas: feature components (59 files)
- A10 - Atlas: tests, scripts and the rest (21 files)

Every one of the repo's 1,770 functions is listed in the atlases. Entries marked ✎ are hand-written notes; the rest quote the function's own code comment plus facts a script checked.

`COVERAGE.md` lists all 632 files in the repo and where each one is covered.

## Setup
1. In VS Code, install the CodeTour extension (ID: vsls-contrib.codetour).
2. Put this `.tours` folder in the root of your ADAgentAI folder, next to `frontend` and `backend`.
3. Open that root folder in VS Code. In the Explorer sidebar, open the CodeTour section and start "Start here".
4. Move with the Next / Previous buttons, or Ctrl+Right / Ctrl+Left (Cmd on a Mac).
5. In an atlas, press Ctrl+G and type a line number to jump to a function.

## Keep the tours out of git
Add `.tours/` to `.git/info/exclude` so they are never committed.
