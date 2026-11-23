# ubuntu-service-docs

[![GitHub Pages](https://img.shields.io/badge/docs-GitHub_Pages-sky.svg)](https://keshavsoft.github.io/ubuntu-service-docs/)
[![Ecosystem](https://img.shields.io/badge/family-8_repositories-orange.svg)](https://keshavsoft.github.io/ubuntu-service-docs/repos/)
[![Organization](https://img.shields.io/badge/org-KeshavSoft-purple.svg)](https://github.com/keshavsoft)

> Interactive documentation website, architectural showcase, and ecosystem hub for the **ubuntu-service** family.

---

## 🌐 Live GitHub Pages Portal

* **Hub / Overview:** [https://keshavsoft.github.io/ubuntu-service-docs/](https://keshavsoft.github.io/ubuntu-service-docs/)
* **All 8 Family Repositories & npm Links:** [https://keshavsoft.github.io/ubuntu-service-docs/repos/](https://keshavsoft.github.io/ubuntu-service-docs/repos/)
* **Detect Module Docs:** [https://keshavsoft.github.io/ubuntu-service-docs/detect/](https://keshavsoft.github.io/ubuntu-service-docs/detect/)
* **Restart Engine Docs:** [https://keshavsoft.github.io/ubuntu-service-docs/restart/](https://keshavsoft.github.io/ubuntu-service-docs/restart/)
* **CLI (us) Docs:** [https://keshavsoft.github.io/ubuntu-service-docs/service/](https://keshavsoft.github.io/ubuntu-service-docs/service/)
* **Evolution Story:** [https://keshavsoft.github.io/ubuntu-service-docs/story.html](https://keshavsoft.github.io/ubuntu-service-docs/story.html)

---

## 📦 The 8 Repositories in the ubuntu-service Family

| Repository | Version | Type | npm Package | GitHub Repository | Dedicated Docs |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **`ubuntu-service`** | `1.2.1` | Core CLI | [![npm](https://img.shields.io/badge/npm-ubuntu--service-red.svg)](https://www.npmjs.com/package/ubuntu-service) | [keshavsoft/ubuntu-service](https://github.com/keshavsoft/ubuntu-service) | [Docs: Service CLI](https://keshavsoft.github.io/ubuntu-service-docs/service/) |
| **`ubuntu-service-detect`** | `1.0.0` | Read Module | [![npm](https://img.shields.io/badge/npm-ubuntu--service--detect-blue.svg)](https://www.npmjs.com/package/ubuntu-service-detect) | [keshavsoft/ubuntu-service-detect](https://github.com/keshavsoft/ubuntu-service-detect) | [Docs: Detect Module](https://keshavsoft.github.io/ubuntu-service-docs/detect/) |
| **`ubuntu-service-restart`** | `1.0.0` | Lifecycle Module | [![npm](https://img.shields.io/badge/npm-ubuntu--service--restart-orange.svg)](https://www.npmjs.com/package/ubuntu-service-restart) | [keshavsoft/ubuntu-service-restart](https://github.com/keshavsoft/ubuntu-service-restart) | [Docs: Restart Engine](https://keshavsoft.github.io/ubuntu-service-docs/restart/) |
| **`ubuntu-services`** | `1.0.0` | Fleet Auditor | [![npm](https://img.shields.io/badge/npm-ubuntu--services-green.svg)](https://www.npmjs.com/package/ubuntu-services) | [keshavsoft/ubuntu-services](https://github.com/keshavsoft/ubuntu-services) | [Ecosystem Page](https://keshavsoft.github.io/ubuntu-service-docs/repos/) |
| **`ubuntu-service-port`** | `2.0.0` | Diagnostics | [![npm](https://img.shields.io/badge/npm-ubuntu--service--port-purple.svg)](https://www.npmjs.com/package/ubuntu-service-port) | [keshavsoft/ubuntu-service-port](https://github.com/keshavsoft/ubuntu-service-port) | [Ecosystem Page](https://keshavsoft.github.io/ubuntu-service-docs/repos/) |
| **`ubuntu-service-cli`** | `1.1.1` | Domain CLI | [![npm](https://img.shields.io/badge/npm-ubuntu--service--cli-blue.svg)](https://www.npmjs.com/package/ubuntu-service-cli) | [keshavsoft/ubuntu-service-cli](https://github.com/keshavsoft/ubuntu-service-cli) | [Ecosystem Page](https://keshavsoft.github.io/ubuntu-service-docs/repos/) |
| **`ubuntu-knowledge`** | `1.0.0` | Handbook | [![npm](https://img.shields.io/badge/npm-ubuntu--knowledge-amber.svg)](https://www.npmjs.com/package/ubuntu-knowledge) | [keshavsoft/ubuntu-knowledge](https://github.com/keshavsoft/ubuntu-knowledge) | [Ecosystem Page](https://keshavsoft.github.io/ubuntu-service-docs/repos/) |
| **`ubuntu-service-docs`** | `Active` | Portal | *Doc Portal* | [keshavsoft/ubuntu-service-docs](https://github.com/keshavsoft/ubuntu-service-docs) | [Live Website](https://keshavsoft.github.io/ubuntu-service-docs/) |

---

## 🎯 The Architecture & Operational Story

1. **Atomic Action (`ubuntu-service`):** Run `us restart` right after `git pull`. Zero memory, instantly detects matching systemd unit via `ubuntu-service-detect` and safely restarts via `ubuntu-service-restart`.
2. **Fleet Visibility (`ubuntu-services`):** Plural companion inspecting all services running across the entire Ubuntu VPS.
3. **Port Diagnostics (`ubuntu-service-port`):** Reverse lookups mapping network ports and sockets back to systemd services.
4. **Knowledge Standards (`ubuntu-knowledge`):** Shared conventions and templates for VPS Node.js systemd deployment.
