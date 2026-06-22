<div align="center">

### Hi 👋, I'm Andika Aryansyach

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=Developer+from+Depok%2C+West+Java;Currently+building+Daemon+Protocol;Tinkering+with+mesh+%26+offline-first+systems;Exploring+cryptography+%26+security+research)](https://git.io/typing-svg)

[![Profile Views](https://komarev.com/ghpvc/?username=0xAre&color=58a6ff&style=flat-square&label=Profile+Views)](https://github.com/0xAre)

[![Portfolio](https://img.shields.io/badge/Portfolio-0xAre.github.io-1a1a2e?style=for-the-badge)](https://0xare.github.io/0xAre/)
[![Email](https://img.shields.io/badge/Email-aryansyach4@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aryansyach4@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-@sartala-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/sartala)
[![Daemon Protocol](https://img.shields.io/badge/Daemon_Protocol-daemonprotocol.com-6C63FF?style=for-the-badge)](https://www.daemonprotocol.com)
[![IEEE](https://img.shields.io/badge/IEEE-SARX--128-00629B?style=for-the-badge&logo=ieee&logoColor=white)](https://ieeexplore.ieee.org/document/11324550)

</div>

---

A passionate developer from Depok, West Java, Indonesia — currently building **[Daemon Protocol](https://www.daemonprotocol.com)**, an onchain intel & AML compliance platform.

- 🎓 Studying at **Politeknik Siber dan Sandi Negara (Poltek SSN)** — National Cyber and Cryptography Polytechnic
- 🔭 Working on **[Caraka-SuperApp](https://github.com/0xAre/Caraka-SuperApp)** (Android mesh) and contributing to **[cakra-mesh](https://github.com/Fatihmaull/cakra-mesh)**
- 🔐 I enjoy tinkering across the stack — desktop (Tauri/Rust), Android (Kotlin), web (Next.js/Firebase), and cryptography
- 📄 Co-authored **SARX-128**, a lightweight sponge-based stream cipher — published at IEEE ICCED 2025
- 🧮 Currently exploring **lattice-based RSA cryptanalysis** for my thesis — partial key exposure via Coppersmith's method (SageMath)
- 📫 Reach me at **aryansyach4@gmail.com**

---

## What I Build

### SaaS & Web

| Project | Description | Stack |
|---------|-------------|-------|
| [**RunIT**](https://github.com/0xAre/RunIT) | AI-native event execution system. One brief becomes a dependency-mapped (DAG) master plan; 9 specialized agents auto-resolve venue, vendor, sponsor & permit tasks with confidence scores, an AI engine stress-tests crisis scenarios, and the whole operation is run from a real-time mission-control dashboard. | Next.js 16, Gemini, Firebase, TypeScript |
| **JuraganApp Pro** | POS & inventory management SaaS for small-to-medium businesses — sales, stock, and reporting dashboards *(private repo)*. | React 19, Firebase, Vite, Recharts |
| [**CryptoSuite**](https://github.com/0xAre/CryptoSuite) | Browser-based cryptography & number-theory calculator — modular arithmetic, prime tools, group theory, hash functions, and classical ciphers, running **100% client-side** (no server, no data leaves the browser). | React 19, TypeScript, Vite |

### Desktop

| Project | Description | Stack |
|---------|-------------|-------|
| [**caraka-dekstop**](https://github.com/0xAre/caraka-dekstop) | Offline-first secure mesh messenger implementing the custom **CLAMP** protocol: **Ascon-AEAD128** E2E encryption (NIST SP 800-232), **X25519 ECDH** for forward secrecy, multi-hop relay, UDP auto peer-discovery, and replay protection — no central server, no internet. | Tauri v2, Rust, cross-platform |

### Android & Mesh

| Project | Description | Stack |
|---------|-------------|-------|
| [**CARAKA**](https://github.com/Fatihmaull/cakra-mesh) | Android WiFi-Direct mesh for disaster response — nearby devices discover, receive, and relay messages with no central server, SOS broadcast, authority roles, encrypted **SQLCipher** storage, and QR identity. Built for WRECK-IT 7.0. *(Upstream: [cakra-mesh](https://github.com/Fatihmaull/cakra-mesh); my fork: [Caraka-SuperApp](https://github.com/0xAre/Caraka-SuperApp).)* | Kotlin, Jetpack Compose, WiFi Direct, SQLCipher |

### Security & Research

| Project | Description | Stack |
|---------|-------------|-------|
| [**SARX-128**](https://github.com/0xAre/SARX-128) | Lightweight sponge-based stream cipher using **Speck128** as its internal permutation — designed for resource-constrained devices. Published at **IEEE ICCED 2025**. | C, cryptography |
| [**pke-common-prime-rsa**](https://github.com/0xAre/pke-common-prime-rsa) | Lattice-based **partial key exposure** attacks on **Common Prime RSA** via Coppersmith's method (Jochemsz–May) with LLL/BKZ. Thesis cryptanalysis work. | SageMath, fpylll |
| [**pke-rsa-additive-blinding**](https://github.com/0xAre/pke-rsa-additive-blinding) | PKE attack on RSA with **additive exponent blinding** from combined MSB–LSB leakage — key finding: blinded-exponent LSBs are the more critical bits to protect. | SageMath, fpylll |
| [**Daemon Protocol / DAEMON**](https://github.com/daemon-blockint-tech/DAEMON) | Decision-intelligence platform for AML & crypto investigations — data fusion, entity resolution, graph analytics, case management, and workflow orchestration in one polyglot monorepo. | Go, Rust, NestJS, TypeScript |
| [**fpylll**](https://github.com/0xAre/fpylll) | Python/Cython bindings for **fplll** lattice reduction — the lattice engine behind the RSA cryptanalysis work above. | Cython, Python |

---

## Open Source Contributions

| Repository | Role | Highlights |
|------------|------|------------|
| [**daemon-blockint-tech/DAEMON**](https://github.com/daemon-blockint-tech/DAEMON) | Contributor | Intel platform phases, NestJS gateway, Go Tor proxy & darkweb monitor, ontology security tests |
| [**Fatihmaull/cakra-mesh**](https://github.com/Fatihmaull/cakra-mesh) | Contributor | Peer-discovery session, animated radar overlay UI, WiFi Direct timeout/retry, unit coverage |

---

## Research & Publications

### SARX-128: A Lightweight Sponge-Based Stream Cipher with Speck Block Cipher

Published at the **11th International Conference on Computing, Engineering and Design (ICCED), 2025**.

**Authors:** Andika Aryansyach Fauzan, Sevinanda Diva Ananta Ilmi, Santi Indarjani

| Resource | Link |
|----------|------|
| IEEE Xplore | [ieeexplore.ieee.org/document/11324550](https://ieeexplore.ieee.org/document/11324550) |
| DOI | [10.1109/ICCED68324.2025.11324550](https://doi.org/10.1109/ICCED68324.2025.11324550) |
| Implementation & paper | [github.com/0xAre/SARX-128](https://github.com/0xAre/SARX-128) |

---

<div align="center">

### Connect with me:

[![GitHub](https://img.shields.io/badge/GitHub-0xAre-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/0xAre)
[![Portfolio](https://img.shields.io/badge/Portfolio-0xAre-1a1a2e?style=for-the-badge&logo=google-chrome&logoColor=white)](https://0xare.github.io/0xAre/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aryansyach4@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-@sartala-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/sartala)
[![Daemon Protocol](https://img.shields.io/badge/Daemon_Protocol-daemonprotocol.com-6C63FF?style=for-the-badge)](https://www.daemonprotocol.com)

### Skills:

[![My Skills](https://skillicons.dev/icons?i=kotlin,android,rust,c,typescript,react,nextjs,firebase,tauri,git,linux,vite,python,nestjs&perline=7)](https://skillicons.dev)

### GitHub Metrics:

<img src="./github-metrics.svg" alt="GitHub metrics — languages, activity, and contributions across owned, fork, and organization repositories" />

</div>

---

<div align="center">

*Still learning, still building — one commit at a time.*

</div>

