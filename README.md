<div align="center">
  <img src="./terminal.svg" width="100%" alt="Aditya Gangil — Full-Stack Developer"/>
</div>

```ts
const aditya = {
  role:      "Full-Stack Developer",
  at:        ["Agent Space AI — document intelligence for customs & trade", "MakeDIY — lead developer"],
  shipping:  "deterministic parsers, GraphQL APIs, Postgres pipelines, Next.js dashboards",
  principle: "if it's in production, it has numbers behind it",
  learning:  ["AI engineering", "agentic workflows", "system design"],
};
```

## `$ now` — Agent Space AI

I build the platform that reads import & export customs documents (Bills of Entry, Shipping Bills) and turns them into verified, queryable data — used in production by **2 enterprise healthcare/biotech clients**.

| | What I built | Proof |
|:-:|---|---|
| ![live](https://img.shields.io/badge/-LIVE-2ea043?style=flat-square) | **Deterministic PDF parser** that replaced the OCR + AI extraction step — Python prototype, then ported to TypeScript inside the NestJS backend | Byte-identical output vs. the prototype on 21 real documents · 45-doc load test, 0 failures |
| ![live](https://img.shields.io/badge/-LIVE-2ea043?style=flat-square) | **Production rollout** — Power Automate flow + custom connector through an on-prem gateway, promoted dev → stage → prod for two clients | Running on both clients' prod |
| ![live](https://img.shields.io/badge/-LIVE-2ea043?style=flat-square) | **Automated triage checks** that flag bad extractions before a human reviews them | 6 checks, 21 unit tests |
| ![dev](https://img.shields.io/badge/-DEV-d29922?style=flat-square) | **Data-accuracy audit & fixes** — multi-IGM fix, DB migration, ingest fixes | 410 prod docs · 4,753 duty rows · **0 mismatches** |
| ![dev](https://img.shields.io/badge/-DEV-d29922?style=flat-square) | **Shipping Bill pipeline** into 5 Postgres tables + in-app notifications | 21,078 fields compared API vs CLI · 0 diffs |
| ![merged](https://img.shields.io/badge/-MERGED-8957e5?style=flat-square) | **Custom report builders** — pick fields, preview, export to Excel | Up to 50k rows |
| ![dev](https://img.shields.io/badge/-DEV-d29922?style=flat-square) | **Performance / SLA page** — clearance time in working days with a state holiday calendar | 80.4% cleared within 3 working days |

## `$ ls ~/projects`

| Project | Stack | Highlights |
|---|---|---|
| **[MakeDIY](https://makediy.in)** · lead dev | Next.js · Express · MongoDB · three.js | E-commerce + PCB & 3D-printing quote wizards with an in-browser 3D model viewer and live weight / print-time estimates · Paytm payments · JWT auth with refresh-token rotation · 17-section admin panel |
| **[Abbie Education](https://training.abbieeducation.world)** · LMS | Next.js · Node · Razorpay | Course → Chapter → Lesson structure, purchase flow, live with enrolled students |
| **[Diwan Foundation](https://allgujaratmuslimfakirdiwansamaj.org)** · NGO | Node · RBAC | Multi-role access, QR donation flow, auto-generated PDF certificates |

## `$ cat stack.json`

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,py,cpp&perline=12" alt="Languages"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,threejs,nodejs,nestjs,express,graphql&perline=12" alt="Frontend and backend"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,vercel,nginx,git,github,figma&perline=12" alt="Data and tooling"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black" alt="Drizzle ORM"/>
  <img src="https://img.shields.io/badge/Apollo_GraphQL-311C87?style=flat-square&logo=apollographql&logoColor=white" alt="Apollo GraphQL"/>
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white" alt="TanStack Query"/>
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" alt="Zod"/>
  <img src="https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white" alt="Power Automate"/>
  <img src="https://img.shields.io/badge/pdf.js-EC1C24?style=flat-square&logo=mozilla&logoColor=white" alt="pdf.js"/>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code"/>
</p>

## `$ git log --stats`

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=developeradi12&show_icons=true&hide_border=true&theme=transparent&include_all_commits=true" height="165" alt="GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=developeradi12&layout=compact&langs_count=8&hide_border=true&theme=transparent" height="165" alt="Top languages"/>
  <br/>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=developeradi12&theme=github-compact&hide_border=true&area=true" width="100%" alt="Contribution graph"/>
</div>

---

<div align="center">
  <a href="https://www.linkedin.com/in/aditya-gangil-5b8b98244/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:adityagangil182@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://makediy.in"><img src="https://img.shields.io/badge/makediy.in-111111?style=flat-square&logo=googlechrome&logoColor=white" alt="MakeDIY"/></a>
</div>
