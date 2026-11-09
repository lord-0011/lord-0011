<!-- Profile README for github.com/lord-0011 -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&section=header&height=210&color=0:0d1117,55:10263f,100:1f4e79&text=Priyanshu%20Kumar&fontColor=e6edf3&fontSize=52&fontAlignY=36&desc=Full-stack%20developer%20%C2%B7%20B.Tech%20CSE%20%2726&descSize=16&descAlignY=56&animation=fadeIn" alt="Priyanshu Kumar — full-stack developer, B.Tech CSE '26" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/lord-0011">
    <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=500&size=19&duration=2800&pause=1400&color=58A6FF&center=true&vCenter=true&width=640&height=40&lines=Full-stack+developer;MERN+%C2%B7+Next.js+%C2%B7+React+Native;Fixing+bugs+in+React+and+Next.js+libraries;Failing+test+first%2C+then+the+fix" alt="Typing animation: Full-stack developer · MERN, Next.js, React Native · Fixing bugs in React and Next.js libraries · Failing test first, then the fix" />
  </a>
</p>

<p align="center">
  I build full-stack web apps, and lately I spend a lot of time in other people's codebases —<br />
  finding bugs in the React and Next.js libraries I use, reproducing them with a failing test, and sending the fix upstream.
</p>

<p align="center"><img src="./assets/divider.svg" alt="" width="100%" /></p>

## About

I'm a B.Tech CSE student who builds full-stack web apps, mostly on the MERN stack, with Next.js and React Native picked up along the way. My recent work has moved toward backend-heavy systems — job queues, OCR pipelines, real-time messaging — and toward software that explains itself: tested edge cases, clear failure messages, and documented assumptions.

The habit I'm proudest of is how I approach bugs, in my own code or anyone else's: reproduce it, pin it down with a failing test, then fix the cause rather than the symptom. That's the same loop I use for my open-source pull requests.

**Right now**

- **Contributing** — bug fixes to React and Next.js ecosystem libraries (Mantine, React Flow, Zag, Fumadocs, Radix, Base UI, and more)
- **Building** — CertiScholar, an OCR-based document-assessment and scholarship-recommendation system
- **Learning** — system design, backend performance with Redis, and data structures & algorithms

<p align="center"><img src="./assets/divider.svg" alt="" width="100%" /></p>

## Tech stack

**Languages**<br />
<img src="https://skillicons.dev/icons?i=js,ts,python,cpp,html,css&theme=dark" alt="JavaScript, TypeScript, Python, C++, HTML, CSS" height="44" />

**Frontend & mobile** <sub>· React, Next.js, Vite, Tailwind CSS, Material UI — plus React Native for mobile</sub><br />
<img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind,materialui&theme=dark" alt="React, Next.js, Vite, Tailwind CSS, Material UI" height="44" />

**Backend** <sub>· Node.js, Express, FastAPI — Socket.IO for real-time</sub><br />
<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi&theme=dark" alt="Node.js, Express, FastAPI" height="44" />

**Data**<br />
<img src="https://skillicons.dev/icons?i=mongodb,redis,postgres&theme=dark" alt="MongoDB, Redis, PostgreSQL" height="44" />

**Tools & platforms**<br />
<img src="https://skillicons.dev/icons?i=git,github,githubactions,docker,vercel&theme=dark" alt="Git, GitHub, GitHub Actions, Docker, Vercel" height="44" />

<p align="center"><img src="./assets/divider.svg" alt="" width="100%" /></p>

## Featured projects

### [CertiScholar](https://github.com/lord-0011/Certi_Scholar)

OCR-based document extraction, consistency checks, and explainable scholarship recommendations. Students upload marksheets and certificates; a Python OCR service extracts fields, verifiers review low-confidence values against the highlighted region of the image, and officers see every eligibility condition with the source of each fact. It deliberately never claims a document is genuine unless the issuing authority has confirmed it. Runs as a full Docker Compose stack with background workers and virus scanning. *Team project.*

`TypeScript` `Next.js` `Express` `BullMQ` `MongoDB` `Redis` `FastAPI` `Tesseract` `Docker`

