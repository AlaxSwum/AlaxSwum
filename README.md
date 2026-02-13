<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:161b22,70:1a1a2e,100:0d1117&height=200&section=header&text=Swum%20Pyae%20Sone&fontSize=38&fontColor=c9d1d9&fontAlignY=30&desc=AI%20%26%20Software%20Engineer%20%7C%20Docker-First%20Infrastructure%20%7C%20UK&descSize=14&descAlignY=52&descColor=58a6ff&animation=fadeIn" width="100%" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=14&duration=3000&pause=1500&color=58A6FF&center=true&vCenter=true&repeat=true&width=700&lines=Building+production-ready+systems+across+applied+AI+and+scalable+infrastructure;Docker-first.+Tested.+Deployed.+Automated.+Every+single+project.;Systems+thinker.+Long-term+maintainability+over+short-term+hacks." />

<br/>

<a href="mailto:swumpyaealax@gmail.com"><img src="https://img.shields.io/badge/swumpyaealax@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=c9d1d9" /></a>
&nbsp;
<a href="https://github.com/AlaxSwum"><img src="https://img.shields.io/badge/github-AlaxSwum-0d1117?style=for-the-badge&logo=github&logoColor=c9d1d9" /></a>

</div>

<br/>

---

<br/>

<table>
<tr>
<td width="58%" valign="top">

### About

AI and software engineer focused on building practical, production-oriented systems across AI, automation, and scalable software infrastructure.

My work sits at the intersection of **applied AI**, **system design**, and **operational execution**. I build tools and workflows that reduce complexity, improve decision-making, and create measurable leverage — whether through backend systems, intelligent agents, or full-stack products.

I think in systems. I optimise for long-term maintainability over short-term hacks. I value clarity, structure, and repeatable processes. My background spans software engineering, AI implementation, and leading technical and education-related initiatives.

I use GitHub as a public lab for experiments, production-ready systems, and long-term technical projects.

</td>
<td width="42%" valign="top">

### Current Focus

```yaml
applied_ai:
  - Intelligent agent systems
  - AI-assisted development
  - Automation pipelines

engineering:
  - Docker-first infrastructure
  - Scalable backend architecture
  - CI/CD deployment workflows

products:
  - Independent digital tools
  - Revenue-generating systems
  - Open source contributions
```

</td>
</tr>
</table>

<br/>

---

<br/>

<div align="center">

### Docker-First Development

*Every project starts with containers. No exceptions.*

</div>

<br/>

```
PROJECT STRUCTURE                              WHAT RUNS IN DOCKER
                                              
my-project/                                    API Server ........... Node/Python container
  docker-compose.yml         base services     Dev Database ......... Postgres (named volume)
  docker-compose.dev.yml     dev overrides     Test Database ........ Postgres (tmpfs / RAM)
  docker-compose.test.yml    test overrides    Cache ................ Redis container
  Dockerfile                 production        Workers .............. Background job containers
  Dockerfile.dev             dev + hot reload  
  Makefile                   all commands      WHAT DOES NOT RUN IN DOCKER
                                              
COMMANDS                                       Production DB ........ Supabase (managed)
                                               CI/CD ................ GitHub Actions
  make dev         start everything            Hosting .............. Vercel / Railway
  make down        stop everything            
  make test        throwaway test DB          RULES
  make seed        fill with fake data        
  make migrate     apply schema changes        Never install a database on the host machine.
  make db-reset    wipe and rebuild            Pin every image version. No :latest.
  make logs        tail all containers         Dev, test, and production use the same engine.
  make nuke        destroy everything          Postgres version matches across all environments.
                                               One Makefile runs every command.
```

<br/>

---

<br/>

<div align="center">

### Tech Stack

<br/>

