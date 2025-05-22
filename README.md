#!/bin/bash

# GitHub Profile Setup Script
# This script creates a GitHub profile repository and adds the README.md

echo "🚀 Setting up GitHub Profile Repository..."

# Variables
GITHUB_USERNAME="saurabbhcode"
REPO_NAME="saurabbhcode"
README_FILE="README.md"

# Create directory for the repository
mkdir -p $REPO_NAME
cd $REPO_NAME

# Initialize git repository
echo "📁 Initializing Git repository..."
git init

# Create README.md file
echo "📝 Creating README.md file..."
cat > $README_FILE << 'EOF'
# Hi there, I'm Saurabh Kumar! 👋

## 🚀 About Me
- 🎓 B.Tech in **Mathematics and Computing** from Delhi Technological University (2021-2025)
- 💻 Full Stack Developer passionate about building scalable web applications
- 📊 Data Analytics enthusiast with experience in machine learning and business intelligence
- 🌱 Currently exploring advanced web technologies and data science
- 💞️ Looking to collaborate on innovative web applications and data-driven projects
- 📫 Reach me at: **skeduc12@gmail.com**

## 🛠️ Tech Stack

### Languages
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### Frameworks & Libraries
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/-Express.js-000000?style=flat-square&logo=express&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

### Data & Analytics
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557c?style=flat-square&logo=python&logoColor=white)

### Databases
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

### Tools & Others
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?style=flat-square&logo=power-bi&logoColor=black)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Figma](https://img.shields.io/badge/-Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

## 💼 Work Experience

**Research & Data Analyst Intern** | Grid Controller of India Limited (July 2024 - August 2024)
- 🚀 Improved operational efficiency by 15% through data analysis methodologies
- 🌐 Contributed to bilingual website development, increasing user engagement by 20%
- 👥 Collaborated in Agile teams to enhance user engagement metrics by 25%

## 🚀 Featured Projects

### 🛒 E-Commerce Analytics Pipeline
- **Tech Stack:** Python (Pandas, NumPy), scikit-learn, SQL, SQLite
- 📊 Processed 50,000+ customer records with comprehensive data pipeline
- 🤖 Achieved 89% accuracy in customer churn prediction using Random Forest
- 📈 Improved stakeholder decision-making efficiency by 40%

### 🧠 AST-Based Rule Engine
- **Tech Stack:** Node.js, MySQL, REST APIs, HTML, JavaScript
- ⚡ Reduced admin tasks by 40% through visual configuration interface
- 🔧 Built dynamic rule processing engine with Abstract Syntax Trees

### 🌤️ Weather-Watch Real-Time Monitoring
- **Tech Stack:** Node.js, React.js, Chart.js, OpenWeatherMap API
- 📱 Increased user interaction by 30% with real-time weather insights
- ⚡ Reduced load time by 40% through caching and optimization

### 🏠 Wanderlust - Airbnb Clone
- **Tech Stack:** JavaScript, Node.js, Mongoose, MVC Architecture
- 🏘️ Manages 100+ accommodation listings with full CRUD operations
- 🚀 Reduced development time by 35% with scalable architecture

## 📈 GitHub Stats

![Saurabh's GitHub stats](https://github-readme-stats.vercel.app/api?username=saurabbhcode&show_icons=true&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=saurabbhcode&layout=compact&theme=radical)

## 🏆 Achievements & Certifications

- 🧩 **300+** LeetCode problems solved
- ⭐ **2-star** coder on CodeChef
- 🧛 **Vampire Badge** on Kaggle
- 📜 Completed **GeeksforGeeks API Bootcamp** (Sponsored by Postman)
- 🐍 Completed **"The Joy of Computing using Python"** (NPTEL)
- 🏅 **1st Place** in School-Wide Mental Maths Quiz
- 👨‍🏫 Mentored **5+ students** in Desh Ke Mentor program

## 📊 Coding Profiles

[![LeetCode](https://img.shields.io/badge/-LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/saurabbhcode)
[![CodeChef](https://img.shields.io/badge/-CodeChef-5B4638?style=flat-square&logo=codechef&logoColor=white)](https://codechef.com/users/saurabbhcode)
[![Kaggle](https://img.shields.io/badge/-Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://kaggle.com/saurabbhcode)

## 🤝 Let's Connect!

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/saurabh-kumar)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/saurabbhcode)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:skeduc12@gmail.com)

---
⭐️ From [saurabbhcode](https://github.com/saurabbhcode)
EOF

# Add README to git
echo "➕ Adding README.md to git..."
git add $README_FILE

# Initial commit
echo "💾 Making initial commit..."
git commit -m "feat: Add GitHub profile README with comprehensive portfolio"

# Add remote origin (you'll need to create the repository on GitHub first)
echo "🔗 Adding remote origin..."
git remote add origin https://github.com/$GITHUB_USERNAME/$REPO_NAME.git

# Set main branch
git branch -M main

echo "✅ Setup complete!"
echo ""
echo "📋 Next steps:"
echo "1. Go to https://github.com/new"
echo "2. Create a new repository named '$REPO_NAME'"
echo "3. Make sure it's PUBLIC"
echo "4. DON'T initialize with README (we already have one)"
echo "5. Run: git push -u origin main"
echo ""
echo "🎉 Your profile README will then appear on your GitHub profile!"
echo "📂 Files created in: $(pwd)"
