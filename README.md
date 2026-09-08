<div align="center">
  <h1>👋 Hi, I'm Nikhil!</h1>
  <h3>Full-Stack AI & Distributed Systems Engineer</h3>
  <p><b>🎓 2027 Graduate · 🚀 Actively seeking Software Engineering roles</b></p>
</div>

<p align="center">
  <a href="https://go.dev/"><img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" /></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /></a>
  <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /></a>
  <a href="https://nodejs.org/"><img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" /></a>
  <a href="https://nextjs.org/"><img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" /></a>
  <a href="https://www.postgresql.org/"><img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="Postgres" /></a>
  <a href="https://redis.io/"><img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" /></a>
  <a href="https://www.docker.com/"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" /></a>
  <a href="https://aws.amazon.com/"><img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS" /></a>
  <a href="https://prometheus.io/"><img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" /></a>
  <a href="https://grafana.com/"><img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" /></a>
  <a href="https://grpc.io/"><img src="https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=google&logoColor=white" alt="gRPC" /></a>
  <a href="https://langfuse.com/"><img src="https://img.shields.io/badge/LangFuse-4F46E5?style=for-the-badge&logoColor=white" alt="LangFuse" /></a>
</p>

---

### 🚀 Featured Projects

<h3 align="center"><a href="https://github.com/nikhilsaxena04/OmniRoute-Multi-Provider-LLM-Gateway">🔀 OmniRoute: Multi-Provider LLM Gateway</a></h3>
<p align="center"><i>Production-grade AI gateway — born from the Sep 3 Azure outage that killed ChatGPT, Claude & Grok at once</i></p>

- **Resilience:** Circuit breaker + rate limiter built from scratch in **&lt;80 lines each** — sliding-window state machine, zero third-party libraries
- **Routing:** Cost-aware failover across **5 LLM providers** — when Gemini dropped pricing 40%, it was a one-line YAML change, not a redeploy
- **Evaluation:** Python engine that mathematically proves ROI — Groq at **$0.00006/req** vs Claude at **$0.0004/req**, identical quality scores
- **Observability:** **Prometheus/Grafana** for P95 latency, **LangFuse** for per-request AI tracing — two layers answering different failure modes

<br/>

<h3 align="center"><a href="https://github.com/nikhilsaxena04/notification-service">📬 Distributed Notification Broker</a></h3>
<p align="center"><i>High-throughput, event-driven async queueing system</i></p>

- **Performance:** Benchmarked at **9,200+ req/s** — 552k requests in 60s, P95 latency under 30ms
- **Architecture:** 3-tier microservice decoupled by a Redis queue
- **Resilience:** Zero silent job loss via atomic `BLMOVE` & DLQ archival to S3
- **Observability:** Distributed tracing with OpenTelemetry & Jaeger

<br/>

<h3 align="center"><a href="https://github.com/nikhilsaxena04/meta_clash">⚔️ Meta Clash: Multiplayer Card Game</a></h3>
<p align="center"><i>Real-time, persistent WebSocket game engine</i></p>

- **Real-Time:** Concurrent WebSocket connections with `sync.RWMutex`
- **Safety:** Strict Finite State Machine (FSM) to prevent illegal moves
- **AI Pipeline:** Gemini LLM for card generation with deterministic fallback
- **Full Stack:** Next.js + Go/PostgreSQL on Vercel & Railway

---

### 📫 Let's Connect

<p align="center">
  <a href="https://linkedin.com/in/nikhil-saxena-codes"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:myemailnikhilsaxena@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://drive.google.com/file/d/1akB4AjTEFXGT8M4DRur5zylDSEl7ShI1/view?pli=1"><img src="https://img.shields.io/badge/Resume-4CAF50?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume" /></a>
  <a href="https://vimeo.com/showcase/12392051"><img src="https://img.shields.io/badge/Video_Portfolio-1AB7EA?style=for-the-badge&logo=vimeo&logoColor=white" alt="Video Portfolio" /></a>
</p>

<p align="center">
  <i>A collection of my engineering projects, focusing on distributed systems, Go, real-time concurrency, and high-throughput architecture.</i>
</p>
