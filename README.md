<div align="center">

<img src="https://consensus.codes/icon.png" alt="Consensus" width="88" height="88" />

# Consensus

**Intelligent Learning Platform**

[![Live](https://img.shields.io/badge/Live-consensus.codes-E8001F?style=flat-square&logo=vercel&logoColor=white)](https://consensus.codes)
[![Status](https://img.shields.io/badge/Status-Production-0A7A3E?style=flat-square)](https://consensus.codes)
[![Stack](https://img.shields.io/badge/Stack-Next.js%20%7C%20Workers%20%7C%20D1-111111?style=flat-square)](https://consensus.codes)

[Website](https://consensus.codes) · [Courses](https://consensus.codes/courses) · [Sign up](https://consensus.codes/signup)

<img src="https://consensus.codes/consensus-social-2026.png" alt="Consensus social banner" width="680" />

</div>

---

## Overview

**Consensus** ([consensus.codes](https://consensus.codes)) is a production learning management system for interactive tech education.

Learners progress through structured courses, practice in hands-on labs, validate skills with exams, and earn shareable certificates.

> **Learn. Build. Reach Consensus.**

---

## Product

| Area | What it delivers |
| :--- | :--- |
| **Courses** | Modular lessons across Linux, Git, JS/React, Python, DevOps, System Design, and more |
| **Labs** | Hands-on environments to practice real workflows |
| **Exams** | Timed assessments and skill checks |
| **Certificates** | Completion credentials with public verification |
| **Learning paths** | Guided multi-course skill tracks |
| **AI assistant** | Course-aware help with credit-based usage |
| **Admin** | Content, enrollments, special access, orders, and operations |

---

## Architecture (high level)

```text
┌─────────────────────┐     ┌──────────────────────────┐
│  Next.js frontend   │────▶│  Cloudflare Workers API  │
│  consensus.codes    │     │  auth · courses · exams  │
└─────────────────────┘     │  labs · certificates     │
                            │  chat assistant          │
                            └────────────┬─────────────┘
                                         │
                    ┌────────────────────┼────────────────────┐
                    ▼                    ▼                    ▼
                 D1 SQLite              R2 files         Email routing
               (users, progress)     (assets / certs)   (@consensus.codes)
```

### Core technologies

- **Frontend:** Next.js, React, TypeScript, Tailwind CSS  
- **API / edge:** Cloudflare Workers  
- **Database:** Cloudflare D1  
- **Storage:** Cloudflare R2  
- **Email:** Domain routing + transactional delivery  
- **AI:** Home-tunnel RAG assistant with per-user credits  

---

## Featured learning tracks

| Track | Skills |
| :--- | :--- |
| Linux | Shell, systems, command-line fluency |
| Git & GitHub | Source control and collaboration |
| JavaScript + React | Modern web UI development |
| Python | Programming and practical automation |
| DevOps | Delivery, tooling, operations mindset |
| System Design | Designing scalable applications |

Full catalog: **https://consensus.codes/courses**

---

## Public endpoints

| URL | Purpose |
| :--- | :--- |
| https://consensus.codes | Homepage |
| https://consensus.codes/courses | Course catalog |
| https://consensus.codes/labs | Labs |
| https://consensus.codes/exams | Exams |
| https://consensus.codes/learning-paths | Learning paths |
| https://consensus.codes/certificates | Certificates |
| https://consensus.codes/verify-certificate | Certificate verification |
| https://consensus.codes/signup | Create account |

---

## Contact

| | |
| :--- | :--- |
| Website | https://consensus.codes |
| Admin | admin@consensus.codes |
| Manager | manager@consensus.codes |
| Organization | https://github.com/consensus-codes |

---

<div align="center">

**Consensus** · Intelligent Learning Platform

<sub>Production platform at [consensus.codes](https://consensus.codes)</sub>

</div>
