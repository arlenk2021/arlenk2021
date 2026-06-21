<!-- ============================================================= -->
<!--  ARLEN FREDERICK KUMAR · PROFILE README                       -->
<!--  Aesthetic: terminal / build-log · slate #0F172A + run-green  -->
<!-- ============================================================= -->

<!-- ===================== HEADER BANNER ===================== -->
<a href="https://arlenkumar.com">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,40:0f172a,100:16a34a&height=210&section=header&text=Arlen%20Frederick%20Kumar&fontSize=44&fontColor=f8fafc&fontAlignY=36&desc=curious%20about%20how%20AI%20systems%20retrieve%2C%20cite%2C%20and%20decide&descAlignY=58&descSize=17" alt="Arlen Frederick Kumar — curious about how AI systems retrieve, cite, and decide" />
</a>

<!-- ===================== TYPING SUBTITLE ===================== -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=22C55E&center=true&vCenter=true&width=860&lines=I+build+tools+that+help+AI+retrieve+and+cite+better;Former+CTO+%40+Wrodium+%C2%B7+Berkeley+SkyDeck+founder;I+read+the+IR+patents+behind+Perplexity+%26+ChatGPT;Golden+evals+%2B+benchmarks+that+run+on+cloud+compute;Still+early%2C+still+learning+in+public)](https://arlenkumar.com)

</div>

<!-- ===================== BADGE ROW ===================== -->
<div align="center">

[![Website](https://img.shields.io/badge/arlenkumar.com-0f172a?style=for-the-badge&logo=vercel&logoColor=white)](https://arlenkumar.com)
[![SkyDeck](https://img.shields.io/badge/Berkeley_SkyDeck-Founder-FDB515?style=for-the-badge&logo=googlescholar&logoColor=003262)](https://skydeck.berkeley.edu)
[![Primitive Bench](https://img.shields.io/badge/Primitive_Bench-111827?style=for-the-badge&logo=target&logoColor=22c55e)](https://www.primitivebench.com)
[![GEO-16](https://img.shields.io/badge/arXiv-GEO--16-b31b1b?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.10762)
<br/>
[![Wrodium](https://img.shields.io/badge/Wrodium-former_CTO-16a34a?style=for-the-badge&logo=googlechrome&logoColor=white)](https://wrodium.com)
[![Vela](https://img.shields.io/badge/Vela-YC_W26-1e293b?style=for-the-badge&logo=ycombinator&logoColor=f97316)](https://tryvela.ai)
[![Relixir](https://img.shields.io/badge/Relixir-YC_X25-1e293b?style=for-the-badge&logo=ycombinator&logoColor=f97316)](https://www.relixir.ai/rex)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arlen-frederick-kumar-1198592b8)

<img src="https://komarev.com/ghpvc/?username=arlenk2021&style=for-the-badge&color=16a34a&label=PROFILE+VIEWS" alt="profile views" />

</div>

---

<!-- ===================== WHOAMI TERMINAL ===================== -->
```bash
arlen@berkeley:~$ whoami

  Hi, I'm Arlen. I build small tools that help AI systems retrieve,
  cite, and act from better information. Most of them start the same
  way: I get curious about how something works and can't stop until
  I've rebuilt it myself and measured whether it's any good.

  former CTO   Wrodium — knowledge freshness for AI search (role now wrapped)
  founder      Berkeley SkyDeck · 2x founder — shipped hardware, exited before 21
  obsessed     information retrieval — I read the patents behind Perplexity
               & ChatGPT to learn how answer engines actually decide what to cite
  building     golden evals + benchmarks that run on cloud compute
  learning     in public, still early, still figuring it out

arlen@berkeley:~$ _
```

---

<!-- ===================== THE ARC ===================== -->
## The arc — how I got here

> Less a résumé, more a habit: **get curious → read the source → rebuild it → measure if it's real.**

```mermaid
timeline
    title  curiosity → retrieval → evals → trust
    section Before 21
        Hardware founder : Built and shipped VR flight-sim hardware : ~10x below incumbent pricing : Exited before turning 21
    section UC Berkeley
        Hearst Lab : NLP / IR research under Prof. Marti Hearst
        Reading the patents : Studied the IR patents behind Perplexity and ChatGPT : to learn how answer engines cite
    section Founding-engineer
        Relixir · YC X25 : autonomous GEO and blindspot loops
        Vela · YC W26 : proactive scheduling intelligence
    section Wrodium
        CTO · Berkeley SkyDeck : Led 7 engineers on knowledge freshness : (role now complete)
    section Now
        Primitive Bench : Golden evals on cloud compute : vendor-neutral and slice-specific
        Still learning : in public, one question at a time
```

<details>
<summary><b>Prefer it as a git history? (click)</b></summary>

```mermaid
gitGraph
    commit id: "hardware-exit"
    commit id: "berkeley · hearst-lab"
    branch retrieval
    commit id: "read the IR patents"
    commit id: "GEO-16 · arXiv"
    checkout main
    merge retrieval
    branch founding-eng
    commit id: "Relixir · YC X25"
    commit id: "Vela · YC W26"
    checkout main
    merge founding-eng
    branch wrodium
    commit id: "CTO · 7 engineers"
    commit id: "knowledge-freshness"
    checkout main
    merge wrodium
    commit id: "Primitive Bench" tag: "now"
```

</details>

---

<!-- ===================== INFORMATION RETRIEVAL ===================== -->
## How answer engines decide — so I read the patents

I kept seeing people optimize for ChatGPT and Perplexity by guessing. I wanted to understand the mechanism instead of the folklore, so I went to the primary source: the **information-retrieval patents** behind these products — how Perplexity ranks and cites, how OpenAI's retrieval patterns work, how classic IR weighs authority against freshness.

Reading them changed how I build. A few patterns I keep coming back to:

```txt
• how a system decides a source is "authoritative enough" to cite
• how recency and freshness get weighed against authority
• how query understanding reshapes what counts as a relevant chunk
• where retrieval quietly fails — and nobody notices the silent miss
```

Then I try to rebuild and measure those patterns. That curiosity is where **GEO-16** (a rubric for what makes a page citation-worthy) and **Primitive Bench** (benchmarks for the retrieval tools agents actually use) both came from.

**📍 [GEO-16 · arXiv:2509.10762](https://arxiv.org/abs/2509.10762)**

---

<!-- ===================== WRODIUM ===================== -->
## Wrodium — what I led as CTO

<table>
<tr>
<td width="56%" valign="top">

As **CTO, I led a team of 7 engineers** at Wrodium (Berkeley SkyDeck) building **knowledge-freshness infrastructure** — tools that show a company where AI answer engines describe it **wrong, stale, or not at all**, and help it fix the gaps before they cost real business. I've since wrapped up that role, but it's where a lot of my thinking about retrieval and freshness took shape.

The simple idea behind it:

```txt
The old web competed for blue links. The new web is read by answer
engines first. If you're invisible or out of date inside them, you
can lose the decision long before anyone visits your site.
```

What the team built:

```diff
+ Blindspot detection   where AI engines get a company wrong, stale, or absent
+ Visibility telemetry  citations, share-of-voice, competitor presence
+ Knowledge freshness   catching content drift and decaying authority
+ Machine readability   schema and structure that make pages easy to cite
```

</td>
<td width="44%" valign="top">

<img src="assets/wrodium-team-skydeck.png" alt="Arlen with the Wrodium team of 7 engineers at UC Berkeley SkyDeck" width="100%" />

<div align="center"><sub><b>Led the Wrodium team @ Berkeley SkyDeck</b><br/>7 engineers · knowledge-freshness infrastructure</sub></div>

</td>
</tr>
</table>

**📍 [wrodium.com](https://wrodium.com) · [SCET feature](https://scet.berkeley.edu/meet-leanid-palkhouski-the-entrepreneur-solving-knowledge-decay/)**

---

<!-- ===================== PRIMITIVE BENCH ===================== -->
## Primitive Bench — what I'm working on now

A small, vendor-neutral way to answer a practical question: *for this specific job, which retrieval or extraction tool actually works?* You give it a vertical, a workflow, and a data need; it builds a hand-verified golden set from the open web, runs each tool through the same harness **on cloud compute**, and reports what holds up.

```mermaid
flowchart TD
    A[A real question from a team]:::dark --> B[Define the narrow slice]
    B --> C[Collect web evidence]
    C --> D[Check provenance + freshness]
    D --> E[Build golden eval items]
    E --> F[Human verification]:::purple
    F --> G[Run tools on cloud compute]:::amber
    G --> H[Score the slice]:::blue
    H --> I[Plain recommendation]:::green
    classDef dark fill:#0f172a,color:#fff,stroke:#22c55e
    classDef purple fill:#6d28d9,color:#fff,stroke:#a78bfa
    classDef amber fill:#b45309,color:#fff,stroke:#fbbf24
    classDef blue fill:#1d4ed8,color:#fff,stroke:#60a5fa
    classDef green fill:#15803d,color:#fff,stroke:#4ade80
```

The thing I keep relearning: **there's no single winner.** A tool that's great for legal citations can be wrong for e-commerce tables. So I score narrow slices, not categories — and I count **cost per *correct* answer**, since a cheap API that's wrong is the expensive one once you add up the cloud-compute bill behind it.

```bash
bench run --primitive web-search --slice fintech.freshness-sensitive
bench run --primitive extraction  --slice ecommerce.table-fidelity
bench decision-card --vertical fintech --workflow sales-intelligence
```

**📍 [primitivebench.com](https://www.primitivebench.com) · [github.com/primitive-bench/benchpublic](https://github.com/primitive-bench/benchpublic)**

---

<!-- ===================== OTHER WORK ===================== -->
## A few other things I've built

<table>
<tr>
<td width="50%" valign="top">

### Vela — proactive scheduling `YC W26`
Founding-engineer work on moving scheduling from **reactive inbox → proactive intelligence**: notice an overbooked day, route it to the agent pipeline, and *refuse to act* when live calendar state is missing instead of guessing.
**📍 [tryvela.ai](https://tryvela.ai)**

</td>
<td width="50%" valign="top">

### Relixir — autonomous GEO `YC X25`
Founding-engineer exposure to blindspot automation: probe answer engines → find missing mentions → map competitor citations → close the gap → re-test. Taught me a product isn't a dashboard; it's the loop between measuring and acting.
**📍 [relixir.ai/rex](https://www.relixir.ai/rex)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### llms.txt Generator
A free tool that crawls a site and writes its `llms.txt` — a clean map of what an AI engine should understand and cite. The lowest-effort, highest-leverage thing most sites are missing.
**📍 [arlenkumar.com/projects](https://arlenkumar.com/projects)**

</td>
<td width="50%" valign="top">

### Smaller experiments
**`Benchmark Graveyard`** — a museum of dead AI benchmarks and why they collapsed · **`regress.fish`** — a NOAA fishing forecast that publishes its own error with a Brier scoreboard, because a model that admits when it's wrong is easier to trust.

</td>
</tr>
</table>

---

<!-- ===================== STACK & FOCUS ===================== -->
## What I work with

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
<br/>
![Postgres](https://img.shields.io/badge/Postgres_+_pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/Cloud_Compute-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Claude / MCP](https://img.shields.io/badge/Claude_/_MCP-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

</div>

| Area | What it means in practice |
|---|---|
| **Information retrieval** | Reading the patents · hybrid dense+sparse · BM25 + vector · reranking · citation behavior · freshness vs. authority |
| **Evaluation** | Hand-verified golden sets · per-slice scoring · cost per *correct* answer · catching silent failures |
| **Cloud compute** | Running eval harnesses at scale · distributed benchmark runs · treating cost-per-correct as a real compute budget |
| **Agent tooling** | Claude Skills · MCP servers · `llms.txt` · JSON-LD · guardrails and refusal paths when state is missing |

---

<!-- ===================== GITHUB STATS ===================== -->
## A bit of GitHub

<div align="center">

<img width="48%" src="https://github-readme-stats.vercel.app/api?username=arlenk2021&show_icons=true&hide_border=true&title_color=22c55e&icon_color=16a34a&text_color=c9d1d9&bg_color=0d1117" alt="Arlen's GitHub stats" />
<img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=arlenk2021&hide_border=true&background=0d1117&ring=22c55e&fire=16a34a&currStreakLabel=22c55e&sideLabels=c9d1d9&dates=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9" alt="GitHub streak" />

<img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=arlenk2021&layout=compact&hide_border=true&title_color=22c55e&text_color=c9d1d9&bg_color=0d1117" alt="Top Languages" />
<img width="48%" src="https://github-profile-trophy.vercel.app/?username=arlenk2021&theme=matrix&no-frame=true&column=4&row=2&margin-w=8&margin-h=8" alt="Trophies" />

</div>

---

<!-- ===================== HOW I THINK ===================== -->
## A few things I believe

> **1.** Research is only useful if it changes what gets built. *A paper should become a rubric, then a tool, then an outcome.*
>
> **2.** A benchmark should be honest enough to disappoint you. *If it always confirms the obvious, it's marketing.*
>
> **3.** "Best" is usually the wrong question. *Better: best for which slice, at what cost, with what failure mode?*
>
> **4.** Autonomy needs guardrails. *An agent should be willing to refuse when it isn't sure.*
>
> **5.** I'd rather be useful than impressive, and I'm still learning either way.

---

<!-- ===================== FOOTER ===================== -->
<div align="center">

### Get curious. Read the source. Rebuild it. Measure if it's real.

[![Website](https://img.shields.io/badge/arlenkumar.com-0f172a?style=for-the-badge&logo=vercel&logoColor=white)](https://arlenkumar.com)
[![Email](https://img.shields.io/badge/Say_hi-16a34a?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arlen1788@berkeley.edu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arlen-frederick-kumar-1198592b8)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:16a34a,60:0f172a,100:020617&height=120&section=footer" />

</div>
