# 🧠 Angular Project Structure

This project follows a modular and scalable architecture using Angular. Below is an overview of the folder structure and purpose of each directory.

---

## 📁 Project Structure

```
src/app/
├── Components/           # Reusable UI components shared across the app
├── Core/                 # Core building blocks and shared services
│   ├── Directives/       # Custom directives to extend HTML behavior
│   ├── Guards/           # Route guards for authentication and role-based access
│   ├── interceptor/      # Global HTTP interceptors (e.g., auth tokens, error handling)
│   ├── pipes/            # Custom pipes for transforming data in templates
│   ├── service/          # Core services (e.g., API, auth, storage)
│   └── shared/           # Shared models, types, constants, and utilities
├── Layout/               # App layout components (e.g., navbars, sidebars for student/instructor)
├── Pages/                # Main feature modules and app pages
│   ├── Auth/             # Login, register, forgot password
│   └── ...               # Other features (e.g., settings, reports)
└── routes/               # Application routing configuration and guards

```