### [AlumniVerse](https://github.com/lord-0011/Alumni-Verse) &nbsp;·&nbsp; [Live demo](https://alumni-verse-frontend.vercel.app)

An alumni networking platform connecting students with graduates: separate student and alumni dashboards, a social feed, real-time chat between connections, an alumni directory with filters, mentorship requests, a job board, events with RSVPs, and a startup showcase. Sign-in with JWT or Google OAuth.

`React` `Vite` `Material UI` `Tailwind CSS` `Node.js` `Express` `MongoDB` `Socket.IO` `Passport` `Cloudinary`

### [SIH 2026 — PAIMANA early warning](https://github.com/lord-0011/SIH-2026)

A predictive layer for India's infrastructure-project monitoring data, built for Smart India Hackathon 2026: forecasting cost and schedule overruns, scoring project risk from 0 to 100, and flagging projects that are deteriorating. Data versioned with DVC, CI from day one. *Team project.*

`Python` `FastAPI` `React` `PostgreSQL` `Docker` `DVC` `pytest`

### [Price Alert Tool](https://github.com/lord-0011/PriceToolAlert)

A dependency-free command-line tool that fires price-level and moving-average-crossover alerts from a price history. Every ambiguity in the spec is written down as an explicit assumption, bad input fails with the exact file and line number, and the behaviour is pinned by 55 unit tests with hand-computed values.

`Python` `unittest` `CLI`

