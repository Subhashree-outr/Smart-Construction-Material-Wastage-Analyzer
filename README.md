# Smart-Construction-Material-Wastage-Analyzer

A web-based application that analyzes construction material usage and identifies potential wastage by comparing actual material consumption with estimated ideal requirements.

The system calculates material wastage, estimated financial loss, and provides practical suggestions to improve material management at construction sites.

## 🚀 Features

* Calculate expected material requirements based on building area
* Compare actual vs. estimated material usage
* Calculate material wastage percentage
* Estimate cost lost due to excess material usage
* Analyze cement, sand, and steel usage
* Provide suggestions to reduce material wastage
* Store project analysis data using SQLite
* Simple and user-friendly web interface

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS
* **Backend:** Python, Flask
* **Database:** SQLite
* **Development Environment:** VS Code

## 📊 Materials Analyzed

The current version analyzes:

* Cement — bags
* Sand — cubic meters (m³)
* Steel — kilograms (kg)

## ⚙️ How It Works

```text
User enters construction details
            ↓
Building area + material usage + cost
            ↓
Calculate estimated material requirement
            ↓
Compare actual vs estimated usage
            ↓
Calculate wastage percentage
            ↓
Estimate financial loss
            ↓
Generate recommendations
            ↓
Store analysis in SQLite
```

## 🧮 Calculation

The application uses predefined estimation factors to calculate approximate material requirements.

### Expected Material Requirement

```text
Expected Cement = Building Area × Cement Factor

Expected Sand = Building Area × Sand Factor

Expected Steel = Building Area × Steel Factor
```

### Material Wastage

```text
Excess Material = Actual Usage − Expected Usage

Wastage % = (Excess Material / Expected Usage) × 100
```

### Estimated Cost Loss

```text
Cost Loss = Excess Material × Material Cost
```

> **Note:** The estimation factors used in this student project are approximate and intended for educational analysis. Actual construction requirements vary depending on structural design, building type, material specifications, and engineering standards.

## 📁 Project Structure

```text
SmartConstructionWasteAnalyzer/
│
├── app.py
├── database.db
├── requirements.txt
│
├── templates/
│   ├── index.html
│   └── result.html
│
└── static/
    └── style.css
```

## 💻 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/SmartConstructionWasteAnalyzer.git
```

### 2. Open the project

```bash
cd SmartConstructionWasteAnalyzer
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

### 5. Open in browser

```text
http://127.0.0.1:5000
```

## 📦 requirements.txt

```text
Flask
```

## 🖥️ Example Output

The system provides:

```text
Expected Cement: 400 bags
Expected Sand: 18 m³
Expected Steel: 4000 kg

Cement Wastage: 12%
Sand Wastage: 8%
Steel Wastage: 10%

Estimated Cost Loss: ₹XXXX

Suggestions:
- Improve material storage
- Optimize material handling
- Improve site supervision
- Plan steel cutting more efficiently
```

## 🎯 Objective

The primary objective of this project is to demonstrate how software can help construction teams monitor material consumption, identify potential wastage, estimate financial losses, and make better material-management decisions.

## 🔮 Future Scope

The project can be further enhanced with:

* Machine Learning-based wastage prediction
* Interactive dashboards and graphs
* PDF report generation
* Project-wise historical analysis
* Material price APIs
* User authentication
* Construction progress tracking
* Weather-based material management recommendations
* Mobile application
* AI-powered construction optimization

## 🌱 Sustainability Impact

Reducing construction material wastage can help minimize unnecessary resource consumption and financial losses. The project demonstrates a technology-based approach toward more efficient and sustainable construction practices.

## 👩‍💻 Author

**Subhashree**

B.Tech — Computer Science & Engineering

## 📄 License

This project is developed for educational and academic purposes.
