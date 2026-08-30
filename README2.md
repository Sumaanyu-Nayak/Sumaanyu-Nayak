<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:0d1117,100:00f7ff&height=120&section=header&text=SUMAANYU%20NAYAK&fontSize=42&fontColor=00f7ff&fontAlignY=65&animation=fadeIn" />

<br/>


██████╗  ██████╗ ██████╗  ██████╗ ████████╗██╗ ██████╗███████╗        ██╗     ██████╗ ██████╗ ██████╗ ███████╗██████╗ 
██╔══██╗██╔═══██╗██╔══██╗██╔═══██╗╚══██╔══╝██║██╔════╝██╔════╝       ██╔╝    ██╔════╝██╔═══██╗██╔══██╗██╔════╝██╔══██╗
██████╔╝██║   ██║██████╔╝██║   ██║   ██║   ██║██║     ███████╗      ██╔╝     ██║     ██║   ██║██║  ██║█████╗  ██████╔╝
██╔══██╗██║   ██║██╔══██╗██║   ██║   ██║   ██║██║     ╚════██║     ██╔╝      ██║     ██║   ██║██║  ██║██╔══╝  ██╔══██╗
██║  ██║╚██████╔╝██████╔╝╚██████╔╝   ██║   ██║╚██████╗███████║    ██╔╝       ╚██████╗╚██████╔╝██████╔╝███████╗██║  ██║
╚═╝  ╚═╝ ╚═════╝ ╚═════╝  ╚═════╝    ╚═╝   ╚═╝ ╚═════╝╚══════╝    ╚═╝         ╚═════╝ ╚═════╝ ╚═════╝ ╚══════╝╚═╝  ╚═╝



<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=2600&pause=800&color=00F7FF&center=true&vCenter=true&width=900&lines=I+build+robots+that+walk+on+18+servos.;I+run+my+own+3-node+bare-metal+cluster.;I+debug+at+the+packet+level.;I+ship+to+production.;IEEE+published+%40+20.;DRDO+%C3%97+2.+AIT+%E2%80%9827." />

<br/>

<a href="https://www.sumaanyu.in"><img src="https://img.shields.io/badge/PORTFOLIO-sumaanyu.in-00f7ff?style=for-the-badge&logo=firefox&logoColor=black&labelColor=00f7ff"/></a>
<a href="https://linkedin.com/in/sumaanyu-nayak-a31a14243/"><img src="https://img.shields.io/badge/LINKEDIN-CONNECT-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:nayaksumaanyu@gmail.com"><img src="https://img.shields.io/badge/EMAIL-REACH_OUT-ff00ff?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=Sumaanyu-Nayak&label=PROFILE+VIEWS&color=00f7ff&style=for-the-badge"/>

</div>

<details>
<summary><strong>💻 `&gt; whoami` — About Me</strong></summary>

> whoami

name:         Sumaanyu Nayak
location:     Pune, Maharashtra, India
degree:       B.E. Computer Engineering — AIT Pune (2027)
cgpa:         8.21 / 10
internships:  DRDO R&DE Engineers × 2
publication:  IEEE ISED-2025 — Autonomous Hexapod Robotics
homelab:      3-node Proxmox cluster (i5-9th gen × 3, 48GB RAM total)
network:      3-router mesh @ 3ms internal latency
robot:        Shatpadi — 18-DOF hexapod I designed, wired, and programmed
leetcode:     300+ problems solved
codeforces:   Pupil
currently:    Building machines that survive the real world

I'm not the kind of engineer who only lives in the browser.

My workbench has a soldering iron on one side and a terminal on the other.

I've debugged a coordinate frame mismatch between HoloLens and ROS at 3am.
I've tuned PID gait parameters on a hexapod that refused to walk straight.
I've traced a network issue to a misconfigured DHCP lease at the router level.
I've written a Next.js service that wakes up every few seconds, scrapes a portal, and fires a WhatsApp alert to 1,000+ students — and then made it a systemd unit so it survives reboots.

