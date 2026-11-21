<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=170&section=header&text=Nguyen%20Thanh%20Bao&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=AI%20Engineering%20Student%20%40%20HCMUS&descSize=16&descAlignY=58" width="100%" alt="Nguyen Thanh Bao — AI Engineering Student at HCMUS"/>

<a href="https://github.com/NTBao-coder">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&pause=1200&color=2C9CDB&center=true&vCenter=true&width=640&lines=Read+the+paper.+Build+the+system.+Measure+the+result.;Logic+agents+%C2%B7+Machine+learning+%C2%B7+Data+pipelines;Currently%3A+parsing+arXiv+LaTeX+into+trees" alt="Typing intro"/>
</a>

<p>
  <a href="https://ntbao-coder.github.io/"><img src="https://img.shields.io/badge/Portfolio-ntbao--coder.github.io-0f172a?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"/></a>
  <a href="https://ntbao-coder.github.io/bao-reads-papers/"><img src="https://img.shields.io/badge/Paper%20Notes-Bao%20Reads%20Papers-b31b1b?style=for-the-badge&logo=arxiv&logoColor=white" alt="Paper notes"/></a>
  <a href="https://www.facebook.com/thanh.bao.386014"><img src="https://img.shields.io/badge/Facebook-Connect-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"/></a>
</p>

</div>

## 👋 About me

```python
class Bao:
    school    = "University of Science, VNU-HCM (HCMUS) · Vietnam"
    pursuing  = "AI Engineering: models whose behaviour I can explain and measure"
    interests = ["logic & search agents", "machine learning", "LLM / RAG systems", "applied math & statistics"]
    habits    = ["read the paper first", "test before trusting a number", "write ADRs"]

    def now(self):
        return [
            "Leading a 4-person team on arXiv Reference Matching (crawl → parse LaTeX → match references)",
            "Logging every paper I read with a four-pass method",
            "Turning NBA Cup Predictor into a daily-updated dashboard",
        ]
```

## 🧭 What this profile should show you

