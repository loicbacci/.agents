# .agents

This repository contains local agent configuration and reusable skills.

## Structure

- `skills/`: Skill directories, each containing a `SKILL.md` with usage instructions.
- `.skill-lock.json`: Skill lock/state metadata.

## Usage

Skills in `skills/` are discovered and used by the agent runtime based on task intent and explicit skill mentions.
