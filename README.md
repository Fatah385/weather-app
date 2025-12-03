🌦️ Weather App — React + TailwindCSS

A simple and beautiful weather application built with React, TailwindCSS, and OpenWeather API.
Users can search for any city and view real-time weather information such as temperature, humidity, wind speed, and more.
Supports Dark Mode with local theme saving 🎨

🚀 Features

🔍 Search weather by city name

🌡️ Display temperature, weather status, humidity & wind speed

🌓 Dark Mode toggle (with transition animation)

💾 Theme saved in LocalStorage

🎯 Keyboard support: press Enter to search

🌈 Auto Weather Icons based on condition

📱 Fully responsive UI (mobile-friendly)

🛠️ Tech Stack
| Technology      | Usage                         |
| --------------- | ----------------------------- |
| React           | UI & State management         |
| TailwindCSS v4  | Styling & Dark mode variant   |
| OpenWeather API | Weather data                  |
| Lucide Icons    | Icons (Sun, Moon, Wind, etc.) |
| Vite            | Fast dev environment          |

📦 Installation & Setup

# 1️⃣ Clone the project
git clone https://github.com/your-username/weather-app.git
cd weather-app

# 2️⃣ Install dependencies
npm install

# 3️⃣ Create environment file
echo "VITE_WEATHER_KEY=YOUR_API_KEY_HERE" > .env

# 4️⃣ Run the project
npm run dev

Get your free API key here: https://openweathermap.org/api

📁 Folder Structure

src/
 ├─ assets/images          # Weather icons
 ├─ App.jsx                # Main component
 ├─ index.css              # Global styles
 └─ main.jsx               # App entry

🖼️ Preview
| Light Mode         | Dark Mode          |
| ------------------ | ------------------ |
| <img width="531" height="601" alt="light-mode" src="https://github.com/user-attachments/assets/f10e7d4f-cb17-46c1-ac23-8b8ca2f7141d" />
 | <img width="548" height="607" alt="dark-mode" src="https://github.com/user-attachments/assets/616096bf-75f9-4ae0-afff-511931471ce0" />
 |

🌱 Future Improvements

🌍 Detect user location using Geolocation

🕐 Show forecast (next 5 days)

☁ Animated backgrounds based on weather

⏳ Loading and error states UI upgrade

📜 License

This project is licensed under the MIT License — free to use and modify!

💡 Author

Created by Yahya ✨
If you like it, consider giving a ⭐ on GitHub!

