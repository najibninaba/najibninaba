# Hi, I'm Najib

📍 Singapore\
🏗️ Head of Platforms Engineering @ [AI Singapore](https://aisingapore.org)\
🌳 Creator of [Orchard](https://github.com/kapitan-ai/orchard), sovereign on-prem LLM orchestration

![Elixir](https://img.shields.io/badge/-Elixir-4B275F?style=flat-square&logo=elixir&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Apple Silicon](https://img.shields.io/badge/-Apple_Silicon_·_MLX-000000?style=flat-square&logo=apple&logoColor=white)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

I lead Platforms Engineering at AI Singapore. I joined in 2018 as one of the original four engineers. My team runs the hybrid infrastructure, GPU and HPC capacity, MLOps and data platforms for national AI programmes.

I started around 2000 with Linux HPC clusters in Singapore. Those habits still apply: get performance and efficiency while keeping results accurate, scale and automate so infrastructure and tools do the heavy lifting, and use embarrassingly parallel work and map-reduce as default patterns.

These days I build AI platforms and tools with AI agents, and I run the agents like a cluster. I plan, review and merge in Codex. RepoPrompt gives the agents context. The work fans out to Amp runners on our own hardware (Mac Studio, an H100 VM and W7900 workstations) and to Devin for remote compute. The agents help me spend less time writing code directly and more time guiding the work.

The problems are the same ones we solved on HPC clusters:

- Scheduling: a queue for builds and tests, with one heavy slot per machine.
- Isolation: a cheap git worktree for each agent, so parallel work stays separate.
- Accounting: a journal of the protected changes that agents make through MCP.

The main tools I build and contribute to are below.

## What I'm building

- 🌳 **[Orchard](https://github.com/kapitan-ai/orchard)** ![Stars](https://img.shields.io/github/stars/kapitan-ai/orchard?style=flat&color=gold) - You can think of Orchard as an OpenAI-compatible API that runs on a fleet of Apple Silicon Macs you control. It has an Elixir/OTP control plane, deny-by-default model grants for each Workspace, request tracing and MLX-LM workers. Postgres is the only infrastructure it needs. Apache-2.0, pre-release pilot. [Demo video](https://youtu.be/lChCSLT3ra8).
- 🌦️ **[Cuaca](https://cuaca.bijan.app)** - Weather and haze briefing for Singapore neighbourhoods. It uses only official data.gov.sg feeds: two-hour forecasts for all 47 areas, PSI and PM2.5, and a separate US AQI. It is an installable PWA on Cloudflare Workers.

## Contributing to

- 🧠 **[RepoPrompt CE](https://github.com/repoprompt/repoprompt-ce)** ![Stars](https://img.shields.io/github/stars/repoprompt/repoprompt-ce?style=flat&color=gold) - Native macOS app for context engineering, with an MCP CLI for AI coding agents. I contribute and review. My merged changes include Cursor ACP agent support ([#902](https://github.com/repoprompt/repoprompt-ce/pull/902)), Cursor Effort and Speed controls ([#960](https://github.com/repoprompt/repoprompt-ce/pull/960)), and Codex goals on by default ([#33](https://github.com/repoprompt/repoprompt-ce/pull/33)).
- 🍺 **[homebrew-repoprompt-ce](https://github.com/repoprompt/homebrew-repoprompt-ce)** - I maintain the Homebrew cask. Install with `brew tap repoprompt/repoprompt-ce && brew install --cask repoprompt-ce`.

## Smaller tools

- 🔎 **[pi-exa-search](https://github.com/najibninaba/pi-exa-search)** ![Stars](https://img.shields.io/github/stars/najibninaba/pi-exa-search?style=flat&color=gold) - Source discovery and search workflows for the [pi coding agent](https://github.com/badlogic/pi-mono), using Exa.
- 📊 **[jobs-sg](https://github.com/najibninaba/jobs-sg)** ![Stars](https://img.shields.io/github/stars/najibninaba/jobs-sg?style=flat&color=gold) - Shows AI exposure across 562 Singapore occupations. Adapted from [karpathy/jobs](https://github.com/karpathy/jobs), with MOM wage data and SSOC codes.
- ✂️ **[sniplette](https://github.com/najibninaba/sniplette)** - Gets a video from a social media link and makes a small clip that you can send in a chat app.
- 📦 **[bmad-pack-installer](https://github.com/najibninaba/bmad-pack-installer)** ![Stars](https://img.shields.io/github/stars/najibninaba/bmad-pack-installer?style=flat&color=gold) - Installs BMAD expansion packs and manages their symlinks and manifests.

## Earlier work

- 2001 to 2006: I contributed cluster tooling and packages to NPACI Rocks, including the PVFS and Grid Engine rolls.
- 2003 to 2006: I co-founded Scalable Systems, an HPC startup. Platform Computing acquired it in 2006. After that, I led engineering teams in Singapore at Platform Computing and then at Revolution Analytics.

## Activity

![GitHub contribution heatmap](https://ghchart.rshah.org/najibninaba)

## Connect

[![Website](https://img.shields.io/badge/-najibninaba.com-111111?style=flat-square&logo=googlechrome&logoColor=white)](https://najibninaba.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYTIuMDYyIDIuMDYyIDAgMSAxIDAtNC4xMjUgMi4wNjIgMi4wNjIgMCAwIDEgMCA0LjEyNXpNNy4xMTkgMjAuNDUySDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8%2BPC9zdmc%2B)](https://www.linkedin.com/in/najibninaba/)
[![X](https://img.shields.io/badge/-@najibninaba-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/najibninaba)
[![Talks](https://img.shields.io/badge/-Talks-6E56CF?style=flat-square&logo=googleslides&logoColor=white)](https://talks.bijan.app)
