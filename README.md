# 📰 Next.js GraphQL News Reader
### Next.js 13.4 App Router · GraphQL · StepZen · TypeScript · Dark Mode · Responsive

![Next.js](https://img.shields.io/badge/Next.js-13.4_App_Router-black?style=flat-square&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript)
![GraphQL](https://img.shields.io/badge/GraphQL-StepZen-E10098?style=flat-square&logo=graphql)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-3.x-06B6D4?style=flat-square&logo=tailwindcss)
![License](https://img.shields.io/badge/License-Educational-lightgrey?style=flat-square)

> A fast, responsive news reader built on Next.js 13.4 App Router — using StepZen to wrap a REST news API in a clean GraphQL layer, with category filtering, article detail views, and light/dark theme switching.

---

## 🏗️ Data Flow Architecture

```
MediaStack REST API
        │
        ▼
   StepZen Layer          ← Converts REST → GraphQL schema automatically
        │
        ▼
  GraphQL Endpoint
        │
        ▼
Next.js App Router        ← Server components fetch data at the edge
        │
        ▼
  React UI Components     ← Category filters · Article cards · Dark mode
```

**Why StepZen?** Rather than building a custom GraphQL server, StepZen introspects the MediaStack REST API and generates a type-safe GraphQL schema automatically — clean data querying without a dedicated backend.

---

## ✨ Features

- 🗂️ Browse news by category — filtered GraphQL queries per topic
- 📰 Detailed article view with full story rendering
- 🌗 Light / Dark theme switching via `next-themes`
- ⚡ Server-side rendering with Next.js App Router — fast initial page load
- 📱 Fully responsive UI built with Tailwind CSS
- 🕐 Relative timestamps via `react-time-ago`

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | Next.js 13.4 (App Router) |
| Language | TypeScript |
| UI Library | React.js |
| Styling | Tailwind CSS · Heroicons |
| Data Layer | GraphQL · StepZen |
| News Source | MediaStack API (REST) |
| Theme | next-themes (Dark / Light) |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/amarkumar55/News-application-next-app
cd News-application-next-app

# Install dependencies
npm install
# or
yarn install
```

### Environment Variables

Create a `.env.local` file in the root:

```env
STEPZEN_API_KEY=your_stepzen_api_key
MEDIASTACK_API_KEY=your_mediastack_api_key
```

```bash
# Start the development server
npm run dev
# or
yarn dev
```

Open **http://localhost:3000** in your browser.

---

## 📁 Project Structure

```
app/
├── page.tsx              # Home — news feed with category filter
├── layout.tsx            # Root layout — theme provider, global styles
├── components/           # ArticleCard, CategoryNav, ThemeToggle, etc.
├── graphql/              # StepZen schema + queries
└── styles/               # Global CSS
```

---

## 🌍 Use Cases

- News aggregation and content discovery platforms
- GraphQL-powered frontend demos
- REST-to-GraphQL transformation reference implementation
- Next.js 13 App Router architecture showcase

---

## 🔭 Roadmap

- [ ] Search functionality across articles
- [ ] Bookmarking and saved articles (localStorage)
- [ ] Infinite scroll / pagination
- [ ] PWA support for offline reading
- [ ] Additional news source integrations

---

## 👤 Author

**Amar Kumar** — Senior Backend Engineer · IBM Certified AI Engineer  
📌 [LinkedIn](https://www.linkedin.com/in/amarkumar241429017) · 💻 [GitHub](https://github.com/amarkumar55)

---

*REST wrapped in GraphQL, rendered at the edge — clean architecture from API to UI.*
