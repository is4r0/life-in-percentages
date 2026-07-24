# Life in Percentages

**Your days are becoming years.**

Life in Percentages is a visually powerful self-awareness experience where users enter their daily habits, and the website transforms those routines into shocking lifetime statistics.

<img width="1887" height="1036" alt="image" src="https://github.com/user-attachments/assets/a63daabe-f738-4d9a-bda2-ab1855d047ae" />

<img width="1887" height="1025" alt="image" src="https://github.com/user-attachments/assets/e6c0e9a7-1400-43ae-9f62-85ec259deea2" />


## ✨ Features

- **Premium Aesthetic**: Minimalist charcoal and gold design language.
- **Cinematic Experience**: Smooth scroll-triggered storytelling and reveal scenes.
- **Procedural Audio**: Emotional ambient soundtrack and SFX generated with Web Audio API.
- **Real-time Insights**: Habit sliders show immediate lifetime impact.
- **Reflection Engine**: Calculates years spent on sleep, screens, movement, and connection.

## 🛠️ Tech Stack

- **Framework**: Next.js 15
- **Styling**: Tailwind CSS 4
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Audio**: Web Audio API (Procedural)

## 🚀 Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) to see the experience.

## 📈 Calculation Logic

The experience assumes a default lifespan (configurable by the user, default 80 years) and calculates lifetime impact based on average daily hours:
`Lifetime Years = (Daily Hours * 365 * Lifespan) / (365 * 24)`

Created with ❤️ by Isar