<sub>Also: [Wanderlust](https://github.com/lord-0011/Wanderlust) (Node · Express · EJS), [UniFinder](https://github.com/lord-0011/UniFinder) (React), and React Native apps — [Mini Spotify](https://github.com/lord-0011/MiniSpotify), [Currency Converter](https://github.com/lord-0011/CurrencyConverter), [Tic-Tac-Toe](https://github.com/lord-0011/TicTacToeApp), [Password Generator](https://github.com/lord-0011/Password-Generator).</sub>

<p align="center"><img src="./assets/divider.svg" alt="" width="100%" /></p>

## Open source

I contribute bug fixes to libraries in the React and Next.js ecosystem — mostly accessibility, scrolling, and state edge cases that I can reproduce with a failing test.

<p>
  <a href="https://github.com/search?q=author%3Alord-0011+is%3Apr+is%3Amerged+-user%3Alord-0011+-user%3ASohamactive+-user%3ANavjot-Singh265+-user%3Armsingh1479-cmd&type=pullrequests"><img src="https://img.shields.io/github/issues-search?query=author%3Alord-0011%20is%3Apr%20is%3Amerged%20-user%3Alord-0011%20-user%3ASohamactive%20-user%3ANavjot-Singh265%20-user%3Armsingh1479-cmd&label=merged%20PRs&color=1f6feb&style=flat-square" alt="Merged pull requests to open-source projects" /></a>
  <a href="https://github.com/search?q=author%3Alord-0011+is%3Apr+is%3Aopen+-user%3Alord-0011+-user%3Armsingh1479-cmd&type=pullrequests"><img src="https://img.shields.io/github/issues-search?query=author%3Alord-0011%20is%3Apr%20is%3Aopen%20-user%3Alord-0011%20-user%3Armsingh1479-cmd&label=in%20review&color=30363d&style=flat-square" alt="Open pull requests currently in review" /></a>
</p>

**Merged**

| Project | Fix | Stack |
| :-- | :-- | :-- |
| [Mantine](https://github.com/mantinedev/mantine) | [`NumberInput` no longer overrides the `inputMode` prop you pass it](https://github.com/mantinedev/mantine/pull/9371) | React · TypeScript |
| [React Flow](https://github.com/xyflow/xyflow) | [Ignore `ResizeObserver` entries without a `contentRect` in the pane extent cache](https://github.com/xyflow/xyflow/pull/6108) | TypeScript |
| [Zag](https://github.com/chakra-ui/zag) | [Combobox only scrolls its own list when bringing the highlighted item into view](https://github.com/chakra-ui/zag/pull/3574) | TypeScript · state machines |
| [Fumadocs](https://github.com/fuma-nama/fumadocs) | [Links to tabs and accordions with non-English ids now open them](https://github.com/fuma-nama/fumadocs/pull/3803) | Next.js · React |

<details>
<summary><b>In review</b> (11)</summary>
<br />

| Project | Pull request |
| :-- | :-- |
| Zag | [#3626](https://github.com/chakra-ui/zag/pull/3626) — keep the highlighted item in view inside a nested scroll area |
| Radix UI | [#4267](https://github.com/radix-ui/primitives/pull/4267) — controlled Tabs no longer fire `onValueChange` twice per click |
| Base UI | [#6201](https://github.com/mui/base-ui/pull/6201) — toast stack collapses when the pointer leaves after closing the hovered toast |
| React Router | [#15721](https://github.com/remix-run/react-router/pull/15721) — no more nonce hydration warning from `<Links>` |
| Fumadocs | [#3806](https://github.com/fuma-nama/fumadocs/pull/3806) — search close button's accessible name includes its visible text |
| Nextra | [#5062](https://github.com/shuding/nextra/pull/5062) — respect `prefers-reduced-motion` when the TOC scrolls |
| Nextra | [#5063](https://github.com/shuding/nextra/pull/5063) — navbar logo link takes its name from the visible logo text |
| Nextra | [#5064](https://github.com/shuding/nextra/pull/5064) — lite theme switch includes the current theme in its name |
| next-intl | [#2448](https://github.com/amannn/next-intl/pull/2448) — support built-in date and time styles in precompiled messages |
| next-intl | [#2457](https://github.com/amannn/next-intl/pull/2457) — one invalid `accept-language` entry no longer throws away the rest |
| Kan | [#681](https://github.com/kanbn/kan/pull/681) — avatar crop dialog fits on a phone screen |

</details>

<sub>[All my pull requests →](https://github.com/search?q=author%3Alord-0011+is%3Apr+-user%3Alord-0011&type=pullrequests&s=created&o=desc)</sub>

**What keeps me contributing**

- Fixing real problems in tools that thousands of developers depend on, including the ones I use myself
- Working with maintainers and developers around the world through code review
- Learning how large, well-run codebases are structured, tested, and released
- Leaving codebases a little more accessible and predictable than I found them

<p align="center"><img src="./assets/divider.svg" alt="" width="100%" /></p>

## GitHub activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=lord-0011&theme=github_dark" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=lord-0011&theme=github" alt="Contribution graph for lord-0011 over the last year" width="100%" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=lord-0011&theme=github_dark" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=lord-0011&theme=github" alt="GitHub stats: stars, commits, pull requests, issues, and contributed repositories" width="49%" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=lord-0011&theme=github_dark" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=lord-0011&theme=github" alt="Top languages by commits" width="49%" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=lord-0011&hide_border=true&background=0D1117&stroke=30363D&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF&currStreakNum=E6EDF3&sideNums=E6EDF3&sideLabels=8B949E&dates=8B949E" />
    <img src="https://streak-stats.demolab.com/?user=lord-0011&hide_border=true&ring=1F6FEB&fire=1F6FEB&currStreakLabel=1F6FEB" alt="GitHub contribution streak: total contributions, current streak, and longest streak" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lord-0011/lord-0011/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/lord-0011/lord-0011/output/github-snake.svg" alt="Animated snake eating the contribution graph" width="100%" />
  </picture>
</p>

<p align="center"><img src="./assets/divider.svg" alt="" width="100%" /></p>

## Connect

<p>
  <a href="https://github.com/lord-0011"><img src="https://img.shields.io/badge/GitHub-lord--0011-0d1117?style=flat-square&logo=github&logoColor=e6edf3" alt="GitHub: lord-0011" /></a>
  <!-- LINKEDIN: <a href="https://www.linkedin.com/in/YOUR-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a> -->
  <!-- EMAIL: <a href="mailto:YOUR-EMAIL"><img src="https://img.shields.io/badge/Email-Get%20in%20touch-1f4e79?style=flat-square&logo=maildotru&logoColor=white" alt="Email" /></a> -->
</p>

Happy to talk about full-stack roles, open-source collaboration, or a bug you'd like a second pair of eyes on.

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=lord-0011&label=profile%20views&color=1f4e79&style=flat-square" alt="Profile view counter" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=110&color=0:1f4e79,45:10263f,100:0d1117" alt="" width="100%" />
</p>
