---

# Email Automation Tool with AI-Powered Replies

## Overview

This project is a **full-stack email automation tool** that integrates **Google's Gemini API** to generate context-aware email replies with **95% semantic accuracy**. The system includes:

- A **Spring Boot** backend with **Spring AI** for processing AI-generated responses.
- A **React frontend** with **Material-UI**, providing real-time previews of AI-generated replies.
- A **Chrome extension** (Manifest V3) for **1-click AI reply integration** in Gmail.

## Features

✅ **AI-Powered Email Replies** – Automatically generates intelligent email responses.  
✅ **Optimized Performance** – 40% lower latency compared to baseline models.  
✅ **Chrome Extension** – Seamless Gmail integration, reducing response time by 50%.  
✅ **Real-Time Previews** – Live editing and review of AI-generated replies.  
✅ **Spring Boot Backend** – RESTful API using **Spring AI, JPA**, and **dependency injection**.

## Tech Stack

- **Backend**: Spring Boot, Spring AI, JPA, Google Gemini API
- **Frontend**: React, Material-UI
- **Browser Extension**: Chrome Manifest V3

## Installation & Setup

### **1. Run the Spring Boot Backend**

```bash
./mvnw spring-boot:run
```

> Ensure your `application.properties` is configured with database credentials and API keys.

### **2. Setup & Run the Frontend**

```bash
npm install
npm run dev
```

### **3. Load Chrome Extension**

1. Open **Google Chrome** → Navigate to `chrome://extensions/`
2. Enable **Developer Mode** (top-right corner).
3. Click **Load Unpacked** and select the `extension` folder.
4. The extension will be loaded and ready to use.

## Usage

1. Open Gmail, compose or reply to an email.
2. Click the AI reply button (added by the Chrome extension).
3. AI generates a response with real-time preview.
4. Edit (if needed) and send with one click.

## Contributing

Pull requests are welcome. Open an issue for feature requests or bug reports.

## License

This project is licensed under **MIT License**.

---

This README gives a clear installation guide and project details. Let me know if you need any modifications! 🚀
