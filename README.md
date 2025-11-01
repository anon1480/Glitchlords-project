---

# 🌍 **Live Forex Dashboard**

### 💱 Real-Time Currency Conversion and Forex News Platform

---

## 🚀 **Project Overview**

The **Live Forex Dashboard** is a **web-based application** designed to provide real-time **foreign exchange (forex) rates** and enable instant **currency conversion** between global currencies.
In addition to conversion tools, it also integrates **live forex news** from trusted sources to keep users informed about market trends, economic policies, and financial developments that influence currency movements.

This project combines **data visualization**, **live APIs**, and **intuitive design** to create an informative and interactive experience for traders, investors, and finance enthusiasts.

---

## 🎯 **Objectives**

* Display **real-time exchange rates** using the [**ExchangeRate API**](https://www.exchangerate-api.com/).
* Provide an **instant currency converter** with accurate and up-to-date rates.
* Integrate **live forex news updates** using the [**GNews API**](https://gnews.io/).
* Offer a **dynamic, user-friendly, and responsive** interface.
* Serve as a **reliable financial dashboard** for quick reference and insights.

---

## 🏗️ **Tech Stack**

| Layer                     | Technology                                                                            |
| ------------------------- | ------------------------------------------------------------------------------------- |
| **Frontend**              | HTML, CSS, JavaScript, React (or Vanilla JS if simple setup)                          |
| **Backend**               | Node.js, Express.js                                                                   |
| **APIs**                  | [ExchangeRate API](https://www.exchangerate-api.com/), [GNews API](https://gnews.io/) |
| **Environment Variables** | Managed using `.env`                                                                  |
| **Hosting (Optional)**    | Render / Vercel / Netlify (Frontend), Railway / Heroku (Backend)                      |

---

## 🧩 **Project Structure**

```
Forex-Dashboard/
│
├── backend/
│   ├── server.js
│   ├── package.json
│   ├── .env
│   └── node_modules/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   └── assets/
│
└── README.md
```

---

## ⚙️ **Setup & Installation**

### 🔹 1. Clone the Repository

```bash
git clone https://github.com/anon1480/Glitchlords-project.git
cd forex-dashboard
```

---

### 🔹 2. Backend Setup

```bash
cd backend
npm install
```

#### Create a `.env` file:

```env
PORT=5000
EXCHANGE_RATE_API_KEY=your_exchange_rate_api_key_here
GNEWS_API_KEY=your_gnews_api_key_here
```

#### Start the backend:

```bash
node server.js
```

Server runs at:

```
http://localhost:5000
```

---

### 🔹 3. Frontend Setup

If using plain HTML/CSS/JS:

* Open `frontend/index.html` in your browser
  or
* Serve it using VS Code Live Server

If using React:

```bash
cd frontend
npm install
npm start
```

---

## 🌐 **API References**

### 🪙 ExchangeRate API

* **Endpoint:** `https://v6.exchangerate-api.com/v6/YOUR_API_KEY/latest/USD`
* Provides live exchange rates for multiple currencies.

### 📰 GNews API

* **Endpoint:** `https://gnews.io/api/v4/search?q=forex&lang=en&country=us&max=10&apikey=YOUR_API_KEY`
* Returns real-time forex and market news articles.

---

## 🧠 **Features**

✅ Real-time forex rate updates
✅ Instant currency conversion
✅ Live forex market news feed
✅ Responsive and modern UI
✅ Fast Node.js backend
✅ Error handling for API failures
✅ Secure API key management with `.env`

---

## 📊 **Example Workflow**

1. User opens the dashboard.
2. The frontend fetches current exchange rates from **ExchangeRate API**.
3. User selects two currencies to convert.
4. The backend processes API requests and returns accurate conversion values.
5. The news section dynamically updates using **GNews API**, showing the latest forex-related headlines.

---

## 🧰 **Sample API Response**

### 💱 Exchange Rate API

```json
{
  "base_code": "USD",
  "conversion_rates": {
    "EUR": 0.93,
    "GBP": 0.81,
    "INR": 83.12,
    "JPY": 150.05
  }
}
```

### 📰 GNews API

```json
{
  "totalArticles": 10,
  "articles": [
    {
      "title": "Dollar strengthens amid inflation fears",
      "description": "The dollar gained on Friday...",
      "source": { "name": "Reuters" },
      "publishedAt": "2025-11-01T09:00:00Z",
      "url": "https://www.reuters.com/article/example",
      "image": "https://example.com/image.jpg"
    }
  ]
}
```

---

## 🔐 **Environment Variables**

| Variable                | Description                    |
| ----------------------- | ------------------------------ |
| `PORT`                  | Port number for backend server |
| `EXCHANGE_RATE_API_KEY` | Your ExchangeRate API key      |
| `GNEWS_API_KEY`         | Your GNews API key             |

---

## 🧩 **Future Enhancements**

* Add **chart visualization** for currency trends (using Chart.js or Recharts).
* Implement **user authentication** for personalized dashboards.
* Introduce **dark mode** and UI themes.
* Add **historical forex data** and **predictive analysis**.
* Mobile-friendly **PWA (Progressive Web App)** version.

---

## 🤝 **Contributing**

1. Fork the repo
2. Create your feature branch:

   ```bash
   git checkout -b feature/new-feature
   ```
3. Commit your changes:

   ```bash
   git commit -m "Add new feature"
   ```
4. Push to branch and create a Pull Request

## 🌟 **Acknowledgements**

* [ExchangeRate API](https://www.exchangerate-api.com/) for real-time currency data
* [GNews API](https://gnews.io/) for live forex news
* [Node.js](https://nodejs.org/) and [Express.js](https://expressjs.com/) for backend support

---

