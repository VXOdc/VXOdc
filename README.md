<div align="center">

<h1>Noah Ly</h1>
<p><strong>Intelligent Applications Developer & Physics Engine Builder</strong></p>

<p>
  <a href="https://noahly.vercel.app"><img src="https://img.shields.io/badge/Production%20Portfolio-noahly.vercel.app-171717?style=flat-square" alt="Website"></a>
  <a href="https://github.com/VXOdc"><img src="https://img.shields.io/badge/GitHub-VXOdc-171717?style=flat-square" alt="GitHub"></a>
  <a href="mailto:lynoah18@gmail.com"><img src="https://img.shields.io/badge/Email-lynoah18@gmail.com-171717?style=flat-square" alt="Email"></a>
</p>

---

## Product Ecosystems & Core Engineering

### <a href="https://perceptacompute.vercel.app/">**PerceptaCompute**</a> — Web dashboard that processes webcam frames and flags objects using a vision model
A real-time command-center interface architected like a continuous streaming asset to handle automated threat detection, spatial entity tracking, and algorithmic risk evaluation inside the browser.

<br>
<a href="https://perceptacomputeai.vercel.app/">
  <img src="https://i.ibb.co/RGdSngX7/Screenshot-2026-05-27-at-7-54-08-PM-removebg-preview.png" alt="PerceptaCompute Icon" width="150">
</a>
<br><br>

**Temporal Tracking Engine:** Captures hardware video streams directly via native media APIs, passing compressed frame layers through a tracking pipeline (`tracker.ts`) that preserves object identity and spatial persistence across chronological frames.<br><br>
**Heuristic Risk Evaluation:** Features a centralized algorithmic brain (`riskEngine.ts`) that runs deterministic rule sets over classification labels and confidence thresholds to instantly trigger system alarms, notification audio, and multi-tier warning states.<br><br>
**Modular Dashboard State:** Orchestrates a completely decoupled UI layer including system health telemetry, automated activity feeds, and tracking logs, utilizing isolated components to eliminate performance bottlenecks during high-frequency data updates.

*Core Stack: Next.js 15 · React 19 · TypeScript · Tailwind CSS · Custom Risk Heuristics*

---

### <a href="https://neurocompute.vercel.app/">**NeuroCompute**</a> — Real-Time AI Vision in the Browser
A browser-based AI vision system that captures live webcam frames and runs them through a multimodal vision model for instant structured scene analysis — engineered for continuous real-time stability, not just short demos.

<br>
<a href="https://neurocompute.vercel.app/">
  <img src="https://i.postimg.cc/tTNpdvD7/Screenshot-2026-05-17-at-3-11-46-PM-removebg-preview.png" alt="NeuroCompute Icon" width="60">
</a>
<br><br>

**Vision Pipeline:** Captures webcam frames at configurable intervals, compresses them adaptively, and routes them through the `pixtral-12b-2409` vision model via a `/api/detect` endpoint for structured JSON scene analysis including object detection, confidence ratings, and contextual summaries.<br><br>
**Adaptive Compression System:** JPEG quality dynamically adjusts based on rolling API latency — lower latency allows higher quality; higher latency reduces payload size — keeping the pipeline responsive under continuous load.<br><br>
**Non-Blocking Architecture:** A `processingRef` guard prevents overlapping API calls; the detection loop skips frames if a previous request is still in-flight, eliminating request pileups and unnecessary memory pressure.

*Core Stack: Next.js 14 · TypeScript · Mistral Pixtral · Web Speech API · MediaDevices API*

---

### <a href="https://physicsone.vercel.app/">**PhysicsOne**</a> — Deterministic 2D Rigid Body Physics Engine
A real time computational physics framework engineered completely from the ground up to address mathematical and architectural challenges in simulation without reliance on pre-built middleware.

<br>
<a href="https://physicsone.vercel.app/">
  <img src="https://i.postimg.cc/TKfnzd1j/Gemini-Generated-Image-aocx43aocx43aocx-removebg-preview.png" alt="PhysicsOne Engine Icon" width="60">
</a>
<br><br>

**Geometric Collision Detection:** Calculates intersections using the Separating Axis Theorem for convex hull verification, real-time penetration depths, surface contact point manifold generation, and continuous dynamic normalization.<br><br>
**Rigid Body Dynamics:** Resolves physical interactions using semi-implicit Euler integration for velocity stability, exact mass matrix distribution, angular inertia tensors, and momentum-preserving instantaneous impulse resolution.<br><br>
**Engineering Architecture:** Eliminates structural drift, joint jitter, boundary tunneling, and floating-point expansion across shifting global and local coordinate hierarchies through a strict mathematical data pipeline.

*Core Stack: JavaScript · Canvas API · Vector Math · Performance Optimization*

---

### <a href="https://syllastudyai.vercel.app/">**SyllaStudy AI**</a> — Student Productivity Suite
A full-featured, local-first intelligent student application architected to orchestrate low-latency data transformations and optimize cognitive load.

<br>
<a href="https://syllastudyai.vercel.app/">
  <img src="https://i.postimg.cc/ZBB7D8Kx/Screenshot-2026-04-19-at-9-38-06-PM.png" alt="SyllaStudy AI App Icon" width="60" style="border-radius: 12px;">
</a>
<br><br>

**Intelligent Routing:** Integrates a dynamic orchestration tier utilizing dedicated **Mistral AI** models with automated fallback routing to **Google Gemini** APIs for high-availability context processing.<br><br>
**Automation Frameworks:** Powers automated test synthesis engines (QuizGen) alongside deep rich-text extraction and structural note compilation engines (SmartNotes).<br><br>
**Database Constraints:** Enforces strict execution guardrails and token safeguards capped directly at the PostgreSQL layer to ensure backend stability and predictable storage budgets.

*Core Stack: React · Supabase (PostgreSQL) · Node.js · Mistral API · Gemini API*

---

### **Systems, Hardware & Embedded Architecture**
Translating highly complex software pipelines and mathematical models directly into structural mechanical execution.

<br><br>

**Embedded Systems:** Designing low-latency firmware implementations using C/C++ architectures for ESP32 and Arduino microcontrollers.<br><br>
**Mechanical Synthesis:** Developing custom physical controllers and functional hardware housings within CAD prototyping environments.<br><br>
**Hardware Optimization:** Designing high-performance hardware topologies, engineering multi-stage thermal dissipation curves, and overclocking microarchitectures to extract maximum bare-metal compute performance.

---

## Technical Specs

<br>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VXOdc&theme=tokyonight&hide_border=true" alt="Top Languages" />
<br><br>

**Languages:** `JavaScript` `TypeScript` `Python` `C` `C++`<br><br>
**Frameworks & Databases:** `React` `Next.js` `Tailwind CSS` `Node.js` `Supabase` `PostgreSQL`<br><br>
**Core AI Infrastructure:** <img src="https://img.shields.io/badge/Mistral%20AI-orange?style=flat-square&logo=mistralai&logoColor=white" alt="Mistral AI" style="vertical-align: middle;"> <img src="https://img.shields.io/badge/Google%20Gemini-blue?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini API" style="vertical-align: middle;"><br><br>
**Systems & Hardware:** `Vector Math` `Arduino` `ESP32` `CAD Prototyping` `PC Architecture`

---

<sub>High Schooler • Software Developer • Physics Simulation Engine Builder • Hardware Maker</sub>

</div>
