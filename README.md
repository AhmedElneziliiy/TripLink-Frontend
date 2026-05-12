# TripLink — Egypt Trip Booking Frontend

<p align="center">
  <img src="https://img.shields.io/badge/Angular-19-DD0031?style=for-the-badge&logo=angular&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
</p>

> Angular 19 frontend for **TripLink** — a full-featured Egypt travel booking platform. Browse trip packages, book hotels, manage tours, and handle all travel needs in one app.

🔗 **Backend API**: [Egypt-Trip-Booking-API](https://github.com/AhmedElneziliiy/Egypt-Trip-Booking-API)

---

## ✨ Features

- **Landing Page** — Marketing homepage with trip highlights and search
- **Tourist Portal** — Browse and book Egypt trip packages
- **Hotels App** — Search, filter, and book hotels across Egypt
- **Tour Guides App** — Browse and hire certified tour guides
- **Tourism Company Portal** — Company dashboard for managing packages
- **Admin Dashboard** — Full admin panel for managing users, bookings, and content
- **Client App** — User account management and booking history
- **SSR Ready** — Angular Universal server-side rendering support

---

## 🏗️ Project Structure

```
src/app/
├── landing-app/         # Public homepage & marketing pages
├── tourist-app/         # Tourist browsing & booking flow
├── client-app/          # User account & booking history
├── hotels-app/          # Hotel search & reservation
├── tour-guides-app/     # Tour guide listings & booking
├── tourism-company-app/ # Company management portal
├── admin-app/           # Admin dashboard
└── shared-app/          # Shared components, services, guards
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+)
- [Angular CLI](https://angular.io/cli) v19

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/AhmedElneziliiy/TripLink-Frontend.git
   cd TripLink-Frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure API URL**

   Update `proxy.conf.json` or your environment file to point to the backend:
   ```json
   { "/api": { "target": "http://localhost:5000", "changeOrigin": true } }
   ```

4. **Run the development server**
   ```bash
   ng serve
   ```
   Navigate to `http://localhost:4200`

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Angular 19 | SPA framework |
| TypeScript | Type-safe development |
| Angular SSR | Server-side rendering |
| Angular CDK | UI component primitives |
| RxJS | Reactive programming |
| Bootstrap 5 | Responsive UI styling |

---

## 🔗 Related Repositories

| Repo | Description |
|------|-------------|
| [Egypt-Trip-Booking-API](https://github.com/AhmedElneziliiy/Egypt-Trip-Booking-API) | ASP.NET Core backend API |

---

## 📄 License

MIT License
