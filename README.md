# 🌿 ePlant Shopping
A simple and modern **React + Redux Toolkit** shopping cart application powered by **Vite**.  
This project showcases a clean architecture for managing global state, adding/removing products from a cart, displaying product lists, and navigating basic sections such as *About Us*.

## 🚀 Features

### 🛒 Shopping Cart  
- Add items to the cart  
- Remove items  
- View total item count and pricing  
- Powered by **Redux Toolkit slices**

### 🧩 Modular Components  
- **ProductList** – displays available products  
- **CartItem** – handles UI for each item in the cart  
- **AboutUs** – simple informational page  
- **App** – global layout and routing  
- **Main** – React entry point  

### ⚙️ State Management  
- Global cart state using **@reduxjs/toolkit**  
- Store configuration via `store.js`  
- Efficient updates and reactivity using **react-redux**

### ⚡ Fast Development with Vite  
- Ultra-fast dev server  
- Modern build pipeline  
- Lightweight configuration (`vite.config.js`)

## 📁 Project Structure

```
eplantshopping/
│── index.html
│── README.md
│── package.json
│── vite.config.js
│── public/
│   └── vite.svg
│── src/
│   ├── App.jsx
│   ├── App.css
│   ├── AboutUs.jsx
│   ├── AboutUs.css
│   ├── ProductList.jsx
│   ├── ProductList.css
│   ├── CartItem.jsx
│   ├── CartItem.css
│   ├── CartSlice.jsx
│   ├── store.js
│   ├── main.jsx
│   ├── index.css
│   └── assets/
│       └── react.svg
```

## 🛠️ Technologies Used

- **React 18**
- **Redux Toolkit**
- **React Redux**
- **Vite 5**
- **ESLint + React plugin**
- **gh-pages** (for deployment)

## ▶️ Running the Project

### 1. Install dependencies
```bash
npm install
```

### 2. Start development server
```bash
npm run dev
```

### 3. Build for production
```bash
npm run build
```

### 4. Preview production build
```bash
npm run preview
```

## 🚀 Deployment (GitHub Pages)

```bash
npm run deploy
```

## 📜 License
This project is licensed under the MIT License.
