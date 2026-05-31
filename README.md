# 🛒 Smart Product Price Comparison

<div align="center">

![Smart Price Comparison](https://img.shields.io/badge/Smart%20Price%20Comparison-v1.0.0-orange?style=for-the-badge&logo=shopify)
![JavaScript](https://img.shields.io/badge/JavaScript-67.9%25-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-smart--product--price--comparison.onrender.com-6b73ff?style=for-the-badge)](https://smart-product-price-comparison.onrender.com/)

**A real-time web application that aggregates product data from major e-commerce platforms to help users find the best deals instantly.**

</div>

---



## 📖 About the Project

**Smart Product Price Comparison** is a real-time web scraping application that fetches and compares product prices from multiple major Indian e-commerce platforms — Amazon, Flipkart, Snapdeal, and Myntra — all in one place. Users can search for any product and instantly see prices side-by-side, making it easy to identify the best deal without switching between tabs.

---

## ✨ Features

- 🔍 **Real-Time Product Search** — Search any product and get live results instantly
- 💰 **Multi-Platform Price Comparison** — Aggregate prices from Amazon, Flipkart, Snapdeal & Myntra
- ⚡ **Fast Web Scraping** — Powered by Axios + Cheerio for efficient data extraction
- 📊 **Side-by-Side Results** — Clean UI to compare prices at a glance
- 🌐 **CORS Enabled** — Cross-origin support for seamless frontend-backend communication
- 📱 **Responsive Design** — Works smoothly on desktop and mobile

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Runtime** | Node.js |
| **Framework** | Express.js v5 |
| **Scraping** | Axios + Cheerio |
| **Frontend** | HTML, CSS, JavaScript |
| **CORS** | cors |
| **Package Manager** | npm |

---

## 🛍️ Supported Platforms

| Platform | Status |
|----------|--------|
| 🟠 Amazon | ✅ Supported |
| 🔵 Flipkart | ✅ Supported |
| 🔴 Snapdeal | ✅ Supported |
| 🩷 Myntra | ✅ Supported |

---

## 📁 Project Structure

```
Smart-Product-Price-Comparison/
├── public/              # Frontend files (HTML, CSS, JS)
│   ├── index.html
│   ├── style.css
│   └── script.js
├── scraper.js           # Web scraping logic (Axios + Cheerio)
├── server.js            # Express server & API routes
├── package.json         # Project metadata & dependencies
└── README.md
```

---

## ⚙️ How It Works

```
User Search Query
      │
      ▼
 Express Server (server.js)
      │
      ▼
 Scraper Module (scraper.js)
  ┌───┴────────────────────────────┐
  │  Axios fetches HTML pages from  │
  │  Amazon, Flipkart, Snapdeal,    │
  │  and Myntra simultaneously      │
  └───┬────────────────────────────┘
      │
      ▼
 Cheerio parses HTML → extracts
 product names, prices & links
      │
      ▼
 JSON response sent to frontend
      │
      ▼
 Results displayed side-by-side
```

---

## 🌐 Live Demo

The application is deployed and accessible at:

**🔗 [https://smart-product-price-comparison.onrender.com/](https://smart-product-price-comparison.onrender.com/)**

Try it out — search for any product and compare live prices across Amazon, Flipkart, Snapdeal, and Myntra instantly!

> **Note:** Since this is hosted on Render's free tier, the server may take ~30 seconds to spin up on the first visit after a period of inactivity.

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the ISC License. See `LICENSE` for more information.

---

## 📬 Contact

**Abhijeet Patil**

[![Portfolio](https://img.shields.io/badge/Portfolio-abhijeetp--portfolio.netlify.app-ff5722?style=flat&logo=netlify)](https://abhijeetp-portfolio.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abhijeetp02-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/abhijeetp02/)
[![GitHub](https://img.shields.io/badge/GitHub-abhijeetpatil02-181717?style=flat&logo=github)](https://github.com/abhijeetpatil02)

Project Link: [https://github.com/abhijeetpatil02/Smart-Product-Price-Comparison](https://github.com/abhijeetpatil02/Smart-Product-Price-Comparison)

---

<div align="center" style=color:"black">
  Made with ❤️ by <a href="https://github.com/abhijeetpatil02">Abhijeet Patil</a>
</div>
