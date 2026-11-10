# Boss Lab Player Guide

Multilingual player reference for **Boss Lab: Robot Battle Builder**, the free Android robot boss-builder auto-battler. Written and maintained by **Boss Lab Studio, the developer of the game** (game design, code and balancing by the team; art and audio are AI-assisted).

- Docs: https://boss-lab-player-guide.readthedocs.io/en/latest/
- Official site and full guides: https://www.bosslab.xyz/blog
- Google Play: https://play.google.com/store/apps/details?id=com.bosslab.game

## Languages

| Page | Language | Topic |
|---|---|---|
| `docs/es.md` | Español | Glossary of game terms |
| `docs/pt-br.md` | Português (Brasil) | Campaign quick reference |
| `docs/de.md` | Deutsch | AI brains quick reference |
| `docs/fr.md` | Français | Part categories quick reference |
| `docs/ru.md` | Русский | Campaign vs Arena reference |
| `docs/tr.md` | Türkçe | Arena defense checklist |
| `docs/it.md` | Italiano | Fact sheet and requirements |
| `docs/pl.md` | Polski | Beginner glossary |

## Build locally

```bash
python -m venv .venv && . .venv/bin/activate
pip install -r requirements.txt
mkdocs serve        # preview at http://127.0.0.1:8000
mkdocs build --strict
```

Read the Docs builds from `.readthedocs.yaml` (Ubuntu 22.04, Python 3.12, MkDocs).