I like owning the whole system. From PCB to API. From ROS to React. From kernel to cloud.

</details>
---

<details>
<summary><strong>🤖 `&gt; cat /proc/shatpadi` — Shatpadi / Flagship Build</strong></summary>

> cat /proc/shatpadi — my flagship build

Shatpadi (Sanskrit: षट्पदी — one with six feet)

┌─────────────────────────────────────────────────────────────────┐
│                    SHATPADI — 18-DOF HEXAPOD                    │
├──────────────────────┬──────────────────────────────────────────┤
│  DEGREES OF FREEDOM  │  18  (3 per leg × 6 legs)                │
│  ACTUATORS           │  18× MG995 Servos                        │
│  SERVO DRIVERS       │  32 ch servo driver                      │
│  MAIN COMPUTE        │  Raspberry Pi 5 (8GB)                    │
│  SENSORS             │  BN880 GPS · Lidar                       │
│  COMMS               │  LoRa Comm                               │
│  SOFTWARE            │  ROS · Analytical IK · Tripod/Ripple     │
│                      │  Body-pose stabilisation · Nav stack     │
│  PUBLICATION         │  IEEE ISED-2025, Raipur ✓                │
└──────────────────────┴──────────────────────────────────────────┘

Implemented from scratch:
Inverse Kinematics → Gait Generation → Body Pose Control → Sensor Fusion → Autonomous Navigation

📄 "Autonomous Hexapod Robot Development for Search, Rescue, and Surveillance Operations"
13th IEEE ISED-2025, Raipur

</details>
---

<details>
<summary><strong>🖥️ `&gt; df -h /homelab` — Homelab Infrastructure</strong></summary>

> df -h /homelab — my infrastructure

┌──────────────────────────────────────────────────────────────┐
│                    HOMELAB ARCHITECTURE                      │
├───────────────────────┬──────────────────────────────────────┤
│  CLUSTER              │  3× Lenovo Mini PC                   │
│  HYPERVISOR           │  Proxmox VE (bare metal)             │
│  WORKLOADS            │  VMs · LXC containers · 10+ services │
├───────────────────────┼──────────────────────────────────────┤
│  ALWAYS-ON HOST       │  Ubuntu Server (repurposed laptop)   │
│  SERVICE MGMT         │  systemd · cron · watchdog timers    │
│  SELF-HOSTED          │  Gitea · Home Automation · Monitoring│
├───────────────────────┼──────────────────────────────────────┤
│  NETWORK              │  3-router mesh (seamless roaming)    │
│  INTERNAL LATENCY     │  3ms ping                            │
│  CONFIG               │  DNS · DHCP · VLAN · Firewall · SSH │
│  UPTIME TARGET        │  99.5%+ across all services          │
└───────────────────────┴──────────────────────────────────────┘

I don't use other people's cloud for things I can run better myself.

</details>
---

<details>
<summary><strong>🚀 `&gt; ls -la /projects` — Projects</strong></summary>

> ls -la /projects

📡  College Placement Notifier

Built because students were missing placement announcements. Deployed because it works.

Next.js scheduled API routes + MongoDB subscription store

Fires real-time alerts to 1,000+ students via WhatsApp and Telegram webhooks

99.9% delivery rate — deduplication, exponential-backoff retry, failure alerts built in

Running 24/7 as a Linux systemd service. Zero babysitting.

</details>
---

🤖  HoloLens × ROS Robot-Following System

Mixed reality meets autonomous navigation. Built at DRDO.

HoloLens + Unity spatial tracking → ROS navigation pipeline on Linux

Bidirectional communication via spatial anchors

Resolved Unity ↔ ROS coordinate frame mismatch → sub-centimetre positional accuracy

Debugged across the full stack: tracking, network latency, robot response

🌐  VoyageCraft — AI Travel Platform

AI itinerary generation. 1,000+ destinations. Actually containerised.

FastAPI · PostgreSQL · Redis · Docker microservices + GraphQL API

