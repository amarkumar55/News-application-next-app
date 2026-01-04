# 📰 Next.js GraphQL News Reader

A modern, responsive **News Reader Application** built using **Next.js 13.4**, **React**, and **GraphQL**, designed to deliver a fast and personalized news browsing experience with category filtering and theme switching.

The application leverages **StepZen** to simplify GraphQL integration over REST-based news APIs.

---

## 🚀 Overview

This application allows users to explore news articles across multiple categories, view detailed stories, and customize their reading experience with light and dark themes.

It is built using the latest **Next.js App Router**, ensuring optimal performance through server-side rendering and efficient data fetching.

---

## ✨ Key Features

- 🗂️ Browse news by categories
- 📰 Detailed article view
- 🌗 Light / Dark theme switching
- ⚡ Fast page rendering with Next.js App Router
- 🔄 GraphQL-based data fetching
- 📱 Fully responsive UI

---

## 🛠️ Technology Stack

### Frontend
- **Next.js 13.4 (App Router)**
- **React.js**
- **TypeScript**

### Data & APIs
- **GraphQL**
- **StepZen**
- **Media Stack API**

### UI & UX
- **Tailwind CSS**
- **Heroicons**
- **Next-Themes (Dark / Light Mode)**
- **React Time Ago**

---

## 🔄 Data Flow Architecture

```text
Media Stack API (REST)
↓
StepZen
↓
GraphQL
↓
Next.js App Router

```


This architecture enables clean data querying and efficient client-server communication.

---

## 📂 Project Structure (High-Level

```text
app/
├── page.tsx
├── layout.tsx
├── components/
├── graphql/
├── styles/
```


## ⚙️ Getting Started

### 1️⃣ Clone the Repository

```bash
          git clone https://github.com/amarkumar55/News-application-next-app
          cd Next.js-GraphQL-News-Reader
```

### Install Dependencies
     npm install
     # or
     yarn install

### Environment Variables

          Create a .env.local file and configure:
          
          STEPZEN_API_KEY=your_stepzen_api_key
          MEDIASTACK_API_KEY=your_mediastack_api_key

### Run the Application

          npm run dev
          # or
          yarn dev


Application will be available at:

          http://localhost:3000


🎯 Use Cases

          News aggregation platforms
          
          Content discovery applications
          
          GraphQL-powered frontend demos
          
          Next.js App Router learning projects


📌 Learning Highlights

          Next.js 13 App Router
          
          GraphQL integration using StepZen
          
          REST-to-GraphQL API transformation
          
          Theme management in Next.js
          
          Responsive UI design with Tailwind CSS

📄 License

This project is intended for educational and demonstration purposes.


