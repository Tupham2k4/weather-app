# 🌤️ Weather App

> Ứng dụng dự báo thời tiết hiện đại, trực quan, hỗ trợ tìm kiếm theo
> tên thành phố hoặc lấy thông tin thời tiết theo vị trí hiện tại.

```{=html}
<p align="center">
```
`<img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge"/>`{=html}
`<img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge"/>`{=html}
`<img src="https://img.shields.io/badge/Build-JavaScript-yellow?style=for-the-badge"/>`{=html}
```{=html}
</p>
```
```{=html}
<p align="center">
```
`<img src="assets/screenshot.png" width="650px" alt="Weather App Screenshot"/>`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

# 📑 Table of Contents

-   [🌤️ Weather App](#️-weather-app)
-   [📑 Table of Contents](#-table-of-contents)
-   [✨ Features](#-features)
-   [🖥️ Demo](#️-demo)
-   [📦 Project Structure](#-project-structure)
-   [🛠️ Technologies Used](#️-technologies-used)
-   [🚀 Installation](#-installation)
-   [🔑 API Key Setup](#-api-key-setup)
-   [📸 Screenshots](#-screenshots)
-   [🧩 Notes](#-notes)
-   [📜 License](#-license)

------------------------------------------------------------------------

# ✨ Features

-   🔍 **Tìm kiếm thời tiết theo thành phố**
-   📍 **Lấy vị trí hiện tại bằng Geolocation API**
-   🌡️ Thông tin hiển thị:
    -   Nhiệt độ
    -   Feels-like
    -   Độ ẩm
    -   Tốc độ gió
    -   Mô tả thời tiết
-   🖼️ Icon động theo điều kiện thời tiết
-   ⚡ Load nhanh, giao diện thân thiện, responsive

------------------------------------------------------------------------

# 🖥️ Demo

👉 **Live Demo:** *(thay link của bạn tại đây)*\
https://your-demo-link.com

------------------------------------------------------------------------

# 📦 Project Structure

    Weather-App/
    │── index.html
    │── style.css
    │── script.js
    │── assets/
    │     ├── icons/
    │     └── screenshot.png
    └── README.md

------------------------------------------------------------------------

# 🛠️ Technologies Used

-   **HTML5**
-   **CSS3**
-   **JavaScript (ES6+)**
-   **OpenWeatherMap API**
-   **Fetch API**
-   **Geolocation API**

------------------------------------------------------------------------

# 🚀 Installation

### 1️⃣ Clone repository

``` sh
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

### 2️⃣ Run the app

Ứng dụng chạy 100% client-side.

Chỉ cần mở:

    index.html

Khuyến nghị dùng **Live Server (VSCode)** để auto reload:

1.  Cài extension **Live Server**\
2.  Nhấn **Go Live**

------------------------------------------------------------------------

# 🔑 API Key Setup

Ứng dụng cần API Key của OpenWeatherMap.

1.  Lấy API key tại: https://openweathermap.org/api\
2.  Mở file `script.js`
3.  Thay vào đây:

``` javascript
const apiKey = "YOUR_API_KEY_HERE";
```

------------------------------------------------------------------------

# 📸 Screenshots

### 🌤️ Giao diện chính

*(Chỉnh đường dẫn nếu cần)*

```{=html}
<p align="center">
```
`<img src="assets/screenshot.png" width="650px"/>`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

# 🧩 Notes

-   Nếu chạy trên HTTP, một số trình duyệt **không cho dùng
    Geolocation**.\
-   API miễn phí có giới hạn request → tránh spam reload.\
-   Bạn có thể mở rộng: 7-day forecast, dark mode, auto-suggest city...

------------------------------------------------------------------------

# 📜 License

Distributed under the **MIT License**.\
Bạn được phép sử dụng cho mục đích học tập và phát triển cá nhân.
