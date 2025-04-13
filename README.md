# React + Vite

# For running 
1) Download the Repo
2) npm install
3) npm run dev

# For mannual installation

1) npm create vite@latest setup -- --template react
2) npm install tailwindcss @tailwindcss/vite
3) Add -> import tailwindcss from '@tailwindcss/vite' in vite.config.ts file
4) Add -> tailwindcss(), in plugins section onn the same file 
5) add -> @import "tailwindcss"; in src/index.css file 
6) npm run dev
7) To test the tailwind is working. In the App.jsx file update this line <h1 className='text-red-400'>Vite + React</h1>



This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
