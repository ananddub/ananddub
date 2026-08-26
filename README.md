<div align="center">

# 👋 Hi, I'm Anand Dubey

<p align="center">
  <a href="https://github.com/ananddub">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=800&lines=Software+Engineer+%E2%80%94+Mobile+%26+Distributed+Systems;React+Native+%7C+Flutter+%7C+Kotlin+Jetpack+Compose;High-Concurrency+Backends+in+Go+%26+Rust;Real-Time+gRPC%2C+UDP+Voice+Sockets+%26+LiveKit+WebRTC;Production+Mobile+Apps+Deployed+to+Google+Play+Store" alt="Typing Banner" />
  </a>
</p>

<p align="center">
  <a href="mailto:duanand6@gmail.com"><img src="https://img.shields.io/badge/Email-duanand6%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/ananddub"><img src="https://img.shields.io/badge/GitHub-ananddub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Location-India-0A66C2?style=for-the-badge&logo=googlemaps&logoColor=white" />
</p>

</div>

---

## 🚀 About Me

I'm a **Software Engineer** focused on building **high-performance mobile applications**, **distributed backend systems**, and **real-time communication engines**.

I enjoy solving complex engineering challenges—from designing high-concurrency real-time microservices with **Go** and **Rust** to crafting fluid 60 FPS mobile user experiences across **React Native**, **Flutter**, and native Android (**Kotlin / Jetpack Compose**). I have end-to-end experience taking platforms from architectural design to **Google Play Store production releases**.

### 💡 Core Engineering Focus:
- 📱 **Mobile Architecture:** Offline-first caching (MMKV, Room DB), fluid UI animations, state hydration, and multi-platform consistency.
- ⚡ **Backend & Distributed Systems:** High-throughput microservices, sub-millisecond gRPC streaming, dedicated UDP socket voice engines, and distributed pub/sub.
- 🗄️ **Data & Infrastructure:** Scalable persistence with ScyllaDB, TimescaleDB, PostgreSQL, Redis, Redpanda (Kafka), and containerized deployments via Docker & Nix.

---

## 🛠 Skills & Technical Arsenal

<div align="center">
  <img src="https://skillicons.dev/icons?i=go,rust,kotlin,dart,ts,js,python,c,cpp,bash,react,flutter,androidstudio,redux,tailwind,nextjs,grpc,docker,kubernetes,nginx,redis,postgres,mongodb,firebase,appwrite,linux,nix,git,neovim&perline=15" alt="Tech Stack Matrix" />
</div>

<br>

- **Programming Languages:** `Go (Golang)`, `Rust`, `Kotlin`, `Dart`, `TypeScript`, `JavaScript`, `Python`, `C`, `C++`, `Java`, `Bash`
- **Mobile Development:** `React Native`, `Flutter`, `Jetpack Compose (Android Native)`, `Riverpod 2.0`, `Zustand`, `Redux Toolkit`, `Routemaster`, `MMKV`, `Room DB`, `LiveKit WebRTC`, `RN Track Player`
- **Backend & Systems:** `gRPC & Protocol Buffers`, `UDP Voice Protocol`, `Tokio / SQLx (Rust)`, `Fiber / Gin (Go)`, `FastAPI`, `WebSockets`, `OpenFGA (Fine-Grained Permissions)`, `WireGuard Tunnels`
- **Databases & Streaming:** `ScyllaDB (Cassandra)`, `TimescaleDB`, `PostgreSQL`, `Redis Pub/Sub`, `Redpanda (Kafka)`, `MongoDB (GeoJSON)`, `MinIO S3`, `Cloud Firestore`
- **DevOps, Cloud & Tooling:** `Docker & Docker Compose`, `Kubernetes`, `Nix Flakes / NixOS`, `Linux Systems`, `Testcontainers (Integration TDD)`, `GitHub Actions CI/CD`, `Grafana & Prometheus`

---

## 🎯 Featured Engineering Systems

