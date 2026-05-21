# WHODAS 2.0 (36-Item) Assessment Web App

A modern, responsive, and interactive web-based implementation of the **WHO Disability Assessment Schedule (WHODAS 2.0)** using the official **36-item structure** from the World Health Organization (WHO).

This application helps users evaluate functional limitations and disability levels across six major domains of daily life based on activities during the last 30 days.

---

## ✨ Features

- ✅ Full WHODAS 2.0 (36-item) questionnaire
- ✅ 6 functional disability domains
- ✅ Interactive multi-step assessment interface
- ✅ Real-time progress tracking
- ✅ Domain-based navigation sidebar
- ✅ Automatic scoring calculation
- ✅ Global disability percentage result
- ✅ Disability severity classification
- ✅ Radar chart visualization using Chart.js
- ✅ Responsive UI (Desktop & Mobile)
- ✅ Built with TailwindCSS
- ✅ Pure HTML + JavaScript (No backend required)

---

## 🧠 Assessment Domains

The application evaluates six core WHODAS domains:

| Domain | Description |
|---|---|
| Cognition | Understanding & communication |
| Mobility | Moving & walking |
| Self-care | Hygiene, dressing, eating |
| Getting Along | Interaction with other people |
| Life Activities | Household/work/school activities |
| Participation | Community & social participation |

---

## 📊 Scoring Method

This application uses the **Simple Scoring Method**:

Domain Score (%) =
((Sum of Responses - Number of Items) / (Number of Items × 4)) × 100

Global score:

Global Disability (%) =
((Total Score - 36) / (36 × 4)) × 100
🏷 Disability Classification
Percentage	Category
0–4%	No Disability
5–24%	Mild Disability
25–49%	Moderate Disability
50–95%	Severe Disability
96–100%	Complete Disability
🛠 Technologies Used
HTML5
TailwindCSS
Vanilla JavaScript
Font Awesome
Chart.js
Google Fonts (Inter)
📱 User Interface Highlights
Smooth animated transitions
Clean medical-style dashboard UI
Domain completion indicators
Mobile-friendly layout
Radar chart analytics visualization
🚀 Getting Started
1. Clone Repository
git clone https://github.com/yourusername/whodas-assessment.git
2. Open Project

Simply open:

index.html

in your browser.

No installation or server required.

📂 Project Structure
whodas-assessment/
│
├── index.html
├── README.md
│
└── assets/
    └── (optional future assets)
📈 Radar Chart Analytics

The app generates a radar chart showing disability severity across all domains, helping users visualize functional strengths and limitations.

⚠ Disclaimer

This application is intended for:

Educational purposes
Research
Preliminary functional assessment
Digital health prototyping

It is NOT a substitute for professional medical diagnosis or clinical judgment.

For clinical use, consultation with licensed healthcare professionals is strongly recommended.

🌍 About WHODAS 2.0

WHODAS 2.0 is developed by the World Health Organization (WHO) as a standardized instrument for measuring health and disability across cultures.

It is based on the International Classification of Functioning, Disability and Health (ICF).

🔮 Possible Future Improvements
PDF report export
User authentication
Database integration
Multi-language support
Dark mode
Offline PWA support
Advanced WHO complex scoring algorithm
Clinical dashboard analytics
Accessibility enhancements
👨‍💻 Author

Developed by Angga Saputra

Public Policy • Digital Systems • Health Innovation • Data Visualization
