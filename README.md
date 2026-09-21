<div align="center">

# Anubhav Kumar

**Full-stack web developer** — I build things that ship, and I make sure they hold up.

Bengaluru, India · CSE @ BMS College of Engineering

[![Live project](https://img.shields.io/badge/live_project-flowshield--app.vercel.app-2fc4a6?style=for-the-badge)](https://flowshield-app.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anubhav-kumar-066b29424/)
[![Email](https://img.shields.io/badge/Email-myacc5010@gmail.com-c14438?style=for-the-badge&logo=gmail&logoColor=white)](mailto:myacc5010@gmail.com)

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</div>

---

<div align="center">

## ✦ right now ✦

</div>

- 🛠️ **Web developer intern @ Internloom** — migrated the product's API off a legacy PHP backend, moved the database and auth to Supabase with row-level security, shipped the redesigned landing page
- 🎓 **CSE @ BMSCE** (2025–2029) · **Technical coordinator** for web development at two college clubs, &lt;CodeIO/&gt; and Protocol
- 🏆 **Winner of two hackathons** — both times a deployed, working product by the deadline
- 💼 **Open to freelance web development and internships** — [email me](mailto:myacc5010@gmail.com)

---

<div align="center">

## ✦ featured builds ✦

<sub>the ones i'd actually show you</sub>

</div>

<br/>

<table>
<tr>
<td width="50%" valign="top">

### 🌊 [flowshield](https://github.com/dingdongkkk/flowshield) · [▶ live](https://flowshield-app.vercel.app)

**Flood simulation and early warning for Bengaluru.**
315 cells of real terrain, the city's real drains,
and a neural network I wrote by hand.

`React 19` `TypeScript` `MapLibre GL` `Web Workers`

- Mass-conserving simulation engine in dependency-free
  TypeScript — a 3h storm solves in ~0.5s, in a Worker
  so the UI never stalls
- **MLP from scratch** — backprop + Adam, no ML library —
  trained on 4,000 of my own engine runs, R² 0.995
  held out, scores ~600 response plans instantly
- 3D map: depth playback, baseline vs response diff,
  warning lead times, buildings exposed
- **21 analytical checks**, water balance to 1e-6 m³

</td>
<td width="50%" valign="top">

### 🌱 [dayzeros](https://github.com/dingdongkkk/dayzeros-app)

**A calm focus app on a pixel-art meadow.**
Pomodoro, tasks and synthesized ambience.

`Next.js 15` `Fastify` `Drizzle` `NeonDB`

- Full-stack monorepo, typed end to end
- Better Auth — sessions, protected routes, cloud sync
- WebAudio ambience synthesizer, no audio files
- Documented like a real product: architecture, API,
  schema and auth guides

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏆 [commit-ed](https://github.com/dingdongkkk/COMMIT-ed)

**Leaderboard for an open-source event.**
Node 20 and *one* dependency.

`node:http` `libSQL / Turso` `node:crypto`

- Hand-rolled router, server-rendered HTML — no framework
- Signed session cookies + CSRF tokens from scratch
- Scores read the PR's difficulty label via GitHub API,
  but nothing counts until an organiser approves it
- Contributor badges drawn client-side on `<canvas>`

</td>
<td width="50%" valign="top">

### 🎓 [internloom](https://github.com/dingdongkkk/internloom)

**Talent-matching backend**, three actors, one API.

`FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic`

- **Concurrency-safe applications** — row locks so a
  1-slot listing can't be over-filled under a race
- JWT auth + role guards, admin approval gates
- Rate-limit & audit-trail middleware
- Routes never hold logic; services never build
  responses — layered on purpose

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🐙 [deep six](https://github.com/dingdongkkk/deep-six) · [▶ play](https://game-anubvkr.vercel.app)

**8-bit escape game.** You're in a flooded research
facility with Specimen 22. Three keycards. One exit.

`JavaScript` `Canvas` `WebAudio`

- **9 puzzle types**, 3 drawn per session and assigned
  to consoles in difficulty order
- Stamina economy — sprint costs ~2x noise radius
- One dash per dive, i-frames for its whole 0.18s
- Chiptune SFX synthesized in-browser

</td>
<td width="50%" valign="top">

### 🛰️ [lagrange-lab](https://github.com/dingdongkkk/lagrange-points)

**Where five points of empty space hold still.**
Finds L1–L5 exactly, decides which can hold a satellite,
and renders a 3m46s film explaining why.

`Python` `NumPy` `Manim` `REBOUND`

- L1–L3 from the collinear quintics — companion-matrix
  eigensolve, polished with Newton to `|∇Ω| < 1e-15`
- Full linear stability analysis + the Routh threshold
- Halo orbits by differential correction, Δv budget
- Cross-validated against an independent N-body
  integrator · **28 physics tests**

</td>
</tr>
</table>

<div align="center">

<br/>

**also worth a look** —
[jansetu](https://github.com/dingdongkkk/CPPGRAMS) civic grievance platform ([live](https://jansetu-grievance.vercel.app)) ·
[nyayasaar](https://github.com/dingdongkkk/NyayaSaar) court judgments in plain English & Hindi ·
[aftersun](https://github.com/dingdongkkk/aftersun) mood & weather aware companion ·
[protocol leaderboard](https://github.com/dingdongkkk/protocol-leaderboard-frontend) ([live](https://protocol-leaderboard-frontend.vercel.app)) ·
[krishiconnect](https://github.com/dingdongkkk/KrishiConnect) farmer-to-consumer marketplace

</div>

---

<div align="center">

## ✦ what i work with ✦

</div>

|  |  |
| --- | --- |
| **Frontend** | React, Next.js (App Router), TypeScript, Tailwind, Vite, MapLibre GL, Canvas, Web Workers |
| **Backend** | Node.js, Fastify, Express, FastAPI, REST API design, JWT & session auth, rate limiting |
| **Data** | PostgreSQL, Supabase, NeonDB, libSQL/Turso, Cloudflare D1, Drizzle, SQLAlchemy, Alembic |
| **Ship it** | Vercel, Cloudflare Workers, Docker, Git, automated verification scripts |
| **Also** | Neural networks from scratch, numerical simulation, geospatial data, LLM APIs |

---

<div align="center">

### Building something and need a developer?

**[myacc5010@gmail.com](mailto:myacc5010@gmail.com)** · **[LinkedIn](https://www.linkedin.com/in/anubhav-kumar-066b29424/)**

</div>
