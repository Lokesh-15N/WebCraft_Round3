# 🚀 EventVerse - Tech Fest Event Portal

**A fully accessible, dynamic, and responsive event information website for a college tech fest.**

Built with pure HTML, CSS, and JavaScript, EventVerse serves as the central digital hub for all fest information, designed for **maximum accessibility and user engagement** following strict **WCAG 2.1 Level AA guidelines**.

## 🎯 Project Goal

To create an inclusive, high-performance, and visually compelling event portal that demonstrates mastery of core web technologies and commitment to accessibility standards (WCAG AA) without relying on external frameworks or libraries.

## ✨ Key Features

### ♿ Accessibility & Inclusivity (WCAG AA Compliant)
* **Keyboard Navigation:** Full support for Tab, Enter, Space, and Escape. Includes a **Skip to main content** link and visible focus indicators.
* **Screen Reader Support:** Extensive use of **Semantic HTML5** elements and **ARIA roles/labels** for all dynamic and interactive components.
* **Visual Accessibility:** **WCAG AA contrast ratios** (minimum 4.5:1) for all text in both themes.
* **Form Accessibility:** Clear labels, real-time validation, and ARIA describedby for error announcements.
* **Reduced Motion Support** for users with vestibular disorders.

### 🎨 User Interface & Design
* **Theme Switcher:** Seamless toggle between:
    * **🌑 Dark Mode (The Cyberpunk Grid):** Futuristic, high-contrast, eye-strain-reducing theme.
    * **☀️ Light Mode (The Digital Blueprint):** Clean, professional, high-legibility theme.
* **Theme Persistence:** User's preference is saved in `localStorage`.
* **Modern Aesthetics:** Cyberpunk-inspired design with smooth animations and high-contrast colors.
* **Responsive Design:** Mobile-first approach optimized for all screen sizes (Mobile ≤ 480px, Tablet 481px - 768px).

### 🔍 Functionality
* **Dynamic Event Catalog:** Displays 18+ events across multiple categories.
* **Real-time Search:** Filter events by name or description.
* **Category Filters:** Technical, Cultural, Gaming, Workshops.
* **Smart Sorting:** Sort by name, date, or prize pool.
* **Event Modals:** Detailed view for rules, prizes, and contact information.
* **Registration Form:** Client-side validation with success feedback.

---

## 💻 Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic Document Structure |
| **CSS3** | Styling, Custom Properties (Variables), Grid & Flexbox Layouts, GPU-accelerated Animations |
| **Vanilla JavaScript (ES6+)** | DOM Manipulation, Dynamic Filtering, Sorting, Validation, and State Management (via localStorage) |

***Crucially, this project contains:***
✅ **No Frameworks** (e.g., React, Angular, Vue)
✅ **No Libraries** (e.g., jQuery)
✅ **No UI Toolkits** (e.g., Bootstrap, Tailwind)
✅ **No Backend/Server-Side Scripting** (Pure Frontend)

---

## 📂 Project Structure
TechFest/
│
├── index.html          # Main HTML structure
├── styles.css          # Complete styling with CSS variables
├── script.js           # All functionality and event data
└── README.md          # Project documentation
