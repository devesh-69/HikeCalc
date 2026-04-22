<p align="center">
  <img src="https://i.ibb.co/BKTSgYV2/Hike-Calc.avif" alt="SalaryHike Calculator" width="120"/>
</p>

<p align="center">
  <strong>A beautifully crafted salary hike calculator for professionals navigating appraisals, job offers, and long-term career growth.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-4a7c59?style=flat-square&labelColor=1c1917" alt="version"/>
  <img src="https://img.shields.io/badge/license-MIT-2563a8?style=flat-square&labelColor=1c1917" alt="license"/>
  <img src="https://img.shields.io/badge/platform-Web%20%7C%20Mobile-b45309?style=flat-square&labelColor=1c1917" alt="platform"/>
  <img src="https://img.shields.io/badge/dependencies-zero-c05621?style=flat-square&labelColor=1c1917" alt="dependencies"/>
  <img src="https://img.shields.io/badge/internet-required-c05621?style=flat-square&labelColor=1c1917" alt="internet required"/>
</p>

<p align="center">
  <a href="https://devesh-69.github.io/HikeCalc/salary-hike-calculator%20(Light).html">
    <img src="https://img.shields.io/badge/Live%20Demo-Try%20it%20now%20%E2%86%92-4a7c59?style=for-the-badge&labelColor=1c1917" alt="Live Demo"/>
  </a>
</p>

---

## ✦ Why SalaryHike Calculator?

Every professional faces the same friction during appraisal season — scattered spreadsheets, mental math, and no easy way to compare multiple offers side by side. **SalaryHike Calculator** solves this with a clean, single-file web app that runs entirely in your browser. No sign-up. No server. No data leaves your device.

> **Note:** An internet connection is required to load Chart.js and Google Fonts from CDN.

Whether you're evaluating a 15% hike from your current employer, comparing three competing job offers, or planning where your salary will be in five years — this tool handles it all with clarity and elegance.

---

## ✦ Features

### 🧮 Hike Calculator
Instantly compute your new salary using either a **percentage hike** or a **fixed amount increase**. Toggle between monthly and annual salary modes to match how you think about your compensation. The result panel shows:

- **New salary** (monthly or annual)
- **Hike amount** in absolute rupees
- **Hike percentage** — even when you entered a flat amount
- **Annual gain** — the total uplift across 12 months
- A visual **base vs. hike breakdown bar** so you can see the ratio at a glance

### 📊 Offer Comparator
Stop juggling tabs and mental arithmetic. Add multiple job offers with their respective base salaries and hike percentages. The comparator renders a **grouped bar chart** showing base vs. post-hike salary for every offer — making the best choice visually obvious. Offers can be named, color-coded, and removed on the fly.

> **Pain point solved:** Comparing "₹1.8L base + 20% hike" vs "₹1.5L base + 35% hike" is non-trivial in your head. This makes it instant.

### 📈 Growth Projector
Enter a projected annual hike rate and see a **5-year salary trajectory** — both as a smooth line chart and a detailed table. Each year shows monthly salary, annual salary, and absolute gain over your current pay. The current year is highlighted so your baseline is always visible.

> **Pain point solved:** Most people underestimate compounding. This makes the long-term impact of negotiating even 2–3% more today viscerally clear.

---

## ✦ Screenshots

> _Add screenshots of the Calculator, Compare, and Growth tabs here._

| Calculator | Compare | Growth |
|:---:|:---:|:---:|
| ![Calculator tab](screenshots/calc.png) | ![Compare tab](screenshots/compare.png) | ![Growth tab](screenshots/growth.png) |

---

## ✦ Getting Started

No build step. No dependencies. No npm install.

**Try it live →** [devesh-69.github.io/HikeCalc](https://devesh-69.github.io/HikeCalc/salary-hike-calculator%20(Light).html)

Or run it locally:

```bash
# Clone the repository
git clone https://github.com/devesh-69/HikeCalc.git

# Open directly in your browser
open salary-hike-calculator.html
```

Or simply download the HTML file and open it. That's it.

---

## ✦ Usage

### Calculate Your Hike

1. Choose **Monthly** or **Annual** mode using the toggle in the header.
2. Enter your **current salary**.
3. Select **Amount** or **Percent** to specify how your hike is expressed.
4. Enter the hike value — results update in real time.

### Compare Offers

1. Navigate to the **Compare** tab.
2. Enter the base salary, hike percentage, and an optional label for each offer.
3. Tap **Add** — the offer appears in the list and the bar chart updates instantly.
4. Remove any offer with the **×** button.

### Project Growth

1. Navigate to the **Growth** tab.
2. Your current salary carries over from the Calculator tab.
3. Adjust the **annual hike rate** to model optimistic or conservative scenarios.
4. Read the 5-year table and chart to plan ahead.

---

## ✦ Design System

The UI is built on a warm, editorial palette designed to feel calm and trustworthy — the opposite of the anxious, neon-drenched dashboards common in fintech.

| Token | Hex | Usage |
|---|---|---|
| `--cream` | `#faf8f4` | App background |
| `--white` | `#ffffff` | Cards, inputs |
| `--ink` | `#1c1917` | Primary text, active states |
| `--sage` | `#4a7c59` | Positive values, growth, CTA |
| `--rust` | `#c05621` | Hike amounts, accent highlights |
| `--sky` | `#2563a8` | Informational, secondary accent |
| `--gold` | `#b45309` | Warnings, tertiary accent |

Typography uses **Lora** (serif) for figures and brand moments, paired with **DM Sans** for UI labels and body copy — a combination that feels editorial without being stiff.

---

## ✦ Technical Details

| Attribute | Detail |
|---|---|
| **Architecture** | Single HTML file — zero build tooling |
| **Runtime dependencies** | [Chart.js 4.4.1](https://www.chartjs.org/) via CDN |
| **Fonts** | Google Fonts (Lora + DM Sans) |
| **Data persistence** | None — stateless by design |
| **Privacy** | 100% client-side; no data sent anywhere |
| **Mobile** | Fully responsive, sticky header + fixed bottom nav |
| **Browser support** | All modern browsers (Chrome, Firefox, Safari, Edge) |

---

## ✦ Contributing

Contributions are welcome and appreciated. Please open an issue first to discuss significant changes before submitting a pull request.

```bash
# Fork and clone
git clone https://github.com/devesh-69/HikeCalc.git

# Create a feature branch
git checkout -b feat/your-feature-name

# Make your changes, then open a PR
```

Please keep the single-file architecture intact for zero-install simplicity. If adding new features, follow the existing color system and typography conventions.

---

## ✦ License

Released under the [MIT License](./LICENSE). Free to use, modify, and distribute — personal or commercial.

---

<p align="center">
  Made with care for professionals who deserve clarity at appraisal time. &nbsp;·&nbsp;
  <a href="https://github.com/devesh-69/HikeCalc/issues">Report a bug</a> &nbsp;·&nbsp;
  <a href="https://github.com/devesh-69/HikeCalc/issues">Request a feature</a>
</p>
