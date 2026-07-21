<h1 align="center">Kerim Lihić</h1>

<p align="center">
  Tech Lead at <a href="https://www.voltium.ai">VoltiumAi</a> · Systems engineer · Security researcher
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows%20Internals-0078D4?style=flat-square&logo=windows11&logoColor=white" alt="Windows Internals">
  <img src="https://img.shields.io/badge/Reverse%20Engineering-1F2937?style=flat-square" alt="Reverse Engineering">
  <img src="https://img.shields.io/badge/Virtualization-7C3AED?style=flat-square" alt="Virtualization">
  <img src="https://img.shields.io/badge/Applied%20AI-0F766E?style=flat-square" alt="Applied AI">
</p>

I build software close to the machine: hypervisor-assisted tracers, Windows kernel
experiments, low-latency graphics, security tooling, and AI systems with explicit
capability boundaries.

## ⚡ Currently: VoltiumAi

I am the Tech Lead at [VoltiumAi](https://www.voltium.ai), a Sarajevo startup building
AI-powered energy optimization for data centers. I lead technical direction and product
engineering across the platform.

VoltiumAi connects to existing DCIM and BMS infrastructure, learns thermal and workload
patterns, then optimizes cooling, UPS usage, and workload scheduling. The goal is to
reduce energy waste, operating cost, and carbon output without replacing existing data
center hardware.

```mermaid
flowchart LR
    A[DCIM and BMS telemetry] --> B[Thermal and workload models]
    B --> C[Optimization engine]
    C --> D[Cooling]
    C --> E[UPS scheduling]
    C --> F[Workload scheduling]
    C --> G[Dashboards and reports]
```

## Selected engineering

| Project | What makes it interesting |
|---|---|
| [**SvmTrace**](https://github.com/ntkrnlmp/svmtrace) | AMD SVM tracer that uses NPT execute faults and intercepted `#DB` exits to capture RIP, RFLAGS, CR3, and 16 GPRs after each instruction |
| [**DComp Overlay**](https://github.com/ntkrnlmp/dcomp-overlay) | D3D11 and DirectComposition overlay DLL manually mapped into `explorer.exe`, with measured render and presentation timing |
| [**VirusShare SDK**](https://github.com/ntkrnlmp/virusshare) | Typed Python SDK and CLI for search, metadata, bounded downloads, and archive inspection |
| [**mapped_explorer**](https://github.com/ntkrnlmp/mapped_explorer) | Windows kernel experiment for finding executable memory outside reported loaded-module ranges |
| [**Excel AI Assistant**](https://github.com/ntkrnlmp/excel-ai-assistant) | Office.js add-in where model actions pass through a named capability policy and confirmed workbook writes |
| [**Anidakapo Studio**](https://github.com/ntkrnlmp/anidakapo-studio) | Interactive 3D web experience built with Next.js, React Three Fiber, Three.js, and GSAP |

## Toolchain

<p>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=111827" alt="C">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
</p>

Windows SDK and WDK · WinDbg · Ghidra · CMake · Office.js · Direct3D 11

Based in Bosnia and Herzegovina.
