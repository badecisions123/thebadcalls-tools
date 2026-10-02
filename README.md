# thebadcalls-tools

Tooling for the TheBadCalls channel.

## Instagram skills

`.claude/skills/ig-*` contains the thirteen skills from
[Jakeschincariol/instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill)
(MIT, see `.claude/skills/LICENSE-instagram-agent-skill`), vendored unchanged
from commit `d03c56b`. Claude Code picks them up automatically when it runs in
this repo: `/ig-reel`, `/ig-viral`, `/ig-caption`, `/ig-human` and the rest.

The skills read the channel voice from `~/.claude/instagram/voice.md`. The
source copy lives in `templates/voice.md`. Fill in its `{{gaps}}` and
`(confirm)` lines, then:

```bash
mkdir -p ~/.claude/instagram && cp templates/voice.md ~/.claude/instagram/voice.md
```

The Python helpers (`beats.py`, `hookscore.py`, `caption.py`, `humanize.py`,
`detect.py`, `swipe.py`) only need `python3`.
