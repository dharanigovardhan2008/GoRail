# 🚂 GoRail

> A full-featured railway ticket booking web application built as a DBMS capstone project.

GoRail simulates the end-to-end experience of booking train tickets — from searching routes to managing reservations — powered by a modern React + TypeScript frontend backed by Firebase.

---

## ✨ Features

- **Train Search** — Search trains by source, destination, and date
- **Ticket Booking** — Reserve seats and manage passenger details
- **Booking Management** — View, track, and cancel bookings
- **User Authentication** — Secure login and registration via Firebase Auth
- **Admin Dashboard** — Manage trains, routes, and schedules (with Recharts analytics)
- **Real-time Updates** — Live data sync using Firebase Firestore
- **Responsive UI** — Mobile-friendly interface built with Tailwind CSS

---

## 🛠️ Tech Stack

| Layer        | Technology                          |
|--------------|-------------------------------------|
| Framework    | React 19 + TypeScript               |
| Build Tool   | Vite 7                              |
| Styling      | Tailwind CSS 4                      |
| Backend/DB   | Firebase (Auth + Firestore)         |
| Routing      | React Router DOM v7                 |
| Charts       | Recharts                            |
| Icons        | Lucide React                        |
| Notifications| React Hot Toast                     |
| Date Utils   | date-fns                            |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- A Firebase project

### Installation

```bash
# Clone the repository
git clone https://github.com/dharanigovardhan2008/GoRail.git
cd GoRail

# Install dependencies
npm install
```

### Firebase Setup

1. Go to [Firebase Console](https://console.firebase.google.com/) and create a new project.
2. Enable **Authentication** (Email/Password) and **Firestore Database**.
3. Copy your Firebase config and create a `.env` file in the root:

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### Running the App

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

---

## 📁 Project Structure

```
GoRail/
├── src/
│   ├── components/      # Reusable UI components
│   ├── pages/           # Route-level page components
│   ├── hooks/           # Custom React hooks
│   ├── lib/             # Firebase config & utilities
│   ├── types/           # TypeScript type definitions
│   └── main.tsx         # App entry point
├── index.html
├── vite.config.ts
├── tsconfig.json
└── package.json
```

---

## 📸 Screenshots

> _Add screenshots of the home, search, booking, and dashboard pages here._

---

## 🎓 About

GoRail was developed as a **Database Management Systems (DBMS) capstone project**, demonstrating real-world application design principles including:

- Relational data modeling translated to a NoSQL (Firestore) schema
- CRUD operations for trains, users, and bookings
- Role-based access (User vs Admin)
- Data aggregation and reporting via charts

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open a pull request or issue.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
  Made with ❤️ by <a href="https://github.com/dharanigovardhan2008">dharanigovardhan2008</a>
</div>