<table>
<tr>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=docker" width="42" height="42" alt="Docker" />
<br/><sub><b>Docker</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=python" width="42" height="42" alt="Python" />
<br/><sub><b>Python</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=tensorflow" width="42" height="42" alt="TensorFlow" />
<br/><sub><b>TensorFlow</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=pytorch" width="42" height="42" alt="PyTorch" />
<br/><sub><b>PyTorch</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=ts" width="42" height="42" alt="TypeScript" />
<br/><sub><b>TypeScript</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=nextjs" width="42" height="42" alt="Next.js" />
<br/><sub><b>Next.js</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=react" width="42" height="42" alt="React" />
<br/><sub><b>React</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=nodejs" width="42" height="42" alt="Node.js" />
<br/><sub><b>Node.js</b></sub>
</td>
</tr>
<tr>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=postgres" width="42" height="42" alt="PostgreSQL" />
<br/><sub><b>PostgreSQL</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=redis" width="42" height="42" alt="Redis" />
<br/><sub><b>Redis</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=supabase" width="42" height="42" alt="Supabase" />
<br/><sub><b>Supabase</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=prisma" width="42" height="42" alt="Prisma" />
<br/><sub><b>Prisma</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=tailwind" width="42" height="42" alt="Tailwind" />
<br/><sub><b>Tailwind</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=git" width="42" height="42" alt="Git" />
<br/><sub><b>Git</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=githubactions" width="42" height="42" alt="GitHub Actions" />
<br/><sub><b>CI/CD</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=linux" width="42" height="42" alt="Linux" />
<br/><sub><b>Linux</b></sub>
</td>
</tr>
<tr>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=nginx" width="42" height="42" alt="Nginx" />
<br/><sub><b>Nginx</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=aws" width="42" height="42" alt="AWS" />
<br/><sub><b>AWS</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=vercel" width="42" height="42" alt="Vercel" />
<br/><sub><b>Vercel</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=vscode" width="42" height="42" alt="VS Code" />
<br/><sub><b>VS Code</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=bash" width="42" height="42" alt="Bash" />
<br/><sub><b>Bash</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=html" width="42" height="42" alt="HTML" />
<br/><sub><b>HTML</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=css" width="42" height="42" alt="CSS" />
<br/><sub><b>CSS</b></sub>
</td>
<td align="center" width="80px">
<img src="https://skillicons.dev/icons?i=figma" width="42" height="42" alt="Figma" />
<br/><sub><b>Figma</b></sub>
</td>
</tr>
</table>

</div>

<br/>

---

<br/>

<div align="center">

### Activity

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=AlaxSwum&show_icons=true&hide_border=true&count_private=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&ring_color=58a6ff" />
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=AlaxSwum&show_icons=true&hide_border=true&count_private=true" />
</picture>
&nbsp;&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=AlaxSwum&layout=compact&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlaxSwum&layout=compact&hide_border=true" />
</picture>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com?user=AlaxSwum&theme=github-dark-blue&hide_border=true&background=0D1117&ring=58a6ff&fire=58a6ff&currStreakLabel=c9d1d9&sideLabels=c9d1d9&dates=8b949e" />
  <img width="53%" src="https://github-readme-streak-stats.herokuapp.com?user=AlaxSwum&hide_border=true" />
</picture>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=AlaxSwum&hide_border=true&bg_color=0d1117&color=c9d1d9&line=58a6ff&point=c9d1d9&area=true&area_color=161b22" />
  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=AlaxSwum&hide_border=true&area=true" />
</picture>

</div>

<br/>

---

<br/>

<div align="center">

### Git Workflow

</div>

<br/>

```
BRANCHING STRATEGY                     DEPLOYMENT PIPELINE

  main                                   Laptop (Docker)
    |                                      |
    +-- feature/auth-system                make test (throwaway DB)
    |     |                                  |
    |     +-- PR reviewed                  GitHub Actions (CI)
    |     +-- Tests pass                     |
    |     +-- Merged to main               Staging (Supabase staging)
    |                                        |
    +-- fix/signup-validation              Production (Supabase production)
    |     |
    |     +-- Hotfix branch
    |     +-- Merged same day            RULES
    |
    +-- refactor/api-routes                One branch per task.
          |                                Pull latest main before branching.
          +-- Ongoing                      Tests pass before any merge.
                                           Migrations through CI/CD only.
                                           Never commit directly to main.
```

<br/>

---

<br/>

<div align="center">

### Principles

</div>

<br/>

<table>
<tr>
<td width="50%" valign="top">

**System Design**

Clear architecture over clever shortcuts. Every system should be readable by someone who did not build it. Structure and intent should be obvious from the file tree alone.

</td>
<td width="50%" valign="top">

**Maintainability**

Code that works in six months matters more than code that is impressive today. Long-term durability over short-term hacks. Resist the urge to be clever.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Operational Efficiency**

Automate the repeatable. Document the complex. Reduce decision fatigue at every layer. If you do it twice, script it. If you do it three times, make it a pipeline.

</td>
<td width="50%" valign="top">

**Intelligent Tooling**

AI should make workflows faster, not more complicated. Every tool is measured by whether it reduces complexity. If it adds friction, it gets replaced.

</td>
</tr>
</table>

<br/>

---

<br/>

<div align="center">

**Open to collaborating on AI systems, automation tools, and production-grade engineering.**

<br/>

<a href="mailto:swumpyaealax@gmail.com"><img src="https://img.shields.io/badge/Get%20in%20touch-swumpyaealax@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=c9d1d9" /></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:161b22,70:1a1a2e,100:0d1117&height=100&section=footer" width="100%" />

</div>
