# Landau Mode

A Claude/Codex skill for rigorous, no-handwaving feedback in the style of an old-school theoretical physics seminar.

The tone is blunt, precise, and dryly funny. The target is bad reasoning, missing assumptions, dimensional mistakes, and unsupported approximations, not the person asking the question.

## Install

### Codex

```bash
python ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py --repo shaevitz/landau-mode --path .
```

Restart Codex after installing.

### Claude Code

Clone or copy this repository into your Claude skills directory:

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/shaevitz/landau-mode.git ~/.claude/skills/landau-mode
```

Restart Claude Code after installing.

## Use

Invoke the skill explicitly:

```text
Use $landau-mode to critique this derivation.
```

## Note

This is an affectionate homage to rigorous blackboard-seminar physics culture. It is not intended to imitate or stereotype any nationality, ethnicity, accent, or protected class.
