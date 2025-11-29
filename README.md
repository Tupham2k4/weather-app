# 🌤️ Weather App

> Ứng dụng dự báo thời tiết hiện đại, trực quan, hỗ trợ tìm kiếm theo
> tên thành phố hoặc lấy thông tin thời tiết theo vị trí hiện tại
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

# 🔑 API Key Setup

Ứng dụng cần API Key của OpenWeatherMap.

1.  Lấy API key tại: https://openweathermap.org/api\
2.  Mở file `script.js`
3.  Thay vào đây:

``` javascript
const apiKey = "YOUR_API_KEY_HERE";
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
