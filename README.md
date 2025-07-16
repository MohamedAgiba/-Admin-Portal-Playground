# 🧩 Admin Portal Playground

A personal **Angular 20 + PrimeNG 20** playground to build a modern **Admin Dashboard** from scratch.  
This project simulates a real-world frontend workflow and is used to practice architecture, UI/UX design, and hands-on feature development in a structured environment using the latest Angular features like **Signals**, **Control Flow**, and **Standalone APIs**.

---

## 🚀 Features

- Modern admin dashboard layout  
- Modular Angular 20 architecture  
- PrimeNG 20 with Tailwind CSS  
- Angular Signals and new control flow syntax  
- Reusable shared components  
- Form validation best practices  
- Responsive design (Desktop & Mobile)  
- Simulated tasks & sprints for practice  

---

## 🛠️ Tech Stack

- Angular 20  
- PrimeNG 20  
- Tailwind CSS  
- RxJS  
- TypeScript  
- SCSS  

---

## 📦 Project Setup

```bash
# Clone the repo
git clone https://github.com/your-username/admin-portal-playground.git
cd admin-portal-playground

# Install dependencies
npm install

# Run the development server
ng serve
```
## 📁 Project Structure
src/
├── app/
│   ├── @core/         # Core services, guards, interceptors
│   ├── @shared/       # Reusable components, pipes, directives
│   ├── features/      # Feature modules (users, leads, models, etc.)
│   ├── layout/        # Shell and navigation components
│   └── app.config.ts  # App configuration with provideRouter, provideHttpClient...
├── assets/
├── environments/

## 🧠 Learning Goals
Deepen understanding of Angular 20 features: Signals, Control Flow, Standalone APIs

Practice component-driven development with PrimeNG 20

Simulate real team workflows: Git, commits, tasks, and refactors

Improve design implementation with Tailwind and modern patterns****

## 📆 7-Day Sprint Plan
This project follows a 7-day simulated sprint. Each day focuses on practical, hands-on tasks covering both Angular and PrimeNG.

✅ Day 1: Project Kickoff & Setup
 Create project with Angular 20

 Setup PrimeNG 20 & TailwindCSS

 Add basic routing & layout shell

 Setup folder structure: @core, @shared, features

⏳ Day 2: Authentication UI
 Create login page using PrimeNG form components

 Add form validation and error messages

 Create basic auth service (mock)

⏳ Day 3: Users Module
 Add users-list page using p-table

 Create dynamic filters using FormGroup

 Use custom cell templates (status color, name as link)

⏳ Day 4: Add/Edit User
 Create add-user form using Reactive Forms

 Use p-dropdown, p-inputText, etc.

 Show validation errors (custom component)

⏳ Day 5: Models Module
 Create models-list like users

 Add color status, links, etc.

 Reuse components between features

⏳ Day 6: Shared Components & Services
 Extract shared button, input, error component

 Add MessageService for toasts

 Organize services under @core

⏳ Day 7: Polish & Review
 Add loading states, empty states

 Refactor duplicated code

 Push final version, write PR description

## 💡 Notes
This is a self-driven learning environment. Tasks are added incrementally, simulating a realistic development sprint.
PRs, branches, commits, and architecture decisions are treated as if it's a production-level admin panel.

## 📌 License
MIT — feel free to use this as a learning template.
