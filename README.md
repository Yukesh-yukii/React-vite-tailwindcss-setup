# React + Vite + Tailwindcss

# For running 
1) Download the Repo as Zip and extract and open in VsCode
2) <pre>npm install</pre>
3) <pre>npm run dev</pre>

# For mannual installation

1) <pre> npm create vite@latest setup -- --template react </pre>
2) <pre>npm install tailwindcss @tailwindcss/vite</pre>
3) Add below code in vite.config.ts file <pre>import tailwindcss from '@tailwindcss/vite' </pre> 
4) Add below code in plugins section onthe same file  <pre> tailwindcss(),</pre> 
5) Add the below codein src/index.css file <pre>@import "tailwindcss"; </pre>
6) <pre>npm run dev</pre>
7) To test the tailwind is working. In the App.jsx file update this line  className='text-red-400' in h1 tag

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
