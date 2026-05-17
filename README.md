<div align="center">
  <h1>Noah Ly</h1>
  <p><strong>Intelligent Applications Developer & Physics Engine Builder</strong></p>

  <p>
    <a href="https://noahly.vercel.app"><img src="https://img.shields.io/badge/Production%20Portfolio-noahly.vercel.app-171717?style=flat-square" alt="Website"></a>
    <a href="https://github.com/VXOdc"><img src="https://img.shields.io/badge/GitHub-VXOdc-171717?style=flat-square" alt="GitHub"></a>
    <a href="mailto:lynoah18@gmail.com"><img src="https://img.shields.io/badge/Email-lynoah18@gmail.com-171717?style=flat-square" alt="Email"></a>
  </p>
</div>

---

## Production Ecosystems & Core Engineering

### <a href="https://neurocompute.vercel.app/">**NeuroCompute**</a> — Real-Time AI Vision in the Browser
A browser-based AI vision system that captures live webcam frames and runs them through a multimodal vision model for instant structured scene analysis — engineered for continuous real-time stability, not just short demos.

<div align="center">
  <br>
  <a href="https://neurocompute.vercel.app/">
    <img src="https://i.postimg.cc/tTNpdvD7/Screenshot-2026-05-17-at-3-11-46-PM-removebg-preview.png" alt="NeuroCompute Icon" width="60">
  </a>
  <br><br>
</div>

* **Vision Pipeline:** Captures webcam frames at configurable intervals, compresses them adaptively, and routes them through the `pixtral-12b-2409` vision model via a `/api/detect` endpoint for structured JSON scene analysis including object detection, confidence ratings, and contextual summaries
* **Adaptive Compression System:** JPEG quality dynamically adjusts based on rolling API latency — lower latency allows higher quality; higher latency reduces payload size — keeping the pipeline responsive under continuous load
* **Non-Blocking Architecture:** A `processingRef` guard prevents overlapping API calls; the detection loop skips frames if a previous request is still in-flight, eliminating request pileups and unnecessary memory pressure

*Core Stack: Next.js 14 · TypeScript · Mistral Pixtral · Web Speech API · MediaDevices API*

---

### <a href="https://physicsone.vercel.app/">**PhysicsOne**</a> — Deterministic 2D Rigid Body Physics Engine
A real-time computational physics framework engineered completely from the ground up to address mathematical and architectural challenges in simulation without reliance on pre-built middleware.

<div align="center">
  <br>
  <a href="https://physicsone.vercel.app/">
    <img src="https://i.postimg.cc/TKfnzd1j/Gemini-Generated-Image-aocx43aocx43aocx-removebg-preview.png" alt="PhysicsOne Engine Icon" width="60">
  </a>
  <br><br>
</div>

* **Geometric Collision Detection:** Calculates intersections using the Separating Axis Theorem for convex hull verification, real-time penetration depths, surface contact point manifold generation, and continuous dynamic normalization
* **Rigid Body Dynamics:** Resolves physical interactions using semi-implicit Euler integration for velocity stability, exact mass matrix distribution, angular inertia tensors, and momentum-preserving instantaneous impulse resolution
* **Engineering Architecture:** Eliminates structural drift, joint jitter, boundary tunneling, and floating-point expansion across shifting global and local coordinate hierarchies through a strict mathematical data pipeline

*Core Stack: JavaScript · Canvas API · Vector Math · Performance Optimization*

---

### <a href="https://syllastudyai.vercel.app/">**SyllaStudy AI**</a> — Student Productivity Suite
A full-featured, local-first intelligent student application architected to orchestrate low-latency data transformations and optimize cognitive load.

<div align="center">
  <br>
  <a href="https://syllastudyai.vercel.app/">
    <img src="https://i.postimg.cc/ZBB7D8Kx/Screenshot-2026-04-19-at-9-38-06-PM.png" alt="SyllaStudy AI App Icon" width="60" style="border-radius: 12px;">
  </a>
  <br><br>
</div>

* **Intelligent Routing:** Integrates a dynamic orchestration tier utilizing dedicated **Mistral AI** models with automated fallback routing to **Google Gemini** APIs for high-availability context processing.
* **Automation Frameworks:** Powers automated test synthesis engines (QuizGen) alongside deep rich-text extraction and structural note compilation engines (SmartNotes).
* **Database Constraints:** Enforces strict execution guardrails and token safeguards capped directly at the PostgreSQL layer to ensure backend stability and predictable storage budgets.

*Core Stack: React · Supabase (PostgreSQL) · Node.js · Mistral API · Gemini API*

---

### **Systems, Hardware & Embedded Architecture**
Translating highly complex software pipelines and mathematical models directly into structural mechanical execution.

* **Embedded Systems:** Designing low-latency firmware implementations using C/C++ architectures for ESP32 and Arduino microcontrollers
* **Mechanical Synthesis:** Developing custom physical controllers and functional hardware housings within CAD prototyping environments
* **Hardware Optimization:** Designing high-performance hardware topologies, engineering multi-stage thermal dissipation curves, and overclocking microarchitectures to extract maximum bare-metal compute performance

---

## Technical Domain Matrix

| Layer | Technologies |
| :--- | :--- |
| **Languages** | `JavaScript` `TypeScript` `Python` `C` `C++` |
| **Frameworks & Databases** | `React` `Next.js` `Tailwind CSS` `Node.js` `Supabase` `PostgreSQL` |
| **Core AI Infrastructure** | <img src="https://img.shields.io/badge/Mistral%20AI-orange?style=flat-square&logo=mistralai&logoColor=white" alt="Mistral AI"> <img src="https://img.shields.io/badge/Google%20Gemini-blue?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini API"> |
| **Systems & Hardware** | `Vector Math` `Arduino` `ESP32` `CAD Prototyping` `PC Architecture` |

---

<div align="center">
  <sub>High School Freshman • Software Developer • Physics Simulation Engine Builder • Hardware Maker</sub>
</div>
