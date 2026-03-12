# Dream of Nihon 🌸

*A Japanese Language Learning Web Platform*

## 📁 Project Structure

```
dream-of-nihon/
│
├── index.html                # Main entry point of the application
│
├── pages/                    # All application pages
│   ├── home.html             # Landing page
│   ├── login.html            # User login page
│   ├── register.html         # User registration page
│   ├── dashboard.html        # User learning dashboard
│   ├── lesson-explorer.html  # Browse available lessons
│   ├── lesson-viewer.html    # View lesson content
│   ├── hiragana.html         # Hiragana learning module
│   ├── katakana.html         # Katakana learning module
│   ├── kanji.html            # Kanji learning module
│   ├── flashcards.html       # Flashcard practice page
│   ├── quiz.html             # Quiz interface
│   ├── progress-analytics.html # Learning analytics and progress
│   ├── profile.html          # User profile page
│   ├── settings.html         # User settings page
│   │
│   └── admin/                # Admin panel pages
│       ├── dashboard.html
│       ├── user-management.html
│       ├── lesson-management.html
│       ├── course-management.html
│       ├── quiz-management.html
│       ├── kanji-database.html
│       ├── kana-database.html
│       ├── flashcard-management.html
│       ├── course-builder.html
│       ├── roadmap-editor.html
│       ├── analytics-dashboard.html
│       ├── content-moderation.html
│       ├── achievement-management.html
│       ├── badge-management.html
│       ├── leaderboard-management.html
│       ├── system-logs.html
│       └── site-config.html
│
├── css/                      # Global styling files
│   ├── style.css             # Main styling
│   ├── components.css        # UI component styles
│   ├── admin.css             # Admin panel styles
│   └── responsive.css        # Mobile and responsive design
│
├── js/                       # Main JavaScript source code
│   │
│   ├── app.js                # App initialization
│   ├── router.js             # Frontend routing logic
│   │
│   ├── stores/               # State management
│   │   ├── auth-store.js
│   │   ├── user-store.js
│   │   ├── lesson-store.js
│   │   └── ui-store.js
│   │
│   ├── services/             # API and backend communication
│   │   ├── api.js
│   │   ├── auth.js
│   │   ├── lessons.js
│   │   ├── quiz.js
│   │   ├── progress.js
│   │   └── admin.js
│   │
│   ├── components/           # Reusable UI components
│   │   ├── navbar.js
│   │   ├── sidebar.js
│   │   ├── footer.js
│   │   ├── lesson-card.js
│   │   ├── flashcard.js
│   │   ├── quiz-question.js
│   │   ├── progress-chart.js
│   │   ├── data-table.js
│   │   ├── modal.js
│   │   └── toast.js
│   │
│   ├── utils/                # Helper utilities
│   │   ├── helpers.js
│   │   ├── validation.js
│   │   └── constants.js
│   │
│   └── data/                 # Mock data for development
│       ├── dummy-data.js
│       └── mock-api.js
│
├── assets/                   # Static resources
│   ├── images/               # Images and illustrations
│   ├── fonts/                # Custom fonts
│   └── icons/                # Icon assets
│
└── lib/                      # Third-party libraries
    ├── chart.js              # Chart library
    └── font-awesome/         # Font Awesome icons
```

---

## 📦 Key Features

* 📚 Interactive Japanese Lessons
* 🈶 Hiragana, Katakana, and Kanji Modules
* 🧠 Flashcards and Quizzes
* 📊 Learning Progress Analytics
* 👤 User Profiles & Settings
* 🛠 Full Admin Management System
* 🏆 Achievements, Badges, and Leaderboards

---

## 🧑‍💻 Tech Stack

* **HTML5**
* **CSS3**
* **JavaScript (Vanilla JS)**
* **Chart.js**
* **Font Awesome**

---

## 🎯 Goal

**Dream of Nihon** is designed to help learners master the Japanese language through structured lessons, quizzes, and interactive tools while allowing administrators to manage educational content efficiently.

---