| | What to look for | Where it is |
|---|---|---|
| **Identity** | AI engineering: agents, ML, data pipelines | everything below 👇 |
| **Technical depth** | Algorithms written from scratch, not only called from a library | DPLL SAT solver and CNF encodings in [Griductive Solver](https://github.com/NTBao-coder/Griductive_Game_solve) |
| **Engineering** | Module boundaries, tests, ADRs, reproducible runs | Engine/Agent split in Griductive; ADRs + pytest in [arXiv Reference Matching](https://github.com/hcmus-arxiv-reference/arxiv-reference-matching) |
| **Research** | Reading papers, running ablations, comparing to baselines | [Bao Reads Papers](https://ntbao-coder.github.io/bao-reads-papers/) · ablations in Griductive · baseline in NBA Cup |
| **Evidence** | Numbers, logs and demos you can re-run | the *Evidence* column below |

## 🚀 Featured projects

| Project | Problem | What I built | Evidence |
|---|---|---|---|
| 🧩 **[Griductive Solver](https://github.com/NTBao-coder/Griductive_Game_solve)**<br><sub>Propositional logic · AI agents</sub> | Solve a deduction puzzle **without ever guessing**: a verdict is played only when it is logically entailed. | Automatic CNF encoder (direct, Sinz sequential counter, Tseitin XOR), **DPLL SAT solver from scratch** with two-watched literals and Jeroslow–Wang branching, a deductive agent that only sees public state, and a std-lib web GUI. | **12/12** puzzles solved; both deliberately broken puzzles flagged (`STUCK`, `INCONSISTENT`). Model cache cuts SAT calls **44 %** (1,281 → 718) across the benchmark. DPLL tested against brute force. |
| 🏀 **[NBA Cup Predictor](https://github.com/NTBao-coder/nba-cup-predictor)**<br><sub>Machine learning · Simulation</sub> | Predict the NBA Cup champion when each season gives only **one** label. | Symmetric logistic regression on ~7,000 games with leak-free features and season shrinkage, then **Monte Carlo** of the full bracket with the official tiebreak rules. | Holdout 2025-26 (1,225 games): accuracy **0.688** vs 0.554 home-team baseline; log-loss 0.597; Brier 0.205. |
| 📚 **[arXiv Reference Matching](https://github.com/hcmus-arxiv-reference/arxiv-reference-matching)**<br><sub>Data science · Team lead</sub> | Link the BibTeX entries in arXiv LaTeX sources to Semantic Scholar references. | Batched crawl pipeline with parallel reference download, shared schema, ADR-driven design, pytest suite. Leading a team of 4. | My range: **4,941 / 5,000** publications crawled (missing ones are mostly arXiv 404s). Parsing and matching milestones in progress. |
| 📝 **[Bao Reads Papers](https://ntbao-coder.github.io/bao-reads-papers/)**<br><sub>Research practice · Astro</sub> | Read papers deliberately and keep notes that are still useful months later. | Astro site with a private workspace (PDF + Triage / Extracts / Notes / Review tabs) and a leak check before every publish. | Public reading log, organised by field and learning path. |

<details>
<summary><b>More projects</b></summary>
<br>

- **[Todo App · FastAPI + Streamlit](https://github.com/NTBao-coder/todo-app-fastapi-streamlit)**: REST API and a first look at agent design.
- **[OpenWeather API Project](https://github.com/NTBao-coder/OpenWeather_API_Project)**: calling an external API efficiently and caching results.
- **[Applied Math & Statistics](https://github.com/NTBao-coder/Applied-Math-and-Statistics---Part-1-)** and **[Data Fitting](https://github.com/NTBao-coder/Data-Fitting)**: matrices, numerical methods and least-squares fitting.
- **[MoisacMusic](https://github.com/NTBao-coder/MoisacMusic)**: TypeScript grid app working with Apple Music and Spotify rate limits.
- **[CSAI Homework](https://github.com/NTBao-coder/CSAI_Homework)**: AI fundamentals exercises and LaTeX reports.

<sub>Forked repositories on my profile are projects I study; original work is everything listed above.</sub>
</details>

## 🛠️ Tech stack

<p align="center"><b>Use regularly</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,sklearn,fastapi,ts,js,html,css,astro,latex,git,github,vscode&perline=12" alt="Python, scikit-learn, FastAPI, TypeScript, JavaScript, HTML, CSS, Astro, LaTeX, Git, GitHub, VS Code"/>
</p>
<p align="center"><b>Learning now</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,docker,githubactions,linux&perline=12" alt="PyTorch, Docker, GitHub Actions, Linux"/>
  <br>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/RAG%20%26%20Agents-6E56CF?style=flat-square&logo=langchain&logoColor=white" alt="RAG and Agents"/>
</p>

## 📊 GitHub stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=NTBao-coder&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github&theme=github_dark&bg_color=0d1117">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=NTBao-coder&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github&theme=default" alt="GitHub stats"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=NTBao-coder&layout=compact&langs_count=8&hide=jupyter%20notebook&size_weight=0.5&count_weight=0.5&hide_border=true&theme=github_dark&bg_color=0d1117">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=NTBao-coder&layout=compact&langs_count=8&hide=jupyter%20notebook&size_weight=0.5&count_weight=0.5&hide_border=true&theme=default" alt="Top languages"/>
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=NTBao-coder&hide_border=true&theme=github-dark-blue&background=0d1117">
  <img src="https://streak-stats.demolab.com?user=NTBao-coder&hide_border=true&theme=default" alt="GitHub streak"/>
</picture>

</div>

## 📐 How I document a project

Every original project README follows the same outline, so you can jump straight to what you care about:

`Problem & Motivation` → `Architecture` → `Methodology` → `Data` → `Experiments` → `Results & Analysis` → `Limitations` → `Usage` → `References`

<div align="center">

<sub>Learning by building, one measured result at a time.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%" alt=""/>

</div>
