
<div align="left">

  <!-- dynamic typing effect 动态打字效果 -->
  
  [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=console.log(%22Hello+World%22);System.out.println(%22Hello+World%22);print(%22Hello+World%22);Hope+you+have+a+nice+day!)](https://git.io/typing-svg)

  <div>&nbsp;</div>
# 👋 Hi, I'm Boyu Qian  

🎓 CS graduate from **McGill University**, passionate about **high-performance distributed systems**, **LLM infrastructure**, and **full-stack development**.  

🔭 Recently built:  
- **🤖 LLM Inference API Platform** – FastAPI + vLLM with real-time streaming, Prometheus/Grafana observability, supporting 500+ concurrent users & 2.5M tokens/day.  
- **🎫 High-Concurrency Ticketing System** – Java Spring Boot + Redis + Kafka, optimized with sharding, distributed locks, and Sentinel/Hystrix for extreme-scale traffic.  
- **💰 FinTrack** – Full-stack financial tracking app with React/TypeScript + Flask + PostgreSQL, serving 500+ active users with 99.7% uptime.  

🌱 Exploring **cloud-native architectures (AWS, Docker, Kubernetes)** and **scalable AI systems**.  
👯 Open to collaborating on **distributed systems, AI infrastructure, and full-stack applications**.  
🤔 Looking for help with **optimizing large-scale LLM inference and cost-efficient deployments**.  
💬 Ask me about **FastAPI, React/TypeScript, PostgreSQL optimization, Redis/Kafka, CI/CD pipelines**.  
📫 Reach me: [LinkedIn](http://linkedin.com/in/boyu-qian-524688211) | [GitHub](https://github.com/Boyu-Qian) | ✉️ **qianboyu.work@gmail.com**  
😄 Pronouns: He/Him  
⚡ Fun fact: I once built a promo app that handled **12K+ API requests in a single weekend** with 99.9% uptime 🚀  

---
## 🚀 Featured Projects  

### 🎫 High-Concurrency Ticketing System  
- Designed and implemented a **high-concurrency ticket booking platform**, supporting user registration, login, event browsing, seat selection, order creation, and payment.  
- **Database Sharding**: Adopted consistent hashing and modulo strategies to achieve horizontal partitioning, improving multi-dimensional query performance and boosting efficiency by **50%+**.  
- **Concurrency Control**: Implemented local locks, distributed locks, read-write locks, and fine-grained locking strategies; combined **Redis + Lua scripts** for atomic operations, improving throughput under peak load by **26%**.  
- **Caching Optimization**: Leveraged Redis data structures (hashes, sorted sets, lists) with Lua scripts, integrated **Caffeine** for in-memory caching, and optimized cache penetration & breakdown issues, significantly reducing DB load.  
- **Asynchronous Messaging**: Integrated **Kafka** to decouple order creation and event recording, ensuring system resilience against message loss and improving overall fault tolerance.  
- **Fault Tolerance & Resilience**: Adopted **Sentinel/Hystrix** for circuit breaking, rate limiting, and fallback mechanisms, guaranteeing high availability during extreme traffic spikes.  

**Tech Stack**:  
![Spring Boot](https://img.shields.io/badge/SpringBoot-%236DB33F.svg?style=flat&logo=springboot&logoColor=white)  ![Spring Cloud](https://img.shields.io/badge/SpringCloud-%23007ACC.svg?style=flat&logo=spring&logoColor=white)  ![MyBatis Plus](https://img.shields.io/badge/MyBatisPlus-%23FF7200.svg?style=flat&logo=java&logoColor=white)  ![Redis](https://img.shields.io/badge/Redis-%23DC382D.svg?style=flat&logo=redis&logoColor=white)  ![Caffeine](https://img.shields.io/badge/Caffeine-%233776AB.svg?style=flat&logo=coffeescript&logoColor=white)  ![Kafka](https://img.shields.io/badge/Kafka-%23000000.svg?style=flat&logo=apachekafka&logoColor=white)  ![Sentinel](https://img.shields.io/badge/Sentinel-%23007396.svg?style=flat&logo=alibabacloud&logoColor=white)  ![Hystrix](https://img.shields.io/badge/Hystrix-%23FF2D20.svg?style=flat&logo=java&logoColor=white)  ![Prometheus](https://img.shields.io/badge/Prometheus-%23E6522C.svg?style=flat&logo=prometheus&logoColor=white)  ![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=flat&logo=grafana&logoColor=white)  

### 🤖 LLM Inference API Platform (Real-Time Streaming)  
- Built a **real-time LLM inference platform** with FastAPI backend and vLLM engine, supporting **500+ concurrent users** and processing **2.5M tokens daily** with 99.7% uptime.  
- **Performance Optimization**: Improved token throughput by **55%** and reduced infrastructure costs by **40%** using **PagedAttention**, continuous batching, and load-aware admission control, achieving **p95 latency of 1.1s**.  
- **Observability**: Integrated **Prometheus** for metrics (TTFR, tokens/sec, queue length), **Grafana** dashboards for real-time visualization, and **OpenTelemetry** for distributed tracing across gateway and inference server.  
- **Resilience & Reliability**: Deployed circuit breakers, idempotency keys, automated health checks, and **load testing with Locust**, documented with **SLOs & runbook**.  
- **Deployment**: Containerized with Docker Compose and deployed on **AWS EC2**, orchestrating multi-container architecture with zero downtime.  

**Tech Stack**:  
![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=flat&logo=python&logoColor=white)  ![FastAPI](https://img.shields.io/badge/FastAPI-%23009688.svg?style=flat&logo=fastapi&logoColor=white)  ![vLLM](https://img.shields.io/badge/vLLM-%23000000.svg?style=flat&logo=openaigym&logoColor=white)   ![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=flat&logo=docker&logoColor=white)  ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazonaws&logoColor=white)  ![Prometheus](https://img.shields.io/badge/Prometheus-%23E6522C.svg?style=flat&logo=prometheus&logoColor=white)  ![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=flat&logo=grafana&logoColor=white)  ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-%23F5A97F.svg?style=flat&logo=opentelemetry&logoColor=white)  ![Locust](https://img.shields.io/badge/Locust-%2337D100.svg?style=flat&logo=python&logoColor=white)  

### 💰 FinTrack – Financial Tracking Web App  
- Built a **full-stack financial tracking app** with React/TypeScript frontend and Flask backend, serving **500+ active users**.  
- Designed PostgreSQL schema with indexed queries, handling **2K+ daily transactions** with sub-200ms response time.  
- Developed data visualization dashboard with Chart.js, showing monthly insights, income vs expenses, and category breakdown.  
- Deployed with **microservices architecture** on AWS EC2, PostgreSQL RDS, and Nginx reverse proxy, achieving **99.7% uptime**.  

**Tech Stack**:  
![React](https://img.shields.io/badge/React-%2361DAFB.svg?style=flat&logo=react&logoColor=black)  ![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white)  ![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=flat&logo=flask&logoColor=white)  ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23336791.svg?style=flat&logo=postgresql&logoColor=white)  ![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=flat&logo=docker&logoColor=white)  ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazonaws&logoColor=white)  ![Nginx](https://img.shields.io/badge/Nginx-%23009639.svg?style=flat&logo=nginx&logoColor=white)  


## 🛠️ Tech Stack

### 💻 Languages
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white)  ![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=flat&logo=javascript&logoColor=black)  ![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white)  ![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=flat&logo=python&logoColor=white)  ![SQL](https://img.shields.io/badge/SQL-%230074C1.svg?style=flat&logo=postgresql&logoColor=white)

### 🖼️ Frontend
![React](https://img.shields.io/badge/React-%2361DAFB.svg?style=flat&logo=react&logoColor=black)  ![Redux](https://img.shields.io/badge/Redux-%23764ABC.svg?style=flat&logo=redux&logoColor=white)  ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white)  ![Bootstrap](https://img.shields.io/badge/Bootstrap-%237952B3.svg?style=flat&logo=bootstrap&logoColor=white)

### ⚙️ Backend
![FastAPI](https://img.shields.io/badge/FastAPI-%23009688.svg?style=flat&logo=fastapi&logoColor=white)  ![Spring Boot](https://img.shields.io/badge/Spring_Boot-%236DB33F.svg?style=flat&logo=springboot&logoColor=white)  ![Express.js](https://img.shields.io/badge/Express.js-%23404d59.svg?style=flat&logo=express&logoColor=white)  ![vLLM](https://img.shields.io/badge/vLLM-%23000000.svg?style=flat&logo=openaigym&logoColor=white)

### ☁️ Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazonaws&logoColor=white)  ![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=flat&logo=docker&logoColor=white)  ![Linux](https://img.shields.io/badge/Linux-%23FCC624.svg?style=flat&logo=linux&logoColor=black)  ![Nginx](https://img.shields.io/badge/Nginx-%23009639.svg?style=flat&logo=nginx&logoColor=white)

---

## 📊 GitHub Stats

![Boyu's GitHub stats](https://github-readme-stats.vercel.app/api?username=Boyu-Qian&show_icons=true&theme=radical)  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Boyu-Qian&layout=compact&theme=radical)

---

⭐️ From [Boyu-Qian](https://github.com/Boyu-Qian)
  <div>&nbsp;</div>

  <!-- Snake Code Contribution Map 贪吃蛇代码贡献图 -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/sun0225SUN/sun0225SUN/profile-snake-contrib/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://cdn.jsdelivr.net/gh/sun0225SUN/sun0225SUN/profile-snake-contrib/github-contribution-grid-snake.svg" />
    <img alt="github-snake" src="https://cdn.jsdelivr.net/gh/sun0225SUN/sun0225SUN/profile-snake-contrib/github-contribution-grid-snake-dark.svg" />
  </picture>

</div>