<div align="center">

# Hi there, I'm Kyle 👋

### **Full-Stack Software Engineer**

*Next.js • React • TypeScript • Prisma • Web Audio*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-kyle--snelgrove-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kyle-snelgrove/)
[![GitHub](https://img.shields.io/badge/GitHub-krsnelgrove--del-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/krsnelgrove-del)

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

</div>

I specialize in building high-performance web applications, serverless architectures, and complex interactive web interfaces. My focus centers on end-to-end product execution: from responsive front-end UI systems to serverless route handlers, relational database design, and edge deployment pipelines.

---

## 🧰 Technical Stack & Ecosystem

| | |
|---|---|
| **Frontend** | Next.js (App Router), React, TypeScript, Tailwind CSS, shadcn/ui, Zustand, Recharts, Web Audio API |
| **Backend** | Node.js, Prisma ORM, PostgreSQL, Supabase, Next.js Route Handlers, RESTful APIs |
| **DevOps** | Git, GitHub Actions, Netlify Edge, Vercel, Serverless Functions, Connection Pooling (PgBouncer) |

---

## 🚀 Featured Engineering Projects

### 🎹 [Synthesize!](https://github.com/krsnelgrove-del/synthesizer-project)
**Browser-based synthesizer and step sequencer, built from scratch on the Web Audio API**

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433e38?style=flat-square)

* Built a playable synth with sine, sawtooth, triangle, and square oscillators, an ADSR envelope, and a reverb, delay, and distortion effects chain, with no audio libraries.
* Designed a 37-note piano-roll step sequencer with a looping, requestAnimationFrame-driven transport.
* Separated state into Zustand stores (`synthStore`, `transportStore`, sequencer store) so the audio engine can read them outside React's render cycle, and bridged engine state into React with `useSyncExternalStore`.
* Built composable keyboard components (`Key`, `Piano`, `Keyboard`) that work independently of one another and are configured through props.
* Tracked down a tricky scheduling bug where only the first sequenced note triggered, and fixed it with a local lookahead window in the audio engine.
* [Live Demo](https://synthesize-project.vercel.app/home) · [Repository Source](https://github.com/krsnelgrove-del/synthesizer-project)

### ⚡ [Operation: Overthink](https://github.com/krsnelgrove-del/operation-overthink)
**Full-Stack Next.js Technical Showcase & Web Dashboard**

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma_ORM-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433e38?style=flat-square)

* Built with Next.js (App Router), React, TypeScript, Tailwind CSS, and Recharts.
* Engineered Next.js route handlers, real-time latency polling mechanisms, and client-side state management via Zustand.
* Integrated Prisma ORM with a hosted Supabase PostgreSQL database, utilizing connection poolers for low-latency serverless edge execution.
* [Live Demo](https://operation-overthink.netlify.app/home) · [Repository Source](https://github.com/krsnelgrove-del/operation-overthink)

### 🚐 [Look! 3D Vehicle Configurator](https://github.com/krsnelgrove-del/Look-Product-Configurator)
**Real-time 3D product configurator built in Unity and deployed to the web as WebGL**

![Unity](https://img.shields.io/badge/Unity_6-000000?style=flat-square&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)

* Built an interactive 3D vehicle configurator with orbit and zoom controls, live paint, rim, and accessory changes, and a running USD total, aimed at streamlining sales quotes for specialty vehicle upfitters.
* Used Cinemachine for smooth camera transitions and weighed its per-frame blend cost against the alternative of hand-rolled interpolation.
* Modeled pricing in integer pennies with an event-driven cart, plus JSON export of the order for a future quoting backend.
* Shipped a Brotli-compressed WebAssembly build to Netlify by configuring `Content-Type` and `Content-Encoding` headers in `netlify.toml`.
* [Live Demo](https://configurator-demo-s001.netlify.app/) · [Repository Source](https://github.com/krsnelgrove-del/Look-Product-Configurator)

---

## 📊 Engineering Highlights

* 🛠 **Architecture:** Deep focus on serverless edge functions, connection pooling, and Row Level Security (RLS) policies.
* ⚡ **Performance:** Responsive layout engineering, dynamic client-side caching, and bundle optimization.
* 🗄 **Data Hygiene:** Schema drift resolution, migration workflows, and type alignment between Prisma and TypeScript contracts.
* ⏱ **Real-Time Systems:** Audio scheduling and timing, `requestAnimationFrame`-driven loops, and SSR-safe browser APIs.

---

## 📬 Connect with Me

* **LinkedIn:** [linkedin.com/in/kyle-snelgrove](https://www.linkedin.com/in/kyle-snelgrove/)
* **GitHub:** [github.com/krsnelgrove-del](https://github.com/krsnelgrove-del)
