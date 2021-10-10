# TailwindCSS Starter Pack With Vite

## **How To start**

### **Clone From:**

```
git clone https://github.com/ibnshayed/Tailwindcss-Starter-Pack-With-Vite.git
```

### **TailwindCss Build For Development:**

```
npm run dev
```

### **Start: On VS Code any live server**

## **How to Create this**

```
npm init -y
npm install -D tailwindcss@latest postcss-cli@latest autoprefixer@latest vite
```

### Tailwind Full Config

```
npx tailwind init --full ( change name to tailwind-default.config.css )
```

### Tailwind & Postcss Config

```
npx tailwind init -p
```

# tailwind.config.js

```javascript
'module.exports' = {
  'mode': 'jit',
  'purge': '["./**/*.html", "./src/**/*.{js,jsx,ts,tsx,vue}"]',
  'plugins': '[require("daisyui")]',
}
```

# package.json

```javascript
"scripts": {
    "dev": "vite",
    "build": "vite build",
    "serve": "vite preview"
  },
```
