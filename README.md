# Blog Platform with Comments

A single-file full-stack blogging platform web application developed as part of the Thiranex Skill Development assignment. This application bundles backend logic, authentication, database management, and UI templates into a single, clean executable file.

---

## 🚀 Features

- **Single-File Architecture:** Utilizes Flask's `render_template_string` to pack the entire application cleanly inside `app.py`, eliminating template file configuration issues.
- **User Authentication:** Secure user signup and login architecture using `Flask-Login` and `pbkdf2:sha256` secure password hashing.
- **Full CRUD Capabilities:** Registered users can Create new posts, Read existing feeds, Update titles/contents, and Delete their own blog posts.
- **Interactive Comments Section:** Allows authenticated users to write comments directly underneath blog posts.
- **Automatic Database Setup:** Built-in SQLite automation via SQLAlchemy that generates the schemas seamlessly upon execution.

---

## 📂 Project Structure

```text
Internship/
│
├── app.py                 # Complete Application (Backend Logic + Inlined HTML Templates)
├── blog.db                # SQLite Database File (Automatically created on first run)
└── README.md              # Project Documentation# Blog-Platform-With-Comments
