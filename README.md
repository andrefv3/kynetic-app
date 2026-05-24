<p align="center">
  <img src="./public/assets/logo-kynetic.svg" width="160" alt="Kynetic Logo" />
</p>

<h1 align="center">Kynetic</h1>
<p align="center">
  <strong>The Intelligence Layer for High-Velocity Execution</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-19.2-20232A?style=flat-square&logo=react" />
  <img src="https://img.shields.io/badge/TypeScript-5.9-3178C6?style=flat-square&logo=typescript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4.2-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Vitest-4.1-6E9F18?style=flat-square&logo=vitest" />
  <img src="https://github.com/andrefv3/kynetic-app/actions/workflows/ci.yml/badge.svg" alt="Build Status" />
</p>

<p align="center">
  Kynetic is not just a task manager; it's a <strong>priority engine</strong>. 
  By synthesizing <i>Impact vs. Effort</i> metrics through a proprietary scoring algorithm, 
  Kynetic eliminates decision fatigue and focuses your cognitive load where it matters most.
</p>

<p align="center">
  <a href="https://kynetic-tasks.vercel.app/"><strong>🚀 Live Demo</strong></a>
</p>

---

## 📋 Overview

Kynetic provides a streamlined environment for organizing and tracking tasks efficiently. The application prioritizes clarity, responsiveness, and predictable behavior, ensuring a consistent experience across different usage scenarios.

The codebase is structured to support long-term evolution, making it easy to extend features, refactor components, and maintain high development velocity.

---

## 🏗️ Architecture & Engineering

The application is built on a **domain-driven, modular architecture** designed for high scalability and clear separation of concerns.

- **Frontend Core:** Utilizes an **Atomic Design** system to ensure component reusability and isolated testing. We leverage **Zustand** for performant global state sharding and **React Query** as the primary data-fetching layer, providing a seamless "local-first" experience with optimistic UI updates.
- **Backend Infrastructure:** A robust **NestJS** backend manages business logic, interacting with a **PostgreSQL** database through **Prisma ORM**. This setup ensures end-to-end type safety and efficient database queries.
- **Continuous Quality:** Every push is validated through a **CI/CD pipeline** (GitHub Actions), maintaining a rigorous standard of code quality with **~85% test coverage** via Vitest.

---

## 🛠️ Technology Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React 19 (Concurrent Mode), Tailwind CSS |
| **State** | Zustand (Store Sharding), React Query v5 |
| **Backend** | NestJS, Prisma ORM, PostgreSQL |
| **Quality** | Vitest, Testing Library, ESLint (Strict) |
---

## ⚡ Features

- Task creation, editing, and deletion  
- Responsive and accessible interface  
- Consistent state handling and UI feedback  
- Error and loading state management  
- Modular and reusable component system  

---

## 🚀 Getting Started

### Prerequisites
- **Node.js** v25+ (Latest features)
- **pnpm** or **npm** v11+

---

## 💻 Development

```bash
npm install
npm run dev
```

## 🧪 Testing & Quality
We maintain a high standard of code reliability through automated testing suites.

```bash
npm run test        # Unit & Integration
npm run test:ui     # Visual Test Runner
```
---
> **Coverage:** Currently maintaining **~85% test coverage** across core business logic, ensuring regression-free deployments.

## 🎨 Design Approach
The interface follows a **minimalist, intent-based design**. By stripping away unnecessary chrome, we maximize the focus on the task at hand. Every component is built for composability, ensuring that the application remains maintainable as features scale.

## 🔮 Roadmap
- [ ] **Kynetic AI Integration**: NLP for automatic task scoring.
- [ ] **Predictive Scheduling**: ML-driven focus block suggestions.
- [ ] **Real-time Sync**: Collaborative execution environments.

---

## 🔭 Future Direction

- Introduce more advanced state management patterns as the application grows in complexity  
- Strengthen accessibility compliance (a11y) to ensure a more inclusive user experience  
- Optimize rendering performance for larger datasets and more dynamic interactions  
- Expand functionality to support more complex task management workflows  

---

## 👤 Author
**Andrés Felipe Vega** – Full Stack Developer  
[GitHub](https://www.github.com/andrefv3) | [LinkedIn](https://www.linkedin.com/in/andrefv3)