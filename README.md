# 🏅 Olympics Data Analysis

This project provides a complete data science pipeline applied to Olympic medal data from the Summer Games (1976–2008). It includes exploratory data analysis (EDA), machine learning for medal prediction, interactive visualization with Streamlit, and a detailed PowerPoint presentation.

---

## 📦 Dataset

- **File**: `Summer-Olympic-medals-1976-to-2008.csv`
- **Description**: Contains athlete-level records for Summer Olympics from 1976 to 2008, including:
  - Athlete Name
  - Gender
  - Country
  - Sport
  - Medal (Gold, Silver, Bronze)
  - Year

---

## 🔍 Project Features

### 📊 Exploratory Data Analysis (EDA)
- Medal distribution over the years
- Top countries by gold medals
- Gender participation insights
- Visualizations using Matplotlib & Seaborn

### 🤖 Machine Learning
- **Model**: Random Forest Classifier (scikit-learn)
- **Features**: Country, Sport, Year (encoded)
- **Target**: Medal Type
- **Evaluation**: Classification report & accuracy

### 🌐 Streamlit Web App
- User selects Country, Sport, and Year
- App predicts medal type
- Includes visuals and summary statistics
- Launch using: `streamlit run app.py`

### 🖼️ PowerPoint Presentation
- Professional presentation for project overview
- Includes all charts, insights, and model explanation

---

## 📁 Folder Structure

```
Olympics-Data-Analysis/
├── code.py                                                  # Streamlit web app
├── requirements.txt                                         # Python dependencies
├── README.md                                                # Project overview
├── Summer-Olympic-medals-1976-to-2008.csv                   # Dataset
├── Project_Report.pptx                                      # Final presentation
├── medal_label_encoder.pkl/olympics_medal_predictor.pkl     # pre-trained models for live predictions
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Olympics-Data-Analysis.git
cd Olympics-Data-Analysis
```

### 2. Install Requirements
```bash
pip install -r requirements.txt
```

### 3. Launch the Streamlit App
```bash
streamlit run app.py
```

---

## 📈 Sample Visualizations

- 📌 `Medals Over the Years` (Line Graph)
- 🥇 `Top 10 Countries by Gold Medals` (Bar Chart)
- 🚻 `Gender Participation Distribution` (Pie Chart)

---

## 🧠 Tools Used

- Python, Pandas, Matplotlib, Seaborn
- scikit-learn (ML modeling)
- Streamlit (interactive dashboard)
- PowerPoint (final presentation)

---

## 📌 Key Insights

- USA and Russia were consistent medal leaders
- Gender disparities exist in event participation
- Predictive models can effectively classify medal outcomes
- Streamlit simplifies presenting data interactively

---

## 📜 License

This project is developed for academic and educational purposes.

---

⭐ If you like this project, give it a star and share it!