OpenAI GPT for personalised itinerary generation

Caching strategy cut API latency by 40%

🏫  HelpDesk EDU

College complaint management. Built it, deployed it, people use it.

Next.js · TypeScript · MongoDB — serving 29+ campus services

1,000+ concurrent users · 99.9% uptime · automated CI/CD on Vercel

Passwordless auth · JWT APIs · real-time priority queuing

🛒  RetailRadar

Local store discovery platform. Multi-tenant. Fast.

Next.js 15 · MongoDB · TypeScript — geolocation filters, admin dashboards

50ms average API response via query optimisation and indexing

<details>
<summary><strong>🧰 `&gt; lscpu` — Tech Stack</strong></summary>

> lscpu — tech stack

<div align="center">

SYSTEMS & INFRASTRUCTURE







ROBOTICS






LANGUAGES









FULL-STACK









AI / ML






</div>

</details>
---

<details>
<summary><strong>⚡ `&gt; uptime` — Competitive Programming</strong></summary>

> uptime — competitive programming

LeetCode    ████████████████████░░░░  300+ problems solved
Codeforces  ████████████░░░░░░░░░░░░  Pupil rank
Focus areas: Arrays · Graphs · DP · Trees · Sliding Window · Binary Search

</details>
---

<details>
<summary><strong>🏆 `&gt; dmesg | grep achievements` — Achievements</strong></summary>

> dmesg | grep achievements

[    0.001] IIT Techfest Zonal Robotics          — 1st Place  🥇
[    0.002] Line Follower Robotics, BITS Goa      — 2nd Place  🥈
[    0.003] CampK12 Hackathon (Nationwide)        — Top 5      🏆
[    0.004] IEEE ISED-2025, Raipur                — Published  📄
[    0.005] DRDO R&DE Engineers                   — Intern ×2  🔬
[    0.006] R&D Club — Core Leader                — 10+ mentored
[    0.007] Hardware & Innovation Cell            — Key Member

</details>
---

<details>
<summary><strong>🧠 `&gt; cat /etc/philosophy` — Engineering Philosophy</strong></summary>

> cat /etc/philosophy

Make it work.
Make it survive failure.
Make it observable.
Make it boring to operate.
Then move on to the next hard problem.

I'm most interested in the systems other people don't want to think about —
the middleware, the watchdog, the retry logic, the thing that keeps running
when the happy path breaks.

Good engineering starts where the happy path ends.

</details>
---

<details>
<summary><strong>📊 `&gt; htop` — GitHub Stats</strong></summary>

> htop — github stats

<div align="center">
<!--
<img height="165" src="https://github-readme-stats.vercel.app/api?username=Sumaanyu-Nayak&show_icons=true&theme=transparent&hide_border=true&title_color=00F7FF&icon_color=ff00ff&text_color=FFFFFF&bg_color=00000000&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sumaanyu-Nayak&layout=compact&theme=transparent&hide_border=true&title_color=00F7FF&text_color=FFFFFF&bg_color=00000000&langs_count=8" />
-->
<br/><br/>

<img src="https://streak-stats.demolab.com?user=Sumaanyu-Nayak&theme=dark&hide_border=true&background=00000000&ring=00F7FF&fire=ff00ff&currStreakLabel=00F7FF&sideLabels=FFFFFF" />

<br/><br/>

<!--
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Sumaanyu-Nayak&bg_color=0d1117&color=00F7FF&line=ff00ff&point=FFFFFF&area=true&hide_border=true" />
-->

</div>

</details>
---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00f7ff,100:0d1117&height=80&section=footer&fontSize=14&fontColor=ffffff&animation=fadeIn" />

<p align="center">
  <img src="https://raw.githubusercontent.com/Sumaanyu-Nayak/Sumaanyu-Nayak/output/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake" />
</p>

Hardware is the body.   Software is the nervous system.
AI is the intelligence.   Engineering connects them.

> _

</div>
