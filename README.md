<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=750&lines=+Dibyo+Banerjee;Full-Stack+Software+Developer;REST+APIs+%7C+JWT+Auth+%7C+MongoDB;Java+%7C+DSA+%7C+500%2B+LeetCode+Problems;Building+%E2%86%92+Learning+%E2%86%92+Growing" alt="Typing SVG" />
</div>

<br/>

<div align="center">
  <a href="https://dibyo.tech/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-dibyo.tech-00D9FF?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/dibyo-banerjee" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Dibyo_Banerjee-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <!-- <a href="https://github.com/dibyo20" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-dibyo20-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a> -->
  <a href="https://leetcode.com/u/dibyo20/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-dibyo20-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/>
  </a>
  <a href="mailto:dibyobanerjee20@gmail.com">
    <img src="https://img.shields.io/badge/Email-Reach_Out-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</div>

---

## 💼 Professional Summary

Full-Stack MERN Developer with hands-on professional experience building and shipping scalable, secure web applications end-to-end — from architecting RESTful APIs to crafting responsive, component-driven UIs. Skilled in JWT authentication, Redis caching, cloud media integration, Razorpay payment flows, and MongoDB schema design, with a strong problem-solving foundation backed by 500+ LeetCode problems solved in Java.

**What I bring to the table:**
- ✅ **End-to-End MERN Development** — Production-ready apps from schema design to VPS deployment
- ✅ **Strong DSA Foundation** — 500+ LeetCode problems solved in Java, 245+ day streak
- ✅ **API Engineering** — JWT auth, Redis-backed session/token caching, role-based access control, Razorpay payment flows, cloud media integration
- ✅ **UI Engineering** — Responsive, mobile-first design with reusable component systems
- ✅ **DevOps Basics** — VPS deployment, Nginx, PM2, custom domain/DNS, Render, Vercel

**Currently:**
- 💼 Working as a **Full-Stack Web Dev Intern** at **Solvit** — shipping a production-grade counselling marketplace
- 🛒 Shipped **NexGear** — an enterprise-grade e-commerce platform with Razorpay payments, variant-aware cart, and Google OAuth
- 📚 Deepening DSA skills and System Design fundamentals
- 🌐 Exploring backend architecture patterns and scalable API design
- 🤖 Exploring AI/ML and its integration with web applications

---

## 💼 Experience

<table>
  <tr>
    <td valign="top">
      <h3>🏢 Solvit — Web Development Intern (Full-Stack, MERN)</h3>
      <p><strong>Remote &nbsp;|&nbsp; Aug 2026 – Present</strong></p>
      <p><strong>Stack:</strong> React 19 · Vite · Node.js · Express.js · MongoDB · Mongoose · JWT · Razorpay · PM2 · Nginx · VPS</p>
      <p>
        • Primary developer owning backend, frontend, and VPS deployment of a production counselling marketplace; hardened the Express/MongoDB backend for 200–250 concurrent users with tiered rate limiting, 50-socket connection pooling, compound indexes, and PM2 clustering — cutting auth queries by 50% and a catalog aggregation from ~350 ms to ~15 ms.<br/>
        • Engineered a payment and booking pipeline with Razorpay HMAC-SHA256 verification, Idempotency-Key protection, partial unique index preventing double-booking, and automatic refund fail-safes; built a zero-trust coupon engine with an admin portal featuring a kill-switch, audit trail, and analytics.<br/>
        • Designed secure authentication: short-lived access tokens with rotating HttpOnly refresh tokens, replay-attack detection, instant server-side revocation, role-isolated cookies, and silent refresh via Axios interceptors — structured as a 4-layer frontend architecture.<br/>
        • Cut the initial JavaScript payload from 5.34 MB to 188 kB using React.lazy route splitting, Vite vendor chunking, and Brotli/Gzip pre-compression; replaced 60-second polling with a focus/visibility-aware refresh hook, reducing idle background requests to zero.
      </p>
      <p>
        <strong>Live:</strong> <a href="https://solvitcounselling.com/">solvitcounselling.com</a>
      </p>
    </td>
  </tr>
