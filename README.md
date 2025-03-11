/src
  └── App.jsx
/components
  └── ui
      └── card.jsx
      └── button.jsx

{
  "name": "gidesh-supermarket",
  "version": "1.0.0",
  "main": "App.jsx",
  "dependencies": {
    "react": "^18.0.0",
    "react-dom": "^18.0.0",
    "framer-motion": "^10.0.0"
  },
  "devDependencies": {
    "vite": "^4.0.0",
    "@vitejs/plugin-react": "^4.0.0"
  },
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "start": "vite preview"
  }
}
import { defineConfig } from 'vite';
import react from '@vitejs/plugin-react';

export default defineConfig({
    plugins: [react()],
    server: {
        open: true,
    }
});
# GIDESH-SUPERMARKET