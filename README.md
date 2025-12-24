# 🌦️ Weather App

A modern, responsive **Weather Application** built with **React + TypeScript**, featuring a clean UI using **shadcn/ui**, powerful data fetching with **TanStack Query**, beautiful visualizations via **Recharts**, and styling powered by **Tailwind CSS**. The app integrates with a **Weather API** to fetch real-time weather data.

---

## 🚀 Features

* 🌍 Search weather by city
* 📊 Interactive weather charts (temperature, humidity, etc.)
* ⚡ Fast & cached API calls using TanStack Query
* 🎨 Modern UI with shadcn/ui components
* 📱 Fully responsive design
* 🌙 Clean and accessible UI

---

## 🛠️ Tech Stack

* **Frontend:** React + TypeScript
* **UI Components:** shadcn/ui
* **Styling:** Tailwind CSS
* **Data Fetching:** @tanstack/react-query
* **Charts:** Recharts
* **Weather Data:** External Weather API
* **Build Tool:** 

---

## 📂 Project Structure

```bash
src/
 ├── api/            # Weather API configuration & requests
 ├── components/     # Reusable UI components (shadcn/ui)
 ├── context/        # Global state & context providers
 ├── hooks/          # Custom React hooks
 ├── lib/            # Utility functions & helpers
 ├── pages/          # Application pages / routes
 ├── App.css
 ├── App.tsx         # Root component
 ├── index.css       # Global styles (Tailwind)
 ├── main.tsx        # App entry point
 └── vite-env.d.ts   # Vite type definitions

```

---

## 🔐 Environment Variables

Create a `.env` file in the root directory:

```env
VITE_OPENWEATHER_API_KEY=your_weather_api_key
```

> ⚠️ **Note:** Do not commit `.env` to GitHub. Add it to `.gitignore`.

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Start development server

```bash
npm run dev
```

App will run at 👉 `http://localhost:5173`

---

## 📊 Charts & Visualizations

* Temperature trends
* Humidity levels
* Weather conditions overview

Built using **Recharts** for smooth and interactive data visualization.

---

## 🌐 Weather API Integration

The app uses a **Weather API** to:

* Fetch real-time weather data
* Display temperature, humidity, and conditions
* Power charts and visual insights

---

## 🧪 Future Enhancements

* 📍 Geolocation-based weather
* 🌙 Dark mode toggle
* 📅 5-day weather forecast
* 🔔 Weather alerts & notifications

---

## 📜 License

This project is licensed under the **MIT License**.

---

⭐ If you like this project, don’t forget to **star the repo**!
