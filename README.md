# Nazar Mykhailyshchuk

Computer Science student at the Ukrainian Catholic University (Lviv). I build full-stack web apps — usually Next.js or Spring Boot on the front of a real database, often with an LLM somewhere in the pipeline. Most of what’s here started as a course project or a hackathon and ended up deployed.

I also mentor first-year students on algorithms and data-structure projects.

-----

## Things I’ve shipped

**[Silpo Party](https://www.silpoparty.app)** — AI that turns a group chat into a ready-to-buy basket from the live catalog of Silpo, a Ukrainian supermarket chain (hackathon, team of 2).
Next.js · TypeScript · Supabase · AI SDK · MCP
Food restrictions and budget respected, cost split fairly, one-click handoff to the host’s real Silpo cart. The live site is a demo with scripted replies; the full app is in the [code](https://github.com/partum55/silpo_party).

**[UCUSnack](https://ucusnack.app)** — Online shop for a self-service micro-market in a university dormitory (team of 3, just launching).
Next.js · Supabase · Monobank
Catalog with search, a cart, a barcode scanner and online payment through Monobank. My part: the staff and admin back office (products, stock per dormitory wing, coupons, orders) and hardening of the payment flow.

**[Vumlo](https://github.com/Vumlo/vumlo-core)** — Open-source (MIT), self-hosted learning platform for a single school or university.
Rust · PostgreSQL · Next.js · Tauri · Docker
Courses, groups, assignments with quizzes and forms, a gradebook, password or Google sign-in and an optional offline desktop app. [UCU deployment](https://vumlo-ucu.vercel.app) (opens on a sign-in screen, university accounts only). It succeeds my earlier [LearnSystem](https://github.com/partum55/LearnSystem), a Spring Boot and React version on microservices.

**[15x4](https://15x4.vercel.app)** — Multi-role platform for a public lecture community.
Next.js · React · TypeScript · Supabase
Email-confirmation auth, an admin moderation dashboard, a bilingual (UA/EN) interface, and AI-powered content translation. [Code](https://github.com/partum55/15x4)

**[MedLab](https://github.com/partum55/medlab)** — Clinic diagnostic web app with role-based access for 4 staff roles.
Next.js · TypeScript · Supabase · PostgreSQL
Supabase SSO (Google + GitHub), middleware-level role resolution, and a normalized 7-table schema for the full orders → specimens → reports → results workflow.

**[Hirely](https://github.com/partum55/hirely)** — AI career assistant (hackathon, team of 3).
React · Django · Groq API
CV builder, AI mock-interview simulator, and a skills trainer, in English and Ukrainian.

**[Planly](https://github.com/partum55/planly)** — AI agent that pulls action items out of group chats (hackathon prototype, not deployed at the moment).
Python · FastAPI · Llama 3.1 · Telegram API · Google Calendar · Supabase
Reads Telegram groups, or any chat app through screenshots, and turns plans like “dinner on Friday” into calendar events and venue suggestions. The model runs through Ollama, or any OpenAI-compatible cloud API such as Groq.

-----

## Open source and side projects

**[terllm](https://github.com/partum55/terllm)** — A tiny local model that autocompletes terminal commands in zsh and bash.
C++ · Python · llama.cpp · SmolLM2 · Modal
A 135M-parameter model fine-tuned on synthetic shell sessions. A native C++ daemon runs it on the CPU, nothing leaves the machine, and it installs as a `.deb` (Debian/Ubuntu, x86-64).

**[VIO](https://github.com/partum55/vio)** — Visual-inertial odometry in C++: estimating how a camera moves from video and motion-sensor data (team project, in progress).
C++20 · OpenCV · Eigen · OpenCL · Rerun
Reads EuRoC dataset sequences, detects and tracks features, estimates the camera pose (PnP + RANSAC), triangulates 3D points and filters IMU data, with an optional OpenCL-accelerated tracker and live Rerun visualization. Bundle adjustment and accuracy evaluation are not implemented yet.

**[Vepryk 6+](https://github.com/partum55/vepryk6plus)** — Remote control and vision for a tracked robot platform (team project).
C++ · Python · Qt · MAVLink · Raspberry Pi · ESP32
A joystick-driven desktop app with live video and telemetry sends MAVLink commands over an SSH tunnel to a Raspberry Pi that drives an ESP32 motor controller. Also has a mode that follows an AprilTag marker with a PID controller.

**[Вартові мрії (Vartovi Mrii)](https://vartovimrii.vercel.app)** — Website and e-ticketing for a charity ball in Kolomyia, where I’m on the organizing team.
Astro · GSAP · Next.js · Supabase
A sponsor landing site with scroll-driven animation, plus an admin panel that issues QR e-tickets scanned at the entrance.

**SemEval RETECO** — Team project for the UCU AI course: our entry in SemEval-2027 RETECO, conversational-retrieval track (in progress).
Python · BM25 · sentence-transformers · Modal
BM25 and dense baselines reproduced against the organisers’ numbers, weighted rank fusion tuned per domain, and LLM query rewriting, scored with nDCG@10.

-----

## Tools I reach for

**Languages:** TypeScript, JavaScript, Python, Java, Rust, C++
**Web:** React, Next.js, Astro, Spring Boot, FastAPI, Django, Node.js, Tailwind
**Data & infra:** PostgreSQL, MySQL, Supabase, Docker, Git
**AI:** Groq API, AI SDK, MCP, llama.cpp

Currently going deeper on Java/Spring and distributed systems.

-----

## Reach me

- Email — [partumyt@gmail.com](mailto:partumyt@gmail.com)
- LinkedIn — [nazar-mykhailyshchuk](https://linkedin.com/in/nazar-mykhailyshchuk)

-----

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=partum55&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="150"/>

<br/>

![Snake animation](https://raw.githubusercontent.com/partum55/partum55/output/github-snake-dark.svg)

<br/>

![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

</div>
