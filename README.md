# CampusConnect — A Community Hub for Students

CampusConnect is a multi-page React web application designed to bring campus life into one
place — a single hub where students can log in, catch up on announcements, browse jobs, track
events, read/write blog posts, and discuss with peers.

## ✨ Features

- **Login Portal** — entry point for students to access the platform
- **Home Dashboard** — hero section, program highlights, campus gallery, testimonials, and
  a contact section, all in one scrollable landing page
- **Job Portal** — browse career opportunities and campus placement listings
- **Event Calendar** — interactive calendar (via React Big Calendar) to track campus events
- **Student Blog** — rich-text blog editor (React Quill / Draft.js) for students to write and
  format posts
- **Discussion Forum** — space for peer-to-peer discussion
- **Announcements** — campus-wide updates and notices
- **Testimonials** — student experiences and feedback
- **Smooth animations** throughout via Framer Motion

## 🛠️ Tech Stack

- **Frontend:** React 19, React Router DOM 7
- **Build tool:** Vite
- **Styling/UX:** Framer Motion (animations), React Icons, React Scroll
- **Rich text editing:** React Quill, Draft.js, draftjs-to-html
- **Calendar:** React Big Calendar
- **Data visualization:** Chart.js, React Chart.js 2
- **Linting:** ESLint

## 📂 Project Structure

```
CampusConnect/
├── index.html
├── package.json
├── vite.config.js
├── eslint.config.js
└── src/
    ├── App.jsx                  # Route definitions
    ├── Home.jsx                 # Landing page composition
    ├── assets/                  # Images, videos, icons
    └── components/
        ├── Navbar/
        ├── hero/
        ├── Programs/
        ├── Title/
        ├── About/
        ├── Campus/               # Gallery
        ├── Testimonials/ & Testimonial/
        ├── Contact/
        ├── Footer/
        ├── VideoPlayer/
        ├── Announcements/ & Announce/
        ├── EventCalendar/
        ├── LoginPortal/
        ├── StudentBlog/
        ├── JobPortal/
        └── DiscussionForum/
```

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (LTS recommended)
- npm (comes with Node.js)

### Installation

```bash
git clone https://github.com/Shruthi755/CampusConnect---A-Community-Hub-for-Students.git
cd CampusConnect---A-Community-Hub-for-Students
npm install
```

### Run in development

```bash
npm run dev
```

Vite will start a local dev server (default: `http://localhost:5173`) with hot module reload.

### Build for production

```bash
npm run build
npm run preview
```

### Lint

```bash
npm run lint
```

## 📍 Routes

| Path | Component |
|---|---|
| `/` | Login Portal |
| `/home` | Home (landing page) |
| `/JobPortal` | Job Portal |
| `/EventCalendar` | Event Calendar |
| `/StudentBlog` | Student Blog |
| `/Discussion` | Discussion Forum |
| `/Announce` | Announcements |
| `/Testimonial` | Testimonials |
| `/Hero` | Hero section (standalone) |

## 📸 Screenshots

_Add screenshots of the Home, Job Portal, Event Calendar, and Student Blog pages here._

## 🙋 Author

**Shruthi B**
[GitHub](https://github.com/Shruthi755)

## 📄 License

This project currently has no license file. Add one (e.g. MIT) if you intend for others to
reuse this code.
