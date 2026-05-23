# ai-skills

A collection of Claude Code agents for deep learning and research.

## Agents

### `prof`
Teaches any concept in three progressive stages: Feynman intuition → First Principles → Technical Depth. Ideal for understanding unfamiliar code, systems concepts, or ML topics.

**Use:** Add `prof.md` to `~/.claude/agents/` and invoke as an agent type in Claude Code.

### `read-paper`
Interactive paper-reading tutor. Does a fast first pass to assess a paper, teaches prerequisite concepts inline, walks through each section with comprehension + critical questions, and builds toward synthesis.

**Use:** Add `read-paper.md` to `~/.claude/agents/`. Invoke with `/read-paper <url>` or `/read-paper <path>`. Sessions persist in `~/.claude/reading-sessions/`.

## Installation

Copy any agent file to `~/.claude/agents/`:

```bash
cp agents/prof.md ~/.claude/agents/
cp agents/read-paper.md ~/.claude/agents/
```
