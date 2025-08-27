# 🍳 Recipe Finder

A **React-based Recipe Finder App** that lets users browse recipes by categories and explore detailed cooking instructions. This project demonstrates **React fundamentals**, API integration, routing, and responsive UI design.  

---

# Live Demo - https://fast-eat-three.vercel.app/

## 🚀 Features

- 📂 **Browse by Categories** – Chicken, Dessert, Vegan, Pasta, Breakfast, etc.  
- 🔍 **Search Recipes** by name or ingredient.  
- 🖼️ **Recipe Cards** – Display recipes with images, titles, and categories.  
- 📋 **Recipe Details** – View ingredients, instructions, and images.  
- 🛠️ **Routing** – Implemented with `react-router-dom`.  
- 🎨 **Modern Styling** – Done with **Sass (SCSS)**.  
- 📱 **Responsive UI** – Works on desktop & mobile.  

---

## 🛠️ Tech Stack

- **React.js (v18)** – Component-based frontend  
- **React Router v6** – Navigation and routing  
- **Axios** – API calls  
- **Sass (SCSS)** – Styling  
- **React Icons** – For icons  
- **Create React App** – Boilerplate  

---

## 📂 Project Structure

my-app/
├── public/
│ └── index.html
├── src/
│ ├── components/
│ │ ├── CategoryCard.jsx
│ │ ├── Navbar.jsx
│ │ └── RecipeCard.jsx
│ ├── pages/
│ │ ├── Categories.jsx
│ │ ├── RecipeDetail.jsx
│ │ └── Home.jsx
│ ├── App.jsx
│ ├── App.scss
│ └── index.js
├── package.json
└── README.md



---

## ⚙️ Installation & Setup

1. **Clone this repo**
   ```bash
   git clone https://github.com/your-username/recipe-finder.git
   cd recipe-finder
2. **Install dependencies**
   ```bash
   npm install
3. **Start development server**
   ```bash
   npm start

📸 Screenshots
    UI
    ![Categories Screenshot](https://github.com/user-attachments/assets/e846c851-51b1-4c94-bd72-c62c83af13fe)

   🏠 Categories Page
   ![Recipe List Screenshot](https://github.com/user-attachments/assets/bcd3c65c-58a1-432a-9127-944e5e9cc626)
   
📦 Dependencies

   From package.json:

   ->react – Core library

   ->react-router-dom – For navigation

  ->axios – For API calls

  ->sass – For styling

  ->react-icons – For icons

🧩 Example API Call
```bash
import axios from "axios";

const fetchCategories = async () => {
  try {
    const response = await axios.get(
      "https://www.themealdb.com/api/json/v1/1/categories.php"
    );
    return response.data.categories;
  } catch (error) {
    console.error("Error fetching categories:", error);
  }
};
```

📝 Future Enhancements

❤️ Add "Favorites" (save recipes locally).

📌 Add filters (by diet, cuisine, difficulty).

🌍 Add multi-language support.

🛒 Generate shopping list from ingredients.
   

