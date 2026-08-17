# AiformX
This a automatic form generator using the just simple prompt by user rest it do by it self. 
# AiFormX 🚀

> An intelligent, prompt-driven dynamic form generation platform built using the MERN stack.

AiFormX streamlines web form creation by transforming natural language user prompts into fully functional, dynamic forms. Instead of manually building inputs, dropdowns, and validation schemas, users describe what they need, and AiFormX auto-generates the corresponding UI modules and backend schemas instantly.

---

## 🌟 Key Features

* **Prompt-Driven Generation:** Automatically parses user prompts to determine required input types (text, selects, checkboxes, radio buttons) and validation rules.
* **Dynamic Form Rendering:** Custom state-driven UI modules render dynamic form schemas on the fly with seamless user interactions.
* **Client-Side Validation:** Instant input validation and feedback to ensure high data integrity before submission.
* **High-Performance Backend:** Node.js/Express REST APIs optimized for sub-100ms schema storage and retrieval from MongoDB.
* **Responsive UI:** Clean, modern interface designed for smooth navigation across desktop and mobile devices.

---

## 🛠️ Tech Stack

* **Frontend:** React.js, JavaScript (ES6+), CSS3, HTML5
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **API Testing & Tools:** Postman, Git, GitHub, Netlify / Vercel

---

## 📁 Repository Structure

```text
aiformx/
├── client/                 # React frontend application
│   ├── public/
│   └── src/
│       ├── components/     # Dynamic form components & UI elements
│       ├── context/        # State management modules
│       ├── pages/          # Primary views (Home, Builder, Preview)
│       └── App.js
└── server/                 # Node.js/Express backend API
    ├── config/             # Database connection setup
    ├── controllers/        # Form generation & schema controllers
    ├── models/             # MongoDB Mongoose schemas
    ├── routes/             # RESTful API endpoints
    └── server.js
