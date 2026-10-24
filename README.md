# 🐝 The Urban Hive Project — 2026 Interactive Annual Report

> **An editorial-grade, interactive impact report showcasing urban beekeeping, rooftop wildflower meadows, and ecological corridors across London.**

[![React](https://img.shields.io/badge/React-19.0-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Motion](https://img.shields.io/badge/Motion-v12-FF4154?logo=framer&logoColor=white)](https://motion.dev/)
[![Vite](https://img.shields.io/badge/Vite-6.2-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)

---

## 🌟 Overview

**The Urban Hive Project** transforms London's concrete rooftops into thriving biodiversity corridors. This digital annual report replaces traditional static PDFs with an immersive, data-driven web experience featuring fluid animations, geographic data visualizations, and an interactive rooftop impact simulator.

### 📊 Key 2026 Impact Metrics
- **52+** Rooftop Apiaries & Wildflower Havens
- **1.4 Million+** Foraging Bees Supported
- **3,200 kg** Urban Honey Sustainably Harvested
- **12** Connected London Borough Biodiversity Corridors
- **980,000+ Litres** Stormwater Retained Annually

---

## ✨ Features

- **🗺️ Interactive London Pollinator Map:** Dynamic borough-by-borough map powered by D3-geo showcasing hive distribution and ecological stepping stones.
- **🧮 Rooftop Impact Calculator:** Real-time simulation tool allowing building managers and homeowners to estimate honey production, cooling effect, and biodiversity score.
- **📖 Editorial Magazine Layout:** High-contrast typography pairing *Fraunces* and *Newsreader* serif headings with modern *Plus Jakarta Sans* body text.
- **🌓 Seamless Dark / Light Mode:** Custom-tailored nature palettes (sandstone, olive green, warm dark foliage).
- **🌊 Fluid Spring Animations:** Motion-driven scroll progress bar, counter animations, and card reveals.
- **📱 100% Responsive & Accessible:** Fully optimized for mobile, tablet, and desktop viewports.

---

## 🛠️ Tech Stack

| Category | Technology |
| :--- | :--- |
| **Framework** | [React 19](https://react.dev/) |
| **Language** | [TypeScript](https://www.typescriptlang.org/) |
| **Styling** | [Tailwind CSS v4](https://tailwindcss.com/) |
| **Animations** | [Motion (Framer Motion 12)](https://motion.dev/) |
| **Mapping & Visuals** | [D3-geo](https://d3js.org/d3-geo) & [Lucide React](https://lucide.dev/) |
| **Build Tool** | [Vite 6](https://vitejs.dev/) |

---

## 🚀 Getting Started

Follow these steps to run the project locally on your machine:

### 1. Prerequisites
Ensure you have **Node.js 18+** installed:
```bash
node -v
npm -v
```

### 2. Clone the Repository
```bash
git clone https://github.com/your-username/urban-hive-annual-report.git
cd urban-hive-annual-report
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Run Development Server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

### 5. Build for Production
```bash
npm run build
```

---

## 📁 Project Structure

```
├── src/
│   ├── assets/            # Editorial photos & background media
│   ├── components/        # Modular UI components
│   │   ├── BoroughCorridorSection.tsx
│   │   ├── EducationSection.tsx
│   │   ├── FoodSharingSection.tsx
│   │   ├── HeroSection.tsx
│   │   ├── LondonPollinatorMap.tsx   # D3-powered interactive map
│   │   ├── Navbar.tsx
│   │   ├── OverviewSection.tsx
│   │   ├── RoadmapGratitudeSection.tsx # Future vision & footer
│   │   ├── RooftopCalculator.tsx     # Interactive simulator
│   │   ├── SectorImpactSection.tsx
│   │   └── StormwaterClimateSection.tsx
│   ├── context/           # Theme context (Light/Dark mode)
│   ├── data/              # London borough & report data
│   ├── types.ts           # TypeScript interfaces
│   ├── App.tsx            # Main application layout
│   └── main.tsx           # React DOM entry point
├── index.html             # HTML template with Google Fonts
├── package.json           # Project dependencies & scripts
└── vite.config.ts         # Vite configuration
```

---

## 👨‍💻 Author

**Crafted with care by Rakesh**  
- 💼 LinkedIn: *[Add your LinkedIn profile link here]*  
- 🐙 GitHub: *[Add your GitHub profile link here]*

---

## 📄 License

This project is open-source and licensed under the [Apache-2.0 License](LICENSE).
