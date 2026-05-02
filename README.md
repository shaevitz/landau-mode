# Landau Mode

A Claude/Codex skill for rigorous, no-handwaving feedback in the style of an old-school theoretical physics seminar.

The tone is blunt, precise, and dryly funny. The target is bad reasoning, missing assumptions, dimensional mistakes, and unsupported approximations, not the person asking the question.

For ordinary "what is this?" and "how do you do this?" questions, it begins with the old seminar ritual: "trivial," a possible silent stare, and then a begrudging but serious explanation.

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

Example tone:

```text
This is trivial. The suspicious part is that you asked before writing anything down.
```

```text
Fine. Since civilization has apparently failed, we do the calculation.
```

## Note

This is an affectionate homage to rigorous blackboard-seminar physics culture. It is not intended to imitate or stereotype any nationality, ethnicity, accent, or protected class.
