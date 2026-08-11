# Hi there 👋, I'm Mansi Maurya

### GSoC '26 Contributor @ Mifos Initiative (Apache Fineract) | Backend & Cloud Engineer

---

### 🚀 About Me

I'm a **software developer** who thinks of architecture as a design discipline — the same instinct I bring to the art I make outside of work.

Right now I'm a **Google Summer of Code 2026 contributor with the [Mifos Initiative](https://mifos.org/)**, working on the modularization of **[Apache Fineract](https://github.com/apache/fineract)** — the open-source core banking platform that powers financial inclusion for millions of underbanked people worldwide.

Before this, I spent **3 years as a Software Development Engineer at Standard Chartered Bank**, building Java/Spring Boot microservices that handled millions of real-time transactions. I hold an **MSc in Advanced Software Development from TU Dublin** and I'm an **AWS Certified Cloud Practitioner**, currently growing toward a cloud & DevOps engineering path.

---

### 🌍 GSoC 2026 — Fineract Modularization

Fineract is a large, mature monolith. My project is about carving clean module boundaries into it **without breaking a system banks actually run on** — using **Spring Modulith** for architecture enforcement and **event-driven patterns** for cross-module communication.

**What I've been shipping:**

- 🧱 **[FINERACT-2645](https://issues.apache.org/jira/browse/FINERACT-2645)** — Modulith architecture overview and boundary verification. Built and merged `AllModulesCrossFeatureBoundaryTest`, an automated ArchUnit-style guardrail that fails the build when a module reaches across a boundary it shouldn't. Regressions now get caught in CI instead of in review.
- 🔌 **[FINERACT-2646](https://issues.apache.org/jira/browse/FINERACT-2646)** — Decoupled `fineract-accounting` from `fineract-charge` using a **port/adapter pattern**, inverting the dependency so the accounting module depends on an abstraction it owns rather than on a concrete sibling module. Included eliminating N+1 queries and centralizing dependency versions through a BOM.
- 👥 **[FINERACT-2647](https://issues.apache.org/jira/browse/FINERACT-2647)** — Triaged 16 cross-feature violation packages around the client module into a decoupling strategy: safe relocations, read-interfaces lifted into core, event-based decoupling for cross-module writes, and shared enum/DTO moves.

**Mentors:** Aleksandar Vidakovic, Adam Saghy, Aman Mittal

Working in the open on a project this size has taught me as much about **review cycles, CI pipelines, and community collaboration** as it has about architecture — build failures spanning Error Prone, Spotless, SpotBugs and Gradle platform resolution are their own kind of curriculum.

---

### 💡 Also Working On

- ☁️ **Cloud & DevOps** — deepening Kubernetes, IaC, and CI/CD practice on top of my AWS certification
- 🧰 **Java libraries from scratch** — a pure-Java rate limiter with six interchangeable algorithms behind one interface (token bucket, leaky bucket, sliding window, and friends)
- 🤝 **Mentoring @ [Develop for Good](https://www.developforgood.org/)** — guiding student teams building software for nonprofits, most recently a volunteer respite-program platform for a caregiver coalition
- 🎨 **Design** — both the architectural kind and the visual kind

---

### 🛠️ Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Modulith](https://img.shields.io/badge/Spring%20Modulith-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)
![Vault](https://img.shields.io/badge/HashiCorp%20Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

---

### 🌱 What Drives Me

💭 Good architecture is invisible when it works and expensive when it doesn't — I like being on the side that makes it invisible.
🌍 Open source lets that work reach people it otherwise never would. Fineract is a good reminder of that.
📚 Always learning, in public, with the build logs to prove it.

---

### 📊 GitHub Stats

![Mansi's GitHub stats](https://github-readme-stats.vercel.app/api?username=mansi75&show_icons=true&theme=default&hide_border=true)

---

### 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mansi-maurya-639683183)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mansimaurya75@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mansi75)

---

⭐️ *"Code with purpose, build with passion, and always keep learning."*
