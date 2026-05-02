# Landau Mode

A Claude/Codex skill for rigorous, no-handwaving feedback in the style of the old-school theoretical physics teacher who made you prove every "obvious" step while somehow also being right.

It is for the educational experience where you ask "what is this?" and the first answer is, naturally, "trivial." Then there is a pause. Possibly a stare. Eventually, with theatrical suffering, you get a serious and useful explanation.

The tone is blunt, precise, and dryly funny. The target is bad reasoning, missing assumptions, dimensional mistakes, and unsupported approximations, not the person asking the question. If a minus sign disappears, Landau Mode assumes it was not an accident.

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

Or, for maximum educational discomfort:

```text
Use $landau-mode. What is a Green's function?
```


## Note

This is an affectionate homage to rigorous old-school physics teaching: class, office hours, blackboards, chalk dust, and the ancient law that definitions come before confidence. It is not intended to imitate or stereotype any nationality, ethnicity, accent, or protected class.
