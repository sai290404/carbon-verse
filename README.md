
# 🌍 CarbonVerse — Explore Your Carbon World

**CarbonVerse** is a personalized carbon footprint calculator that helps individuals evaluate and reduce their monthly carbon emissions. Built with **Streamlit** and **machine learning**, the app empowers users with awareness and actionable insights across categories such as **diet, travel, energy**, and **waste**.

---

## 🎯 Project Objective

Every action we take — from how we commute, what we eat, to how much energy we consume — contributes to CO₂ emissions. CarbonVerse aims to raise awareness and encourage sustainable living by:

* Estimating monthly carbon emissions based on lifestyle inputs  

* Breaking down emissions by category: Travel, Energy, Diet, Waste  

* Suggesting actionable reductions and tree-planting offsets  

---

## ⚙️ How It Works

The app collects inputs across five lifestyle areas:

* **Personal Information** – body metrics, diet, social activity  

* **Travel** – preferred transport mode, distance, air travel  

* **Waste** – bag size, recycling behavior  

* **Energy Use** – heating, cooking methods, screen/internet time  

* **Consumption** – groceries and clothing habits  

Your responses are processed and passed to a **pre-trained MLPRegressor** to calculate your monthly **kgCO₂e** (kilograms of CO₂ equivalent).

---

## 📊 You’ll Receive

* A personalized footprint breakdown chart  

* A total emission estimate  

* The number of trees needed to offset your carbon impact  

* A direct link to a tree donation portal  

---

## 🚀 Features

* Interactive multi-tab Streamlit interface  

* Pre-trained machine learning model for carbon footprint prediction  

* Emissions breakdown by category: Travel, Energy, Diet, Waste  

* Custom visual report with chart overlays  

* Enhanced UI styling with CSS and JavaScript  

* "Did You Know" pop-ups for carbon awareness  

* Built-in tree offset calculator with donation link  

---

## 🛠️ Tech Stack

### Backend

* **Pandas**, **NumPy** – data handling and transformation  

* **scikit-learn** – regression model for predictions  

* **pickle** – to load pre-trained model and scaler  

* **Matplotlib**, **Pillow** – visualization and annotated image generation  

### Frontend

* **Streamlit** – rapid frontend interface  

* **HTML**, **CSS**, **JavaScript** – UI customization and interactivity  

* **Base64** – image handling and encoding  

---

## ▶️ Getting Started

```bash
# Clone the repository
git clone https://github.com/loukhyachundi/CarbonVerse.git
cd CarbonVerse

# Install required packages
pip install -r requirements.txt

# Launch the app
streamlit run app.py
```

---

## 📸 Sample Output

* Interactive monthly emission chart  

* Visual overlay with CO₂ summary  

* Emission breakdown by Travel, Energy, Diet, and Waste  

---

## 🌳 Offset Your Footprint

Once your footprint is calculated, the app estimates how many trees you need to plant monthly to offset it. You can proceed to [tema.org.tr](https://www.tema.org.tr/en/homepage) to support reforestation efforts.


---

## 📂 Repository

Explore the full source code and contribute to the project:  
👉 [https://github.com/loukhyachundi/CarbonVerse](https://github.com/loukhyachundi/CarbonVerse)