<table>
  <tr>
    <th width="35%">System</th>
    <th width="65%">Architectural Highlights & Tech Stack</th>
  </tr>
  <tr>
    <td>
      <b><a href="https://github.com/ananddub/incord">🎧 Incord</a></b><br>
      <i>Full-Stack Real-Time Voice & Chat Platform</i>
    </td>
    <td>
      • <b>Dual-Transport Backend:</b> Go gRPC server for transactional state + dedicated UDP server for low-latency voice packet processing.<br>
      • <b>Distributed Persistence:</b> ScyllaDB (message history), TimescaleDB (telemetry), Redis (presence), OpenFGA (RBAC), and 171 automated Testcontainers tests.<br>
      • <b>Native Android Client:</b> 17+ screens in Kotlin Jetpack Compose, LiveKit WebRTC, and Room DB offline caching.<br>
      <code>Go</code> • <code>gRPC</code> • <code>UDP</code> • <code>ScyllaDB</code> • <code>Kotlin</code> • <code>Jetpack Compose</code> • <code>LiveKit</code>
    </td>
  </tr>
  <tr>
    <td>
      <b><a href="https://github.com/ananddub/openoxide">🦀 OpenOxide</a></b><br>
      <i>High-Performance Systems & Server Infrastructure Engine</i>
    </td>
    <td>
      • <b>Systems Engine in Rust:</b> Zero-overhead memory safety with compile-time type-checked SQLx persistence.<br>
      • <b>Host & Infrastructure:</b> Docker socket daemon management, automated WireGuard peer provisioning, and host-key pinned SSH clients.<br>
      <code>Rust</code> • <code>TypeScript</code> • <code>SQLx</code> • <code>SQLite</code> • <code>Docker API</code> • <code>WireGuard</code>
    </td>
  </tr>
  <tr>
    <td>
      <b><a href="https://github.com/ananddub/soundpulse">🎵 SoundPulse</a></b><br>
      <i>High-Performance Audio Streaming Mobile Application</i>
    </td>
    <td>
      • <b>Audio Engine:</b> Background audio playback, lock-screen controls, and notification triggers via React Native Track Player.<br>
      • <b>State & Caching:</b> Lightweight Zustand state store with MMKV local caching for instant state hydration and dynamic artwork palette extraction.<br>
      <code>React Native</code> • <code>TypeScript</code> • <code>Zustand</code> • <code>RN Track Player</code> • <code>MMKV</code>
    </td>
  </tr>
  <tr>
    <td>
      <b><a href="https://github.com/ananddub/ludoarena">🎲 LudoArena</a></b><br>
      <i>Real-Time 4-Player Multiplayer Board Game Engine</i>
    </td>
    <td>
      • <b>Game State Machine:</b> Custom coordinate matrix mapping (<code>PlotData</code>), collision rules, safe-spot logic, and automated turn rotation.<br>
      • <b>Interactive UI:</b> Redux Toolkit state slice, 60 FPS 3D dice roll animations, sound effect triggers (SFX), and celebration dialogs.<br>
      <code>React Native</code> • <code>Redux Toolkit</code> • <code>Animated API</code> • <code>Lottie</code> • <code>Sound Utility</code>
    </td>
  </tr>
  <tr>
    <td>
      <b><a href="https://github.com/ananddub/threadnest">💬 ThreadNest</a></b><br>
      <i>Responsive Cross-Platform Community Discussion App</i>
    </td>
    <td>
      • <b>Cross-Platform:</b> Adaptive responsive layout supporting Android, iOS, and Desktop Web via Flutter.<br>
      • <b>Community Mechanics:</b> Subreddit management, Google/Guest authentication, upvote/downvote scoring, Karma calculation, and Routemaster navigation.<br>
      <code>Flutter</code> • <code>Dart</code> • <code>Firebase Auth</code> • <code>Cloud Firestore</code> • <code>Routemaster</code>
    </td>
  </tr>
  <tr>
    <td>
      <b>🎓 Equality Through Education (ETE)</b><br>
      <i>Production Mobile Platform (Google Play Store)</i>
    </td>
    <td>
      • <b>Published Production App:</b> Centralized educational curriculum platform deployed on Google Play Store serving students across institutions.<br>
      • <b>PDF Engine:</b> In-app PDF reader with background download pipeline, local file caching, role-based auth, and Firebase cloud sync.<br>
      <code>Flutter</code> • <code>Dart</code> • <code>Firebase</code> • <code>Cloud Firestore</code> • <code>Google Play Store Live</code>
    </td>
  </tr>
</table>

---

## 📊 GitHub Analytics & Activity

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ananddub&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

<br>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ananddub&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Anand's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ananddub&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>

---

<div align="center">
  <sub>⚡ <i>"Turning complex systems and architecture into high-performance, elegant software."</i> ⚡</sub>
</div>