</table>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎮 <a href="https://github.com/dibyo20/Nexgear">NexGear</a></h3>
      <p>Enterprise-grade full-stack e-commerce platform for mechanical hardware & studio equipment, built with SDE-level design patterns.</p>
      <p>
        <strong>Key Highlights:</strong><br/>
        • 17 REST endpoints across auth, products, cart & payments<br/>
        • Variant-aware SKU cart with real-time stock validation & atomic updates<br/>
        • 8-stage MongoDB aggregation pipeline computing totals in-database<br/>
        • Razorpay HMAC-SHA256 payment verification with immutable payment ledger<br/>
        • Google OAuth 2.0 (Passport.js) + Redis JWT blacklisting (O(1) lookup)<br/>
        • Buyer/Seller RBAC with protected & guest route guards
      </p>
      <p><strong>Stack:</strong> React 19 · Redux Toolkit · Node.js · Express 5 · MongoDB · Redis · Razorpay · Passport.js · JWT · ImageKit · Vite · SCSS</p>
      <p>
        <strong>Live:</strong> <a href="https://nexgear.dibyo.tech/">nexgear.dibyo.tech</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🎵 <a href="https://github.com/dibyo20/Predicto">Predicto</a></h3>
      <p>Mood-based music platform that reads real-time facial expressions on-device and streams a curated, mood-matching playlist.</p>
      <p>
        <strong>Key Highlights:</strong><br/>
        • On-device face landmarking & mood classification with MediaPipe<br/>
        • Redis-backed JWT blacklisting for secure logout/session handling<br/>
        • ID3 metadata auto-parsing on track ingestion<br/>
        • Full-featured custom audio player streamed via ImageKit CDN
      </p>
      <p><strong>Stack:</strong> React.js · Node.js · Express.js · MongoDB · Redis · MediaPipe · JWT · ImageKit · Vite</p>
      <p>
        <strong>Live:</strong> <a href="https://predicto.dibyo.tech/">predicto.dibyo.tech</a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📱 <a href="https://github.com/dibyo20/Clicksy">Clicksy</a></h3>
      <p>Feature-rich MERN social media platform covering auth, dynamic feeds, posts, likes, comments, and follows.</p>
      <p>
        <strong>Key Highlights:</strong><br/>
        • 20+ REST API endpoints for user interactions & feeds<br/>
        • ImageKit API for secure media uploads<br/>
        • Cookie-based JWT session handling with role-aware access<br/>
        • Mobile-first responsive UI with SCSS components
      </p>
      <p><strong>Stack:</strong> React.js · Node.js · Express.js · MongoDB · JWT · SCSS · ImageKit · Vite</p>
      <p>
        <strong>Live:</strong> <a href="https://clicksy.dibyo.tech/">clicksy.dibyo.tech</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🧑‍⚕️ <a href="https://github.com/dibyo20/Solvit-Counselling">Solvit Counselling</a></h3>
      <p>Full-stack counselling platform for discovering professional counsellors, authenticating users, and browsing specialists by their area of expertise.</p>
      <p>
        <strong>Key Highlights:</strong><br/>
        • Cookie-based JWT authentication with HTTP-only session tokens<br/>
        • Counsellor discovery with search & specialization filtering<br/>
        • Appointment booking UI workflow<br/>
        • Responsive, user-friendly React interface
      </p>
      <p><strong>Stack:</strong> React.js · Node.js · Express.js · MongoDB · JWT · SCSS</p>
      <p>
        <strong>Live:</strong> <a href="https://solvit.dibyo.tech/">solvit.dibyo.tech</a>
      </p>
    </td>
  </tr>
</table>

---

## ⚙️ Tech Stack

### Frontend
<div align="left">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
  <img src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white"/>
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
</div>

### Backend & APIs
<div align="left">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_OAuth_2.0-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/Razorpay-02042B?style=for-the-badge&logo=razorpay&logoColor=3395FF"/>
  <img src="https://img.shields.io/badge/Bcrypt.js-003A70?style=for-the-badge&logo=letsencrypt&logoColor=white"/>
  <img src="https://img.shields.io/badge/Passport.js-34E27A?style=for-the-badge&logo=passport&logoColor=white"/>
</div>

### Database & Caching
<div align="left">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
</div>

### Languages & Tools
<div align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
</div>

### ☁️ Cloud, Media & DevOps
<div align="left">
  <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white"/>
  <img src="https://img.shields.io/badge/ImageKit-20A8D8?style=for-the-badge&logo=imagekit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
  <img src="https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white"/>
  <img src="https://img.shields.io/badge/VPS_Deployment-333333?style=for-the-badge&logo=linux&logoColor=white"/>
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
</div>

### 🤖 AI / ML — Learning & Exploring
<div align="left">
  <img src="https://img.shields.io/badge/Generative_AI-FF6B6B?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/MediaPipe-0F9D58?style=for-the-badge&logo=google&logoColor=white"/>
</div>

---

## 📊 DSA & Problem Solving

| Platform | Stat |
|:---|:---|
| 🟡 **LeetCode** | 500+ Problems Solved |
| 🔥 **Streak** | 245+ Days |
| 📚 **Language** | Java |
| 🧠 **Topics** | Arrays · Strings · Linked Lists · Trees · Binary Search · Recursion · Sliding Window · Two Pointers · Graph |

[![LeetCode Stats](https://leetcard.jacoblin.cool/dibyo20?theme=dark&font=JetBrains%20Mono&ext=activity)](https://leetcode.com/u/dibyo20/)

---

## 📈 GitHub Stats

<div align="">
  <img src="https://streak-stats.demolab.com?user=dibyo20&theme=tokyonight&hide_border=false"/>
  <br/>
  <br/>
  <img src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=dibyo20&theme=tokyonight&hide_border=false&layout=compact"/>
</div>

---

## 📬 Get In Touch

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-dibyo.tech-00D9FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://dibyo.tech/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dibyo_Banerjee-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dibyo-banerjee)
[![LeetCode](https://img.shields.io/badge/LeetCode-dibyo20-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/dibyo20/)
[![Email](https://img.shields.io/badge/Email-dibyobanerjee20%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dibyobanerjee20@gmail.com)

</div>
<!-- <br/> -->

<!-- <div align="center">
  <img src="https://komarev.com/ghpvc/?username=dibyo20&style=for-the-badge&color=00D9FF&label=PROFILE+VIEWS" alt="Profile Views"/>
</div> -->

---

<div align="center">
  <strong>Open to internships, collaborations, and full-stack opportunities</strong>
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=4000&pause=1500&color=00D9FF&center=true&vCenter=true&width=700&lines=Writing+clean+code+%7C+Solving+hard+problems+%7C+Shipping+real+products" alt="Tagline" />
</div>
