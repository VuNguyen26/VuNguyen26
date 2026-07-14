<!-- =========================================================
     VU NGUYEN — GITHUB PROFILE README
========================================================= -->

<div align="center">

<img
  width="100%"
  src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,45:1D4ED8,75:0284C7,100:06B6D4&height=200&section=header&text=Vu%20Nguyen&fontSize=50&fontColor=FFFFFF&animation=fadeIn&fontAlignY=36&desc=Backend%20%2F%20Full-stack%20Developer&descSize=19&descAlignY=58"
/>

<img
  src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=3000&pause=900&color=38BDF8&center=true&vCenter=true&width=780&height=50&lines=Building+reliable+backend+platforms+and+APIs;Focused+on+security%2C+observability%2C+and+maintainability;Creator+of+the+PulseGate+API+Management+Platform"
  alt="Typing introduction"
/>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit_Website-0EA5E9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://vunguyen26.github.io)
[![PulseGate](https://img.shields.io/badge/PulseGate-Explore_Project-2563EB?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VuNguyen26/pulsegate)
[![Release](https://img.shields.io/badge/Release-v2.0.0-16A34A?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/VuNguyen26/pulsegate/releases/tag/v2.0.0)

</div>

---

## About Me

I am a **Backend / Full-stack Developer** focused on building reliable APIs, backend platforms, and developer-facing tools.

\- Building **PulseGate**, a product-oriented API Gateway and API Management platform.<br/>
\- Primary stack: **TypeScript, Node.js, Fastify, PostgreSQL, Redis, and Docker**.<br/>
\- Also building backend systems with **Java and Spring Boot**.<br/>
\- Interested in API security, distributed systems, observability, and platform engineering.<br/>
\- I value clean architecture, automated testing, reproducible delivery, and clear documentation.

---

## Engineering Focus

<table>
<tr>
<td width="50%" valign="top">

### API Platforms

Designing secure API gateways, routing systems, authentication boundaries, rate limits, caching, retries, and traffic-management policies.

</td>
<td width="50%" valign="top">

### Backend Architecture

Building maintainable services with clear contracts, modular components, persistent storage, runtime validation, and failure-safe behavior.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Security & Reliability

Applying secure-by-default access control, validation, defensive error handling, runtime guardrails, and production-minded operational practices.

</td>
<td width="50%" valign="top">

### Observability & Delivery

Working with metrics, traces, logs, dashboards, containers, Kubernetes, automated tests, release validation, and deployment documentation.

</td>
</tr>
</table>

---

## Core Stack

### Backend

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-111827?style=flat-square&logo=fastify&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)

### Data & Infrastructure

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### Observability & Quality

![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-7C3AED?style=flat-square&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)

---

## Featured Project — PulseGate

<div align="center">

[![Version](https://img.shields.io/badge/Product-v2.0.0-2563EB?style=flat-square)](https://github.com/VuNguyen26/pulsegate/releases/tag/v2.0.0)
![TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-20+-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Status](https://img.shields.io/badge/Status-Released-16A34A?style=flat-square)

</div>

### API Gateway & API Management Platform

**PulseGate** is a product-oriented platform built to demonstrate secure API routing, traffic management, analytics, observability, operator workflows, and production-minded software delivery.

### Platform Highlights

\- API-key and JWT authentication<br/>
\- Administrative authorization boundaries<br/>
\- Rate limiting and response caching<br/>
\- Timeout and retry policies<br/>
\- Request and response transformations<br/>
\- Dynamic runtime route registry<br/>
\- Host-based and weighted upstream routing<br/>
\- PostgreSQL and Redis integration<br/>
\- Usage, rejection, and rollup analytics<br/>
\- Admin Dashboard and Developer Portal<br/>
\- Prometheus and Grafana metrics<br/>
\- OpenTelemetry distributed tracing<br/>
\- Loki structured logging<br/>
\- Docker Compose and Kubernetes deployment<br/>
\- End-to-end demo and bounded k6 validation<br/>
\- Automated testing and release-readiness workflows

### Architecture

```text
Clients
   │
   ▼
PulseGate API Gateway
   ├── Authentication and authorization
   ├── Rate limiting and caching
   ├── Routing and traffic policies
   ├── Runtime route registry
   ├── Usage and rejection analytics
   └── Metrics, traces, and structured logs
          │
          ▼
   Downstream Services

Platform Interfaces
   ├── Admin Dashboard
   └── Developer Portal

Infrastructure
   ├── PostgreSQL
   ├── Redis
   ├── Prometheus
   ├── Grafana
   ├── OpenTelemetry
   ├── Loki
   └── Kubernetes
```

<div align="center">

[![Repository](https://img.shields.io/badge/Repository-Explore_PulseGate-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VuNguyen26/pulsegate)
[![Release](https://img.shields.io/badge/Release-View_v2.0.0-16A34A?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/VuNguyen26/pulsegate/releases/tag/v2.0.0)
[![Portfolio](https://img.shields.io/badge/Portfolio-Project_Overview-0284C7?style=for-the-badge&logo=googlechrome&logoColor=white)](https://vunguyen26.github.io)

</div>

---

## Development Principles

```text
Audit before patching
Small and reviewable checkpoints
Secure and fail-closed defaults
Tests before claims
Runtime evidence before documentation
Reproducible builds and releases
Clear architecture and operational documentation
```

---

## GitHub Activity

<div align="center">

<strong>Contribution Streak</strong>
<br/>

<img
  height="190"
  src="https://streak-stats.demolab.com/?user=VuNguyen26&theme=tokyonight&background=135%2C0D1117%2C161B22&border=30363D&stroke=30363D&ring=FF8A00&fire=FF2D20&currStreakNum=FFFFFF&sideNums=7AA2F7&currStreakLabel=FF8A00&sideLabels=A9B1D6&dates=73DACA&border_radius=12&card_height=190&disable_animations=false"
  alt="Vu Nguyen GitHub contribution streak"
/>

<br/>

<strong>Most Used Languages</strong>
<br/>

<img
  height="175"
  src="https://github-stats-extended.vercel.app/api/top-langs/?username=VuNguyen26&layout=compact&theme=tokyonight&hide_border=true"
  alt="Vu Nguyen most used languages"
/>

</div>

> Language statistics describe the public repositories in this profile and do not represent overall proficiency.

---

<div align="center">

### Build carefully. Validate honestly. Document clearly.

<img
  src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=2600&pause=800&color=38BDF8&center=true&vCenter=true&width=720&height=40&lines=Secure+by+default.;Observable+by+design.;Validated+before+release."
  alt="Engineering principles typing animation"
/>

<img
  width="100%"
  src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,35:0284C7,70:1D4ED8,100:0F172A&height=115&section=footer"
/>

</div>
