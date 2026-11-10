# React Glassmorphism Profile Card 🚀

A modern, responsive glassmorphism profile card component built with **React 18** and **Tailwind CSS** for the **ApnoAI Internship (Task 2)**.

🔗 **Live Website:** [https://apnoai-task-2-harsh.vercel.app](https://apnoai-task-2-harsh.vercel.app)  
📂 **GitHub Repository:** [https://github.com/harshaljagdale0222/apnoai-task-2-harsh](https://github.com/harshaljagdale0222/apnoai-task-2-harsh)

---

## 🌟 Key Concepts Applied

- **🧩 Components:** Reusable `<ProfileCard />` component representing a self-contained UI block.
- **📥 Props:** External dynamic inputs passed into the component:
  - `name`: Full Name
  - `role`: Current Position / Title
  - `bio`: Professional summary
  - `skills`: Array mapped dynamically into chips
  - `avatar`: Profile image with automatic fallback to initials
  - `links`: Array of social/portfolio destination URLs
- **🧠 State (useState):**
  - `isDark`: Dynamic theme toggle between Light and Dark Glassmorphism modes.
  - `liked` & `likes`: Interactive heart like button with reactive counter (Challenge Option A).
  - `imgFailed`: Error boundary state handling missing/broken image URLs.

---

## 💻 Tech Stack

- **React 18:** Functional Components, Hooks (`useState`)
- **Babel Standalone:** In-browser JSX transformation (zero npm / zero build tools)
- **Tailwind CSS 3:** Utility classes and backdrop blur filters
- **Deployment:** [Vercel](https://vercel.com)

---

## 👤 Author

**Harshal Jagdale**  
- 💼 GitHub: [@harshaljagdale0222](https://github.com/harshaljagdale0222)  
- 🌐 Portfolio (Task 1): [apnoai-task-1-harsh.vercel.app](https://apnoai-task-1-harsh.vercel.app)  
- 📧 Email: [harshaljagdale40@gmail.com](mailto:harshaljagdale40@gmail.com)
