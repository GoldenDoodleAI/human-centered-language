# Human-centered language standard (agent skill)

This repository packages the **human-centered language standard** as an agent skill for Claude and other tools that load `SKILL.md` plus companion files.

## What you get

- `SKILL.md`: entry point the agent reads first.
- `standard.md`: full standard text for the skill to follow.
- `SOURCES.md`: organizations whose published guidance informed the standard.
- `PROVENANCE`: which commit of the upstream monorepo produced this export.

## Install

1. Download or clone this repository.
2. **Claude (Skills):** zip `SKILL.md` and `standard.md` together (or upload this folder) under Settings → Customize → Skills.
3. **Other agents:** load `SKILL.md`, then load `standard.md` when the skill activates.

For compiled single-file installs and trauma-informed layering, see the upstream monorepo at https://github.com/GoldenDoodleAI/trauma-informed-language.

## License

See `LICENSE`. Standard content is CC BY 4.0 unless noted there.

## Updates

Re-exports track commits of `GoldenDoodleAI/trauma-informed-language`. Compare `PROVENANCE` in this repo with the monorepo release you intend to match.
