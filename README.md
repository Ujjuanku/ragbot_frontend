# 💻 Acme Tech RAG Chatbot - Frontend

> **Role**: Senior Full Stack Developer Assessment  
> **Status**: Production Ready 🚀

The stunning, responsive frontend interface for the Acme Tech RAG Chatbot. Built with **React** and **Vite**, featuring a modern "Glassmorphism" design system that provides a premium user experience.

![Stack](https://img.shields.io/badge/Stack-React%20%7C%20Vite%20%7C%20CSS3-000000?style=for-the-badge&logo=react&logoColor=61DAFB) ![Deployment](https://img.shields.io/badge/Deploy-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

## ✨ key Features

- **Glassmorphism UI**: A consistent, translucent design language with blur effects and gradients.
- **Real-time Interaction**: Smooth chat interface with typing indicators and auto-scroll.
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile.
- **Robust Error Handling**: Graceful degradation and user feedback for network issues.
- **Dynamic Configuration**: Runtime environment variable injection for seamless deployment.

## 📂 Project Structure

```bash
frontend/
├── src/
│   ├── components/     # 🧩 Reusable React components
│   ├── api.js          # 🔌 Axios instance & API service layer
│   ├── App.jsx         # ⚛️ Main application container
│   ├── Chat.jsx        # 💬 Core chat logic & UI
│   └── styles.css      # 🎨 Global styles & design system
├── .env                # 🤫 Local environment variables
└── vite.config.js      # ⚡️ Vite configuration
```

## 🚀 Getting Started

### Prerequisites
- Node.js 16+
- NPM or Yarn
- Running Backend Service

### Local Development

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Ujjuanku/ragbot_frontend.git
    cd ragbot_frontend
    ```

2.  **Install Dependencies**:
    ```bash
    npm install
    ```

3.  **Environment Configuration**:
    Create a `.env` file in the root:
    ```env
    VITE_API_URL=http://localhost:8000
    ```
    *Note: The app automatically appends `/api` if needed.*

4.  **Run Development Server**:
    ```bash
    npm run start
    ```
    Access the app at `http://localhost:5173`.

## ☁️ Deployment (Vercel)

The frontend is optimized for **Vercel** serverless deployment.

1.  **Import Project**: Connect your GitHub repo to Vercel.
2.  **Configure Build**: Vercel automatically detects Vite.
    - Build Command: `npm run build`
    - Output Directory: `dist`
3.  **Environment Variables**: Add the backend URL to Vercel settings:
    - `VITE_API_URL`: `https://ragbot-production-6b35.up.railway.app`
4.  **Deploy**: Click deploy and watch your app go live!

## 🔗 Integration

This frontend connects to the `ragbot` backend. Ensure the backend CORS settings allow requests from your Vercel domain.

---
*Maintained by [Your Name]*
