# NextJS & TailwindCSS

---
- npx create-next-app --example with-tailwindcss name


###  ***OR***


- npx create-next-app name
- cd name
- npm install -D tailwindcss postcss autoprefixer
- npx tailwindcss init -p
- to start -> npm run dev 
- rfce -> shortcut for start code
- npm run build -> to test for deploy on vercel .
- in tailwind.config.js :
  ```
    module.exports = {
    content: [
        "./pages/**/*.{js,ts,jsx,tsx}",
        "./components/**/*.{js,ts,jsx,tsx}",
    ],
    theme: {
        extend: {},
    },
    plugins: [],
    }
  ```
- in global.css :
  ```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
  ```
