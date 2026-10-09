# Terminal Lab Builder

A Cowork/Claude plugin that packages the methodology behind the **Linux Terminal Lab**
(a live, stateful, single-file HTML terminal simulator covering RHEL, SUSE, Ubuntu,
Debian, and two-node clusters) as a reusable skill, so the same quality of interactive
terminal/CLI simulator lab can be reproduced for **any other platform** — Windows/PowerShell,
a cloud CLI (AWS/Azure/GCP), Docker/Kubernetes, a database shell, network gear, git, and so on.

## What's inside

| Component | Purpose |
|-----------|---------|
| `skills/interactive-terminal-lab-builder` | The full build methodology: catalog format, live-state simulation engine architecture, generated hands-on-lab exercises, the two-pass build pipeline that guarantees sample outputs are real (never hand-typed), the self-study command-explainer generator, and the combinatorial + real-browser testing discipline required before publishing. |

## Installing

Install this plugin in Claude/Cowork the same way as any other plugin bundle
(add this repository as a plugin/marketplace source, then enable it). Once
installed, the skill is picked up automatically whenever you ask Claude to
"build an interactive terminal lab for X" — you don't need to invoke it by name.

## Origin

Extracted from a real project: a six-environment Linux Terminal Lab built with a live
simulation engine for LVM/Btrfs/RAID/mdadm/Pacemaker cluster storage, validated with a
4,500-scenario combinatorial test matrix plus real-browser hand-typed validation before
each publish.

## License

MIT — see your own preference; add a LICENSE file if you plan to distribute this publicly.
