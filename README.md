<div align="center">

# Nazar Mykhailyshchuk

**Full-stack developer · Computer Science student at the Ukrainian Catholic University, Lviv**

[![Portfolio](https://img.shields.io/badge/Portfolio-partum55.me-1a1b26?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjN2FhMmY3IiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMTAiLz48cGF0aCBkPSJNMiAxMmgyME0xMiAyYTE1LjMgMTUuMyAwIDAgMSA0IDEwIDE1LjMgMTUuMyAwIDAgMS00IDEwIDE1LjMgMTUuMyAwIDAgMS00LTEwIDE1LjMgMTUuMyAwIDAgMSA0LTEweiIvPjwvc3ZnPg%3D%3D)](https://www.partum55.me)
[![Email](https://img.shields.io/badge/Email-partumyt%40gmail.com-1a1b26?style=for-the-badge&logo=gmail&logoColor=7aa2f7)](mailto:partumyt@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-nazar--mykhailyshchuk-1a1b26?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iIzdhYTJmNyIgZD0iTTIwLjQ1IDIwLjQ1aC0zLjU2di01LjU3YzAtMS4zMy0uMDMtMy4wNC0xLjg1LTMuMDQtMS44NiAwLTIuMTQgMS40NS0yLjE0IDIuOTR2NS42N0g5LjM0VjloMy40MXYxLjU2aC4wNWMuNDgtLjkgMS42NC0xLjg1IDMuMzctMS44NSAzLjYgMCA0LjI3IDIuMzcgNC4yNyA1LjQ2djYuMjh6TTUuMzQgNy40M2EyLjA2IDIuMDYgMCAxIDEgMC00LjEyIDIuMDYgMi4wNiAwIDAgMSAwIDQuMTJ6TTcuMTIgMjAuNDVIMy41NlY5aDMuNTZ2MTEuNDV6Ii8%2BPC9zdmc%2B)](https://linkedin.com/in/nazar-mykhailyshchuk)

</div>

I build full-stack web apps, usually Next.js or Spring Boot in front of a real database, often with an LLM somewhere in the pipeline. Most of what’s here started as a course project or a hackathon and ended up deployed. I also mentor first-year students on algorithms and data-structure projects.

-----

## Things I’ve shipped

<table>
<tr>
<td width="33%" valign="top">
<a href="https://ucusnack.app"><img src="assets/ucusnack.jpg" alt="UCUSnack"></a>
<h3><a href="https://ucusnack.app">UCUSnack</a></h3>
<sub>Team of 3 · just launching · <a href="https://ucusnack.app">live</a></sub>
<p>Online shop for a self-service micro-market in a university dormitory: catalog with search, a cart, a barcode scanner and online payment through Monobank. My part: the staff and admin back office (products, stock per dormitory wing, coupons, orders) and hardening of the payment flow.</p>
<code>Next.js</code> <code>Supabase</code> <code>Monobank</code>
</td>
<td width="33%" valign="top">
<a href="https://vartovimrii.vercel.app"><img src="assets/vartovi-mrii.jpg" alt="Vartovi Mrii"></a>
<h3><a href="https://vartovimrii.vercel.app">Вартові мрії (Vartovi Mrii)</a></h3>
<sub>Charity ball in Kolomyia · I’m on the organizing team · <a href="https://vartovimrii.vercel.app">live</a></sub>
<p>A sponsor landing site with scroll-driven animation, plus an admin panel that issues QR e-tickets scanned at the entrance.</p>
<code>Astro</code> <code>GSAP</code> <code>Next.js</code> <code>Supabase</code>
</td>
<td width="33%" valign="top">
<a href="https://15x4.vercel.app"><img src="assets/15x4.jpg" alt="15x4"></a>
<h3><a href="https://15x4.vercel.app">15x4</a></h3>
<sub>Public lecture community · <a href="https://15x4.vercel.app">live</a> · <a href="https://github.com/partum55/15x4">code</a></sub>
<p>Multi-role platform: email-confirmation auth, an admin moderation dashboard, a bilingual (UA/EN) interface, and AI-powered content translation.</p>
<code>Next.js</code> <code>React</code> <code>TypeScript</code> <code>Supabase</code>
</td>
</tr>
</table>

-----

## Open source and research

<details open>
<summary><b>Vumlo</b> — self-hosted learning platform for a school or university <i>(open source, MIT)</i></summary>
<br>

[Code](https://github.com/Vumlo/vumlo-core) · [UCU deployment](https://vumlo-ucu.vercel.app) (opens on a sign-in screen, university accounts only)

`Rust` `PostgreSQL` `Next.js` `Tauri` `Docker`

Courses, groups, assignments with quizzes and forms, a gradebook, password or Google sign-in and an optional offline desktop app. It succeeds my earlier [LearnSystem](https://github.com/partum55/LearnSystem), a Spring Boot and React version on microservices.

</details>

<details open>
<summary><b>terllm</b> — a tiny local model that autocompletes terminal commands</summary>
<br>

[Code](https://github.com/partum55/terllm) · [Model on Hugging Face](https://huggingface.co/partum/terllm)

`C++` `Python` `llama.cpp` `SmolLM2` `Modal`

A 135M-parameter model fine-tuned on synthetic shell sessions suggests the rest of a command in zsh and bash. A native C++ daemon runs it on the CPU, nothing leaves the machine, and it installs as a `.deb` (Debian/Ubuntu, x86-64).

</details>

<details>
<summary><b>VIO</b> — visual-inertial odometry in C++ <i>(course team project, in progress)</i></summary>
<br>

[Code](https://github.com/partum55/vio)

`C++20` `OpenCV` `Eigen` `OpenCL` `Rerun`

Estimates how a camera moves from video and motion-sensor data. Reads EuRoC dataset sequences, detects and tracks features, estimates the camera pose (PnP + RANSAC), triangulates 3D points and filters IMU data, with an optional OpenCL-accelerated tracker and live Rerun visualization. Bundle adjustment and accuracy evaluation are not implemented yet.

</details>

<details>
<summary><b>Vepryk 6+</b> — remote control and vision for a tracked robot platform <i>(course team project)</i></summary>
<br>

[Code](https://github.com/partum55/vepryk6plus)

`C++` `Python` `Qt` `MAVLink` `Raspberry Pi` `ESP32`

A joystick-driven desktop app with live video and telemetry sends MAVLink commands over an SSH tunnel to a Raspberry Pi that drives an ESP32 motor controller. Also has a mode that follows an AprilTag marker with a PID controller.

</details>

<details>
<summary><b>SemEval RETECO</b> — conversational retrieval <i>(UCU AI course team project, in progress)</i></summary>
<br>

`Python` `BM25` `sentence-transformers` `Modal`

Our entry in SemEval-2027 RETECO, conversational-retrieval track. BM25 and dense baselines reproduced against the organisers’ numbers, weighted rank fusion tuned per domain, and LLM query rewriting, scored with nDCG@10.

</details>

-----

## Hackathons

<table>
<tr>
<td width="42%" valign="top"><a href="https://www.silpoparty.app"><img src="assets/silpo-party.jpg" alt="Silpo Party"></a></td>
<td width="58%" valign="top">
<h3><a href="https://www.silpoparty.app">Silpo Party</a></h3>
<sub><b>Hackathon</b> · team of 4 · <a href="https://www.silpoparty.app">live demo</a> · <a href="https://github.com/partum55/silpo_party">code</a></sub>
<p>AI that turns a group chat into a ready-to-buy basket from the live catalog of Silpo, a Ukrainian supermarket chain. Food restrictions and budget respected, cost split fairly, one-click handoff to the host’s real Silpo cart. The live site is a demo with scripted replies; the full app is in the code.</p>
<code>Next.js</code> <code>TypeScript</code> <code>Supabase</code> <code>AI SDK</code> <code>MCP</code>
</td>
</tr>
</table>

<details>
<summary><b>Hirely</b> — AI career assistant <i>(hackathon, team of 3)</i></summary>
<br>

[Code](https://github.com/partum55/hirely)

`React` `Django` `Groq API`

CV builder, AI mock-interview simulator, and a skills trainer, in English and Ukrainian.

</details>

<details>
<summary><b>Planly</b> — AI agent for group chats <i>(hackathon prototype, not deployed at the moment)</i></summary>
<br>

[Code](https://github.com/partum55/planly)

`Python` `FastAPI` `Llama 3.1` `Telegram API` `Google Calendar` `Supabase`

Reads Telegram groups, or any chat app through screenshots, and turns plans like “dinner on Friday” into calendar events and venue suggestions. The model runs through Ollama, or any OpenAI-compatible cloud API such as Groq.

</details>

-----

## Tools I reach for

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,js,py,java,rust,cpp,react,nextjs,astro,spring,fastapi,django,nodejs,tailwind,postgres,mysql,supabase,docker,git&theme=dark&perline=10" alt="TypeScript, JavaScript, Python, Java, Rust, C++, React, Next.js, Astro, Spring Boot, FastAPI, Django, Node.js, Tailwind, PostgreSQL, MySQL, Supabase, Docker, Git">

<sub>Plus Groq API, AI SDK, MCP and llama.cpp on the AI side. Currently going deeper on Java/Spring and distributed systems.</sub>

</div>

-----

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=partum55&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="150"/>

<br/>

![Snake animation](https://raw.githubusercontent.com/partum55/partum55/output/github-snake-dark.svg)

<br/>

![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

</div>
