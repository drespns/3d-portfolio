# Portfolio


## ⚙️ Setup (React + Vite)

```bash
npm create vite@latest ./ -- --template react
```

- TailwindCSS:
```bash
npm install -D tailwindcss
npx tailwindcss init
```

- Dependencies:
```bash
npm install --legacy-peer-deps @react-three/fiber @react-three/drei react-tilt maath react-vertical-timeline-component @emailjs/browser framer-motion react-router-dom

npm install @react-three/fiber
npm install @react-three/drei
npm install react-tilt
npm install maath
npm install react-vertical-timeline-component
npm install @emailjs/browser
npm install framer-motion
npm install react-router-dom
```
`--legacy-peer-deps` used with npm install to address potential peer dependency conflicts in your project.
Peer dependencies are packages that a module requires but doesn't directly depend on. Instead, it relies on the project using the module to provide these dependencies. This is common in libraries and frameworks that need to ensure the host application is using a compatible version of a shared dependency.

#### ⚙️ Vite template
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.
Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
