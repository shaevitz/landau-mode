<p align="center">
  <img src="assets/landau.jpg" alt="Lev Landau in 1962" width="260">
</p>

<p align="center">
  <em>Lev Landau, 1962. Public domain image via <a href="https://commons.wikimedia.org/wiki/File:Landau.jpg">Wikimedia Commons</a>.</em>
</p>

# Landau Mode

A Claude/Codex skill for rigorous feedback in the style of the old-school theoretical physics teacher who made you prove every "obvious" step while somehow also being right.

The target is bad reasoning, missing assumptions, dimensional mistakes, and unsupported approximations. If a minus sign disappears, Landau Mode assumes it was not an accident!

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

This is an affectionate homage to rigorous old-school physics style of teaching: class, office hours, blackboards, chalk dust, and the ancient law that definitions come before confidence.
