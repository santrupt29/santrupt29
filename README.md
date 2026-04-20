# Hi, I'm Santrupt

Backend Developer focused on distributed systems, real-time applications, and high-performance Java/Spring Boot services. Pre-final year ECE student at VJTI Mumbai, actively building and shipping.

---

## 🛠 Tech Stack

**Languages:** Java, C++, Python, JavaScript/TypeScript  
**Backend:** Spring Boot, Node.js, Express  
**Frontend:** Next.js, React  
**Databases:** PostgreSQL, MongoDB, Redis, Supabase  
**Infrastructure:** Kafka, WebSocket (STOMP), AWS S3, DigitalOcean, Docker, FFmpeg  
**Observability:** Prometheus, Grafana, Zipkin

---

## 🚀 Projects

**[Doodle-Sync](https://drive.google.com/file/d/1T3MsEo3LxXi6Gzky-4QpUbwg6AkAsaOq/view)** — Real-Time Multiplayer Drawing Game  
`Spring Boot · Kafka · Redis · WebSocket/STOMP · Docker`  [Source](https://github.com/santrupt29/Doodle-Sync)
- 7 microservices via Spring Cloud Gateway with Resilience4j circuit breakers
- p99 < 1ms stroke latency using Redis Pub/Sub; Kafka reserved for durable game events
- 5-state game machine with time-decay scoring and Levenshtein-based guess detection
- Redis-backed WebSocket ticketing system (30s TTL) bridging JWT auth

**[Vortex](https://vortexhq.vercel.app)** — Video Streaming Platform  
`Spring Boot · PostgreSQL · AWS S3 · FFmpeg · Next.js`  [Source](https://github.com/santrupt29/stream-spring-backend)
- Async Java 21 video pipeline via ExecutorService; eliminated processing timeouts
- Adaptive Bitrate Streaming (360p/720p HLS) using FFmpeg filter complex
- Parallelized S3 uploads with `CompletableFuture.allOf()` — upload time: 120s → 20s
- Hosted on DigitalOcean; eliminated 100% of OOM crashes via swap + PostgreSQL tuning

**[HireLyze](https://hirelyzehq.vercel.app)** — AI-Powered Hiring Platform  
`React · Express · Supabase · Google GenAI · Redis` · [Source](https://github.com/santrupt29/ai-resume-screener)  
- AI resume matcher processing 1,000+ resumes with 90%+ alignment accuracy
- Redis-backed PDF/DOCX parsing pipeline — 3x throughput improvement
- Serverless APIs + Supabase for 300+ job postings at 99.9% uptime

---

## 📊 Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=santrupt29&show_icons=true&theme=dark&hide_border=true&include_all_commits=true&count_private=true" width="410" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=santrupt29&layout=compact&theme=dark&hide_border=true&langs_count=8" width="310" />
  <br/>
  <img src="https://streak-stats.demolab.com?user=santrupt29&theme=dark&hide_border=true" width="730" />
</div>

---

## 🏆 Competitive Programming

- **LeetCode:** 600+ problems · Peak rating 1687 (Top 15% globally)
- **CodeChef:** 3★ · Highest rating 1608 (Top 25%)
- **Codeforces:** Pupil · 200+ problems · Peak 1275

---

## 📬 Connect

[LinkedIn](https://linkedin.com/in/santrupt29) · [Portfolio](https://santrupt29.vercel.app) · [Email](mailto:santrupt.potphode29@gmail.com) · [X](https://x.com/santrupt_29)
