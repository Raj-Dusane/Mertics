# Mertics:
A modern and responsive admin dashboard application built with React, Syncfusion components, and TailwindCSS. This project demonstrates various functionalities such as data visualization, interactive charts, user management, and more.

 ## 📋 Table of Contents
1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🚀 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 📂 [Project Structure](#project-structure)

## <a name="introduction">🤖 Introduction</a>
This dashboard is designed for managing data, monitoring progress, and interacting with various widgets and tools. It includes reusable components, state management, and optimized layouts for a seamless user experience.

---

## <a name="tech-stack"> ⚙️️️ Tech Stack </a>
-  React
-  Syncfusion
-  TailwindCSS
-  CRACO
-  ESLint

---

## <a name="features"> 🚀 Features </a>
- **Interactive Charts**: Line, Bar, Pie, and other advanced charts using Syncfusion components. <br/>
- **Responsive Design**: Mobile-first design using TailwindCSS. <br />
- **State Management**: Context API for managing global state. <br/>
- **Pages**: Modular and optimized pages for an E-commerce Dashboard, User Management (Customers and Employees), Calendar, Kanban Board, Rich Text Editor, and Color Picker. <br/>
- **Reusable Components**: Modular design for headers, navigation, components.

---

## <a name="quick-start"> 🤸 Quick Start </a>
1. Clone the repository:
   ```bash
   git clone https://github.com/raj-dusane/Metrics.git
   cd Metrics
   ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```
4. Open the app in your browser at `http://localhost:3000`
    
---

## <a name="project-structure"> 📂 Project Structure </a>
```
Metrics/
├── README.md
├── craco.config.js             # Configuration for CRACO
├── license.txt                 # License information
├── package.json                # Project dependencies and scripts
├── tailwind.config.js          # TailwindCSS configuration
├── .eslintrc.js                # ESLint configuration
├── public/                     # Static files served by the app
│   ├── index.html              # Main HTML file
│   ├── manifest.json           # Web app manifest
│   └── robots.txt              # Robots exclusion protocol
├── src/                        # Source code
│   ├── App.css                 # Global styles
│   ├── App.js                  # Main application component
│   ├── index.css               # TailwindCSS styles
│   ├── index.js                # Entry point for React
│   ├── components/             # Reusable components
│   │   ├── Button.jsx
│   │   ├── Cart.jsx
│   │   ├── ChartsHeader.jsx
│   │   ├── Chat.jsx
│   │   ├── Footer.jsx
│   │   ├── Header.jsx
│   │   ├── Navbar.jsx
│   │   ├── Notification.jsx
│   │   ├── Sidebar.jsx
│   │   ├── ThemeSettings.jsx
│   │   ├── UserProfile.jsx
│   │   ├── index.jsx
│   │   └── Charts/
│   │       ├── LineChart.jsx
│   │       ├── Pie.jsx
│   │       ├── SparkLine.jsx
│   │       └── Stacked.jsx
│   ├── contexts/               # Context API for state management
│   │   └── ContextProvider.js
│   ├── data/                   # Mock data
│   │   └── dummy.js
│   └── pages/                  # Application pages
│       ├── Calendar.jsx
│       ├── ColorPicker.jsx
│       ├── Customers.jsx
│       ├── Ecommerce.jsx
│       ├── Editor.jsx
│       ├── Employees.jsx
│       ├── Kanban.jsx
│       ├── Orders.jsx
│       ├── index.jsx
│       └── Charts/
│           ├── Area.jsx
│           ├── Bar.jsx
│           ├── ColorMapping.jsx
│           ├── Financial.jsx
│           ├── Line.jsx
│           ├── Pie.jsx
│           ├── Pyramid.jsx
│           └── Stacked.jsx
└── .github/
```