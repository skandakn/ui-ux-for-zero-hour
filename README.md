# ⚡ APPROVA — Brutalist Fintech Approval Workflow & 3D Audit Dashboard

> **Winner-tier submission for the Zero Hour UI/UX Challenge.**  
> Inspired by Kombai's "Approva" design specification (`dashboards-web-18`).

![Approva Preview](https://agent.kombai.com/kombai-inspiration-library/app-pages/dashboards/web/18/index.html)

---

## 💎 Design System & Aesthetic Spec

- **Style**: Neo-Brutalist, mint-green canvas (`#CFE8D6`), `#121210` hard 3px borders with offset drop shadows (`4px 4px 0 #121210`).
- **Typography**: 
  - `Archivo` (Heavy Display Headings)
  - `Hanken Grotesk` (Interface & Body Copy)
  - `Space Mono` (Tabular Numbers & Currency Amounts)
- **Palette**:
  - Canvas: `#CFE8D6`
  - Ink / Border: `#121210`
  - Approved / Pass: `#2E8C42`
  - Escalated / Reject: `#C03A3A`
  - Review / Warning: `#E8A030`

---

## 🚀 Key Features Built

### 1. 🌐 Interactive 3D Kinetic Audit Seal (Three.js WebGL)
- An interactive 3D physical metallic seal/token rendered with WebGL.
- Drag & inspect the 3D coin in real-time.
- Material shader changer (`#2E8C42`, `#E8A030`, `#C03A3A`, `#00A3FF`).
- High-velocity 3D rotational burst when decisions are stamped!

### 2. 📑 Three-Pane Financial Workflow
1. **Sidebar Navigation**: Approva brand badge, live inbox count (12), escalations (3), history, workflow builder, daily stamped meter, and Mara Vossberg CFO profile.
2. **Request Queue**: Multi-status cards with SLA risk counters (`3D SLA LEFT`, `+52H LATE`), submitter avatars, and multi-tier approval chain nodes.
3. **Purchase Order Document Viewer**: Line-item breakdown table, subtotal/VAT calculation, and 4-tier approval chain stepper.

### 3. 🎯 Tactile Decisions & Hotkeys
- **Approve (`Ctrl/⌘ + Enter`)**: Drops brutalist green stamp watermark with spring physics, document vibration shake, celebration confetti explosion, and mechanical audio thump.
- **Reject (`Ctrl/⌘ + Backspace`)**: Applies red rejection watermark and routes to audit log.
- **Needs Detail (`Ctrl/⌘ + D`)**: Flags for revisions.
- **Search (`Ctrl/⌘ + K`)**: Quick focus on filter bar.

### 4. 📜 Immutable Audit Terminal & Workflow Builder
- SHA-256 chained transaction log updating in real-time.
- Interactive visual pipeline for "CapEx ≥ $25k" with customizable stages.
- Escalation warning strip with amber warning stripes.

---

## 🏃‍♂️ How to Run Locally

Simply double-click `index.html` or open it in any modern browser:
```bash
# Clone the repository
git clone https://github.com/skandakn/ui-ux-for-zero-hour.git
cd ui-ux-for-zero-hour

# Open in browser
start index.html   # Windows
# or open index.html on macOS / Linux
```

Zero build steps, zero `node_modules` delay — powered by modern CDN imports (Tailwind CSS, Three.js, Lucide, Tabler, GSAP, Canvas Confetti).
