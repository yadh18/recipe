# 🍲 Recipe Rescue – Smart Recipe Recommendation App

**Cook smart. Waste less. Create more!**

Recipe Rescue is a beginner-friendly web application that recommends recipes based on the ingredients available at home. It helps students and bachelors prepare simple, affordable meals while reducing food waste and minimizing the need to buy extra ingredients.

## 📌 Problem Statement

Students and bachelors often have only a few ingredients at home and struggle to decide what to cook. Existing recipe applications may require users to search for a specific dish. Recipe Rescue solves this problem by recommending recipes based on the ingredients users already have.

## 🎯 Objectives

- Suggest recipes using available ingredients.
- Reduce food wastage.
- Help beginners cook easily.
- Save time when deciding what to cook.
- Reduce the need to buy extra ingredients.
- Provide simple cooking instructions.

## ✨ Key Features

- 🥕 **Ingredient-Based Search** – Enter the ingredients available at home.
- 🔍 **Smart Recipe Matching** – Find recipes that match your ingredients.
- 📊 **Recipe Ranking** – Display the most relevant recipes first.
- 🛒 **Missing Ingredients** – Identify additional ingredients needed.
- ⏱️ **Cooking Details** – View preparation time and difficulty level.
- 👨‍🍳 **Step-by-Step Instructions** – Follow simple cooking instructions.
- 📱 **Responsive Interface** – Designed for mobile and desktop screens.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend logic and recommendations |
| Flask | Backend web framework |
| HTML | Web page structure |
| CSS | Styling |
| JavaScript | Frontend interactions |
| Tailwind CSS | User interface styling |
| SQLite | Recipe database |
| difflib | Ingredient name matching |

## ⚙️ How It Works

1. The user enters the ingredients available at home.
2. The system standardizes the ingredient names.
3. The system compares the ingredients with recipes stored in the database.
4. A matching score is calculated for each recipe.
5. Recipes are ranked based on ingredient matches and other factors.
6. Recommended recipes and missing ingredients are displayed.
7. The user selects a recipe to view its ingredients and cooking instructions.

## 🏗️ System Architecture

```text
        User
          |
          v
    Web Interface
          |
          v
   Ingredient Input
          |
          v
    Flask Backend
          |
          v
  Recommendation Engine
          |
          v
    SQLite Database
          |
          v
     Recipe Ranking
          |
          v
 Recommended Recipes
          |
          v
 Recipe Details & Steps
```

## 📂 Project Structure

```text
Recipe-Rescue/
│
├── app.py
├── database.db
├── requirements.txt
├── README.md
│
├── templates/
│   ├── index.html
│   └── recipe.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
│
└── data/
    └── recipes.json
```

*Note: This is a suggested folder structure. Update it to match your actual project files.*

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- pip
- Visual Studio Code or another code editor
- A web browser

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/Recipe-Rescue.git
```

**2. Navigate to the project folder**

```bash
cd Recipe-Rescue
```

**3. Create a virtual environment**

```bash
python -m venv venv
```

**4. Activate the virtual environment on Windows**

```bash
venv\Scripts\activate
```

**5. Install dependencies**

If you have a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

Otherwise, install Flask:

```bash
pip install flask
```

**6. Run the application**

```bash
python app.py
```

Open the local URL displayed in your terminal. With Flask's default configuration, it is usually:

```text
http://127.0.0.1:5000
```

## 🔮 Future Enhancements

- Dietary preference filters.
- Regional cuisine recommendations.
- Voice-based ingredient input.
- Personalized recipe suggestions.
- AI-powered recipe generation.
- Expanded recipe database and improved matching accuracy.

## 🌱 Expected Impact

Recipe Rescue aims to make everyday cooking easier, especially for students and bachelors. By recommending meals based on ingredients already available at home, the application can help reduce food waste, save time, and encourage affordable home cooking.

## 👩‍💻 Development Tools

- Visual Studio Code
- Git
- GitHub
- Web Browser

## 🤝 Contributions

Suggestions, contributions, and improvements are welcome. You can contribute by suggesting new features, improving the interface, or expanding the recipe database.

## 📄 License

A license can be added when the project is ready for distribution. If you choose the MIT License, include a `LICENSE` file in the repository.

---

**Recipe Rescue — Your ingredients, your next meal! 🍳**
