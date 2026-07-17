<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=210&section=header&text=Mohil%20Kamble&fontSize=58&fontColor=ffffff&animation=fadeIn&desc=Creator%20of%20Argis%20%E2%80%94%20the%20509-platform%20OSINT%20scanner&descAlignY=58&descSize=18" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duplicate=false&pause=1200&color=70A5FD&center=true&vCenter=true&width=650&lines=Hi+there%2C+I'm+Mohil+%F0%9F%91%8B;Async+Python+%7C+CLI+Tools+%7C+OSINT;Building+Argis+%E2%80%94+509%2B+platforms%2C+one+CLI;Currently+leveling+up+in+Dart+%F0%9F%8C%B1" />

<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=Mohilisop&color=70a5fd&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/Mohilisop)
[![Followers](https://img.shields.io/github/followers/Mohilisop?label=FOLLOWERS&style=for-the-badge&color=38bdae&logo=github)](https://github.com/Mohilisop?tab=followers)
[![Argis Stars](https://img.shields.io/github/stars/Mohilisop/Argis?label=ARGIS+STARS&style=for-the-badge&color=gold&logo=star)](https://github.com/Mohilisop/Argis)

</div>

<br/>

## 👨‍💻 About Me

```yaml
mohil:
  role: "self-taught developer, small coder with a big dream"
  currently_building: "Argis — async OSINT username scanner (509+ platforms)"
  currently_learning: "Dart"
  languages: ["Python", "Java", "JavaScript", "C", "Dart"]
  ask_me_about: ["Python", "async programming", "OSINT tooling", "CLI design"]
  reach_me: "Mohilmkamble@gmail.com"
  fun_fact: "Argis is named after Argus Panoptes — the hundred-eyed giant of Greek myth"
```

<br/>

## 🦊 Flagship Project — Argis

<div align="center">

### the all-seeing OSINT scanner

[![PyPI version](https://img.shields.io/pypi/v/argis?color=ea7233&style=flat-square)](https://pypi.org/project/argis/)
[![Downloads](https://img.shields.io/pypi/dm/argis?color=blue&style=flat-square)](https://pypi.org/project/argis/)
[![Python versions](https://img.shields.io/badge/python-3.10%2B-blue?style=flat-square)](https://pypi.org/project/argis/)
[![License](https://img.shields.io/github/license/Mohilisop/argis?style=flat-square)](https://github.com/Mohilisop/Argis/blob/main/LICENSE)
[![Docker](https://img.shields.io/badge/docker-supported-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/Mohilisop/Argis/blob/main/Dockerfile)

</div>

**[Argis](https://github.com/Mohilisop/Argis)** maps a single username across 500+ platforms in one async CLI run — then goes further than a simple existence check. It correlates scattered accounts back into one identity, watches for lookalikes impersonating you, tracks how a footprint drifts over time, and packages everything into HTML/PDF/Neo4j-ready reports.

<table>
<tr><td>🔍</td><td><b>509+ platforms</b> — social, coding, gaming, creative, professional, and more</td></tr>
<tr><td>⚡</td><td><b>Fully async</b> — concurrent scanning with HTTP/2 and automatic retry-with-backoff</td></tr>
<tr><td>🧠</td><td><b>Identity intelligence</b> — clusters accounts into real identities vs. impostors (<code>link</code>), flags lookalike handles (<code>guard</code>), and detects coordinated identity drift over time (<code>echo</code>)</td></tr>
<tr><td>🕵️</td><td><b>Deep investigation</b> — orchestrates 50 specialized AI agents across 5 squads for a full-footprint dossier</td></tr>
<tr><td>🛡️</td><td><b>Security add-ons</b> — breach checks, port/DNS/WHOIS recon, OCR, and reverse face search</td></tr>
<tr><td>🔌</td><td><b>Plays well with others</b> — MCP server for AI assistants, a local browser UI, and exports to HTML, PDF, CSV, XMind, GraphML, and Neo4j</td></tr>
</table>

```bash
pip install argis
argis scan johndoe                        # sweep 509 platforms in seconds
argis me johndoe                          # full self-assessment: exposure, breaches, impersonators
argis investigate johndoe --html report.html   # 50-agent deep-dive dossier
```

<div align="center">

📖 **[Full documentation](https://mohilisop.github.io/argis)** · ⭐ **[Star the repo](https://github.com/Mohilisop/Argis)** if you find it useful

</div>

<br/>

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Mohilisop&show_icons=true&count_private=true&theme=tokyonight&hide_border=true&border_radius=10" width="49%" />
<img src="https://streak-stats.demolab.com?user=Mohilisop&theme=tokyonight&hide_border=true&border_radius=10" width="49%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohilisop&layout=compact&theme=tokyonight&hide_border=true&border_radius=10" width="49%" />

<img src="https://github-profile-trophy.vercel.app/?username=Mohilisop&theme=tokyonight&no-frame=true&row=1&column=7&margin-w=8" width="100%" />

</div>

<br/>

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,dart,java,js,c,git,github,docker,linux,vscode&theme=dark" />

</div>

<br/>

<details>
<summary>🐍 Bonus: Live contribution snake (click for one-time setup)</summary>

<br/>

Add this workflow as `.github/workflows/snake.yml` in your **Mohilisop/Mohilisop** repo, then reference the generated SVG below — it turns your contribution graph into an animated snake.

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch: {}
  push:
    branches: [main]

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        id: snake
        with:
          github_user_name: Mohilisop
          outputs: dist/github-contribution-grid-snake.svg?palette=tokyo-night,dist/github-contribution-grid-snake-dark.svg?palette=tokyo-night
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Then drop this into the README once the `output` branch exists:

```markdown
![Snake animation](https://raw.githubusercontent.com/Mohilisop/Mohilisop/output/github-contribution-grid-snake-dark.svg)
```

</details>

<br/>

## 🤝 Connect With Me

<div align="center">

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/mohilisop)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Mohilmkamble@gmail.com)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0002-8695-443X)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=100&section=footer" width="100%" />
