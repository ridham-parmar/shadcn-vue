# 📚 Project for Shadcn-Vue with Vue 3 and TailwindCSS@3 (Vite-based)

## 🚀 How the project was setup

1. **Created the project with Vite:**

   ```bash
   npm create vite@latest shadcn-vue -- --template vue-js
   ```

2. **Navigated into the project directory:**

   ```bash
   cd shadcn-vue
   ```

3. **Installed project dependencies:**

   ```bash
   npm install
   ```

4. **Ran the development server:**

   ```bash
   npm run dev
   ```

5. **Installed TailwindCSS, PostCSS, and Autoprefixer:**

   ```bash
   npm install -D tailwindcss@3 postcss autoprefixer
   ```

6. **Initialized TailwindCSS configuration:**

   ```bash
   npx tailwindcss init -p
   ```
   _(This command creates both `tailwind.config.js` and `postcss.config.js` files.)_

7. **Added `jsconfig.json`**  
   _(This file is used to properly resolve path aliases in your project.)_

8. **Installed Shadcn-Vue CLI (compatible with TailwindCSS v3):**

   ```bash
   npm install -D shadcn-vue@1.0.3
   ```
   _(If installing shadcn-vue@1.0.3 does not the packages like class-variance-authority, clsx, reka-ui, tailwind-merge, tailwindcss-animate then you need to manually install them)_

   ```bash
   npm i class-variance-authority@0.7.1 clsx@2.1.1 reka-ui@2.2.0 tailwind-merge@3.2.0 tailwindcss-animate@1.0.7
   ```

9. **Initialized Shadcn-Vue:**

   ```bash
   npx shadcn-vue@1.0.3 init
   ```
   _(This command creates a `components.json` file.)_

10. **Added a UI component (e.g., Button) using Shadcn-Vue:**

    ```bash
    npx shadcn-vue@1.0.3 add button
    ```

---

## ⚡ Running the Project

1. **Clone the repository:**

   ```bash
   git clone {repository-url}
   ```

2. **Navigate into the project folder:**

   ```bash
   cd {project-name}
   ```

3. **Install dependencies and start the dev server:**

   ```bash
   npm install
   npm run dev
   ```

4. **Access the application:**  
   Open your browser and visit: [http://localhost:5173](http://localhost:5173)

---


