# Interview-Prep-Tracker
# Interview Prep Tracker 🎯

A comprehensive interview preparation management system to track job applications, interview rounds, questions asked, and analyze preparation patterns.

> **Built during placement season to solve a real problem I faced - keeping track of what questions came up where, and identifying my weak topics.**

## 🌟 Features

### Current Features
- **Company Management**: Track companies you've applied to with status updates
- **Interview Round Tracking**: Log multiple interview rounds per company (Online Assessment, Technical, HR, etc.)
- **Questions Bank**: Store questions asked during interviews with topic categorization
- **Analytics Dashboard**: 
  - Most frequently asked topics
  - Success rate analysis
  - Application timeline visualization

### Planned Features
- [ ] Export questions by topic for focused revision
- [ ] Preparation checklist per company
- [ ] Interview feedback notes
- [ ] Difficulty trend analysis

## 🗄️ Database Schema

### Tables Overview
```
Companies → Interview_Rounds → Questions
                ↓
              Notes
```

### Detailed Schema
**Companies**
- Stores company information and application status
- Tracks application timeline

**Interview_Rounds**
- Multiple rounds per company
- Round type, date, duration, and result
- Difficulty rating for self-assessment

**Questions**
- Questions asked in each round
- Topic and subtopic categorization
- Self-rated answer quality

**Notes**
- Additional feedback and observations per round

## 🛠️ Tech Stack

**Backend:**
- Python 3.x
- Flask/FastAPI (Web Framework)
- SQLAlchemy (ORM)
- SQLite/PostgreSQL (Database)

**Frontend:**
- HTML/CSS/JavaScript
- Bootstrap (Styling)
- OR Streamlit (Dashboard)

**Analytics & Visualization:**
- Pandas (Data manipulation)
- Matplotlib/Plotly (Charts)

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8+
pip
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/interview-prep-tracker.git
cd interview-prep-tracker
```

2. **Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Set up database**
```bash
python setup_db.py
```

5. **Run the application**
```bash
python app.py
```

6. **Access the application**
```
Open browser and go to: http://localhost:5000
```

## 📊 Sample Use Cases

**Scenario 1: After an Interview**
1. Add company if not exists
2. Create new interview round entry
3. Log all questions asked with topics
4. Add notes about interviewer feedback

**Scenario 2: Preparation Analysis**
1. View analytics dashboard
2. Identify most frequently asked topics
3. Export questions from weak topics
4. Focus revision accordingly

## 🎯 Key Interview Discussion Points

This project demonstrates:
- **Database Design**: Normalized schema, primary/foreign key relationships
- **SQL Proficiency**: Complex joins, aggregations, window functions
- **Backend Development**: RESTful API design, ORM usage
- **Data Analysis**: Query optimization, pattern recognition
- **Real-world Problem Solving**: Built to solve actual placement preparation challenges

## 📸 Screenshots

_Coming soon - will be added as features are completed_

## 🤝 Contributing

This is a personal project for learning and placement preparation, but suggestions are welcome!

## 📝 License

MIT License - feel free to use this for your own interview prep!

## 👤 Author

**Your Name**
- GitHub: [@ginah-p](https://github.com/ginah-p)
- LinkedIn: [Chantel_gina Pindula](www.linkedin.com/in/chantel-gina-pindula-a21739238)

---

**Project Status**: 🚧 In Development

**Current Phase**: Database Schema Design

**Last Updated**: October 2025
