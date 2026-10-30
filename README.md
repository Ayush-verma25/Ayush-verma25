<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Ayush%20Verma&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20Developer%20%E2%80%A2%20MERN%20%E2%80%A2%20TypeScript%20%E2%80%A2%20AI%20Integration&descAlignY=58&descSize=18" width="100%" alt="header"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&width=700&lines=I+build+AI-powered+full-stack+products;React+19+%7C+Node.js+%7C+Express+5+%7C+MongoDB+%7C+PostgreSQL;Open+to+Full-Stack+Developer+roles+%F0%9F%9A%80)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ayush-verma-2b8223329)
[![Email](https://img.shields.io/badge/Email-ayve012@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayve012@gmail.com)
[![GitHub followers](https://img.shields.io/github/followers/Ayush-verma25?style=for-the-badge&logo=github&color=181717)](https://github.com/Ayush-verma25)
![Profile views](https://komarev.com/ghpvc/?username=Ayush-verma25&style=for-the-badge&color=7C3AED&label=PROFILE+VIEWS)

</div>

---

## 👋 About Me

I'm a **MERN Stack Developer** based in **Ajmer, Rajasthan, India** with over a year of internship experience and a portfolio of **full-stack products that go beyond CRUD**: AI pipelines, role-based access control, payments, background jobs, multi-tenant architecture and production deployments.

- 🤖 Building **AI-integrated apps** with Google Gemini, OpenAI SDK, OpenRouter, Vercel AI SDK and Leonardo AI
- 🏗️ Comfortable across **MERN and PERN** stacks, with **TypeScript** on my newest projects
- 🔐 Experienced with **JWT auth, RBAC, Stripe / Razorpay payments, webhooks and cron / workflow jobs**
- 🚢 Ship to **Vercel, Render and AWS** with CI/CD via GitHub Actions
- 🎯 **Looking for:** a Full-Stack Developer role where I can build, test and maintain scalable web applications

---

## 🚀 Featured Projects

### 🛍️ [Orbivo: Multi-Tenant E-Commerce Platform](https://github.com/Ayush-verma25/Orbivo-E-Commerce-Platform-App) &nbsp; [![Live](https://img.shields.io/badge/Live_Demo-Open-22C55E?style=flat-square&logo=render&logoColor=white)](https://orbivo-e-commerce-platform-frontend.onrender.com)

> Anyone can launch their own branded online store in minutes: isolated storefronts for customers, a management console for merchants, and platform-wide oversight for admins.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Express](https://img.shields.io/badge/Express_5-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_(Neon)-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma_7-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary_AI-3448C5?style=flat-square&logo=cloudinary&logoColor=white)

- **Tenant isolation by construction:** every merchant query is scoped to the store resolved from the authenticated token, never from client input
- **Race-free checkout:** Prisma transactions with conditional stock decrements, so inventory can't oversell; prices are recomputed server-side
- **AI product photography** via Cloudinary generative AI: recolor, background removal and on-model virtual try-on
- **Hardened uploads:** magic-byte file checks, SVG sanitising and SSRF protection on remote image URLs
- Three roles (Customer / Merchant / Platform Admin), per-store theming and a Neon Function serving public reads
- *Frontend builds on the open-source StoreiFly project (MIT); the API layer, Neon Function, AI pipelines and admin features are my additions.*

---

### 🤖 AI-Integrated Projects

<table>
<tr>
<td width="50%" valign="top">

#### 📣 [PostPilot](https://github.com/Ayush-verma25/PostPilot-Social-Media-Automation-Platform-App) &nbsp; [🔗 Live](https://postpilot-social-media-automation.onrender.com)
**AI Social Media Automation Platform**

Compose, AI-generate, schedule and publish posts to **X, LinkedIn, Facebook and Instagram** from one dashboard.

- Strict-mode **TypeScript** MERN app
- **Crash-safe node-cron scheduler:** atomic claims, idempotency keys and reconciliation, so posts are never double-published or lost
- **Gemini** captions (retry with backoff, model fallback) + **Leonardo AI** images hosted on Cloudinary
- JWT, bcrypt, Helmet and rate limiting

`TypeScript` `React 19` `Express 5` `MongoDB` `Gemini` `Leonardo AI` `Cloudinary`

</td>
<td width="50%" valign="top">

#### ⚡ [SiteSpark](https://github.com/Ayush-verma25/SiteSpark-AI-Website-Builder-App) &nbsp; [🔗 Live](https://site-spark-ai-website-builder-app-t.vercel.app/login)
**AI Website Builder**

Describe a site in plain English; an AI agent plans it, writes the React code and previews it live.

- **Two-phase AI pipeline:** file plan, then parallel generation with retries
- **Zod-validated structured output** and auto-repair of common LLM code mistakes
- **Chat-based revisions** applied as create / update / delete patches, not full rewrites
- Live **Sandpack** preview, one-click publish and ZIP export

`React 19` `Express 5` `MongoDB` `Vercel AI SDK` `OpenRouter` `Zod`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧠 [Vertexa](https://github.com/Ayush-verma25/Vertexa-Full-Stack-AI-SaaS-App) &nbsp; [🔗 Live](https://vertexa-ai-frontend.onrender.com)
**Full-Stack AI SaaS Suite (PERN)**

Six AI tools behind one dashboard: article writer, blog titles, image generator, background remover, object remover and an ATS-aware resume reviewer.

- **Clerk** auth and subscription billing with **server-side Free / Premium gating**
- **Gemini** (via OpenAI SDK), **ClipDrop** and **Cloudinary AI**
- Community gallery with atomic likes in a single SQL update
- Prompt-injection-resistant resume review, hardened file uploads

`React 19` `Express 5` `PostgreSQL (Neon)` `Clerk` `Gemini` `Cloudinary`

</td>
<td width="50%" valign="top">

#### 📄 [ResumeNova](https://github.com/Ayush-verma25/ResumeNova-AI-Resume-Builder-APP) &nbsp; [🔗 Live](https://resume-nova-ai-resume-builder-app.vercel.app)
**AI Resume Builder**

Build, polish, import, share and print professional resumes.

- Live preview, **4 templates**, accent colours, public share links, print-to-PDF
- **AI Enhance** for summaries and job descriptions
- **AI PDF import:** extracted text becomes structured, editable resume data via an LLM in JSON mode
- Redux Toolkit auth state, ImageKit face-cropped photos

`React 19` `Redux Toolkit` `Express 5` `MongoDB` `OpenAI SDK` `ImageKit`

</td>
</tr>
</table>

---

### 🏢 More Production-Style Apps

| Project | What it does | Stack | Links |
|:--|:--|:--|:--|
| **WorkPilot** | Employee management with separate Admin / Employee portals for attendance, leave and payroll; RBAC re-verified from the DB on every request; MongoDB transactions; Inngest workflows for reminders and leave escalations; 21 backend regression tests | React 19, Express 5, MongoDB, Inngest, Nodemailer | [Code](https://github.com/Ayush-verma25/WorkPilot_Employment_Management_App_MERN) · [Live](https://work-pilot-employment-management-ap-six.vercel.app) |
| **SkillSpring (LMS)** | Learning management system: educators publish video courses; students discover, buy, watch and track them | MERN | [Code](https://github.com/Ayush-verma25/LMS-Website-App-MERN) · [Live](https://lms-website-app-mern-jhzn.vercel.app/) |
| **LMS Course Platform** | Second LMS built with the modern Next.js stack | Next.js 15, Clerk, Sanity CMS, Stripe, TypeScript | [Code](https://github.com/Ayush-verma25/Lms-Course-Platform-NextJs) · [Live](https://lms-course-platform-next-js.vercel.app) |
| **BiteMo** | Restaurant discovery and table reservation with owner dashboards and admin approval flow | MERN, TypeScript | [Code](https://github.com/Ayush-verma25/BiteMo-App) · [Live](https://bite-mo-app-client.vercel.app/) |
| **QuickStay** | Hotel booking with live availability, online payment and owner revenue dashboard | MERN | [Code](https://github.com/Ayush-verma25/QuickStay-Hotel-Booking-App) · [Live](https://quick-stay-hotel-booking-app-io73.vercel.app/) |
| **QuickShow** | Movie discovery and cinema seat booking with Stripe Checkout and admin dashboard | MERN, Stripe | [Code](https://github.com/Ayush-verma25/QuickShow-Movie-App-MERN) · [Live](https://quickshow-movie-app-mern-client.vercel.app/) |
| **Doctor Appointment System** | Browse doctors, book slots and pay online; separate admin and doctor dashboards | MERN, Razorpay | [Code](https://github.com/Ayush-verma25/Doctor-Appointment-Booking-System-MERN) · [Live](https://doctor-appointment-booking-system-mern-vct1.onrender.com) |
| **GreenCart** | Grocery e-commerce with COD / Stripe payments and a seller dashboard | MERN, Stripe | [Code](https://github.com/Ayush-verma25/Green-Cart-MERN) · [Live](https://green-cart-mern-client.vercel.app/) |
| **Zomo** | Zomato-inspired food delivery app | MERN | [Code](https://github.com/Ayush-verma25/Zomo-Food-Delivery-App-MERN) · [Live](https://zomo-food-delivery-app-mern-frontend.onrender.com) |
| **JobPortal** | Students search and apply; recruiters post jobs and review applicants | MERN | [Code](https://github.com/Ayush-verma25/JobPortal-App-MERN) · [Live](https://jobportal-app-mern-client.vercel.app/) |

<details>
<summary><b>🧪 Range across frameworks (click to expand)</b></summary>
<br/>

- **Angular 16:** [YourCartShop](https://github.com/Ayush-verma25/YourCartShop-App-Angular), a responsive e-commerce storefront ([live](https://your-cart-shop-app-angular.vercel.app))
- **Vue.js:** [Search Meals](https://github.com/Ayush-verma25/Search-Meals-with-VueJS), a recipe discovery SPA ([live](https://search-meals-with-vue-js.vercel.app))
- **Next.js:** [Blog App](https://github.com/Ayush-verma25/Nextjs-Blog-App), [Airbnb clone](https://github.com/Ayush-verma25/Airbnb-clone-using-NEXTJS), [Hulu clone](https://github.com/Ayush-verma25/Hulu-2.0-NextJs-TailwindCss)
- **React Native (Expo):** [Delivero food delivery](https://github.com/Ayush-verma25/Delivero-Food-Delivery-App-Using-Expo-React-Native) plus to-do apps backed by MongoDB and Firebase
- **Node.js backend:** [Job scheduler](https://github.com/Ayush-verma25/job-scheduler-using-NodeJS) for one-off and recurring tasks
- **Full-stack:** [Crypto tracker](https://github.com/Ayush-verma25/Full-Stack-Crypto-Tracker-App) with live price updates every 3 minutes

</details>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![MUI](https://img.shields.io/badge/Material_UI-007FFF?style=for-the-badge&logo=mui&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT_&_RBAC-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

**AI Integration**

![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_SDK-412991?style=for-the-badge&logo=openai&logoColor=white)
![Vercel AI SDK](https://img.shields.io/badge/Vercel_AI_SDK_+_OpenRouter-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Leonardo](https://img.shields.io/badge/Leonardo_AI-7C3AED?style=for-the-badge)

**Testing, DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_EC2_&_S3-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

**Payments & Services**

![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-0C2451?style=for-the-badge&logo=razorpay&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)

</div>

---

## 💼 Experience

**MERN Stack Developer Intern** · GRRAS Solutions Pvt. Ltd. · *Feb 2024 – Dec 2024*
- Built and shipped **3+ end-to-end MERN applications** with React frontends, Express REST APIs and MongoDB
- Implemented **JWT authentication and RBAC** across 2 production applications with multi-role workflows
- Optimized REST APIs and MongoDB queries (indexing, query restructuring); improved frontend load time with code splitting and lazy loading
- Set up **CI/CD pipelines** to automate deployments across AWS, Vercel and Render

**Web Development Intern** · Carikture India Pvt. Ltd. · *Jul 2022 – Sep 2022*
- Built 4+ responsive interfaces (HTML, CSS, JavaScript, Node.js), integrated 3 third-party REST APIs and resolved 15+ UI/UX issues

## 🎓 Education & Certification

- **MCA**, Jaipur National University, Jaipur · *2020 – 2022*
- **BCA**, S.S. Jain Subodh College, Jaipur · *2017 – 2020*
- **MERN Stack Developer Certificate**, GRRAS Solutions Pvt. Ltd.

---

## 📊 GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Ayush-verma25&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ayush-verma25&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Ayush-verma25&theme=tokyonight&hide_border=true" alt="GitHub streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Ayush-verma25&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph" width="100%"/>

</div>

---

## 📫 Let's Connect

I'm actively looking for **Full-Stack / MERN Developer** opportunities. If you're building something interesting, I'd love to hear about it.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ayush--verma-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ayush-verma-2b8223329)
[![Email](https://img.shields.io/badge/Email-ayve012@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayve012@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" alt="footer"/>

</div>
