
# SQL Learning Studio

**SQL Learning Studio** is a modern, browser-based online SQL compiler that allows users to write, execute, and visualize SQL queries in real-time. It provides a friendly interface for learning and experimenting with SQL commands without the need to install a local database.

---

## 🌟 Features

- **SQL Editor**  
  - Write and execute SQL queries using a powerful Monaco-based editor.  
  - Supports keyboard shortcuts (Ctrl+Enter) for quick execution.

- **Query Execution & Results**  
  - Execute `SELECT`, `INSERT`, `UPDATE`, `DELETE`, `CREATE`, `DROP` commands.  
  - Results displayed in a clean, responsive table format.  
  - Supports syntax highlighting for easier readability.

- **Database Schema Viewer**  
  - View all tables and columns dynamically.  
  - Shows row count and column data types.

- **Query History**  
  - Tracks executed queries with timestamps.  
  - Click history items to re-run or edit queries.

- **Responsive Design**  
  - Fully mobile-friendly using Tailwind CSS.  
  - Clean, modern UI inspired by IDEs.

---

## 🛠️ Technologies Used

- **Frontend:**  
  - HTML, CSS, JavaScript  
  - [Tailwind CSS](https://tailwindcss.com/) for UI  
  - [Monaco Editor](https://microsoft.github.io/monaco-editor/) for SQL editing  
  - [Lucide Icons](https://lucide.dev/) for UI icons

- **Backend:**  
  - Optional: Node.js + Express + SQLite (for local testing)  
  - Recommended: [Supabase](https://supabase.com/) for cloud-hosted PostgreSQL backend and API  
  - REST API or Edge Functions for executing SQL commands

- **Other Tools:**  
  - Fetch API for communicating with backend  
  - Responsive design with CSS Grid and Flexbox  

---

## 💻 Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/Tanishka761/SQL-Learning-Studio.git
cd sql-learning-studio
