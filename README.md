# AI-Career-Mentor-Agent-for-School-College-Students
FutureGuide is an AI-powered mentorship agent designed to support school and college students with personalized, reliable, and accessible career guidance. Many students struggle to choose the right path due to limited counseling resources and the fast-changing job market. 
# 🎓 AI Career Mentor Agent for Students  
**Google Capstone Project | SkillBridge Course**  

An intelligent multi-agent system designed to help school and college students understand their strengths, plan their careers, analyze skills, evaluate resumes, and receive personalized recommendations.

This project is fully implemented end-to-end using Generative AI APIs and includes 4 major modules:
1. **Career Roadmap Generator**  
2. **Skills Gap Analyzer**  
3. **Resume Analyzer (ATS Simulation)**  
4. **Personality & Interest Test**

---

## 🚀 Project Overview

Students often struggle with:
- Choosing a career  
- Understanding required skills  
- Planning their learning roadmap  
- Improving resumes  
- Finding what job role fits their personality  

This AI agent solves all these problems using a single, modular, intelligent system.

It works like a **career counsellor chatbot** that guides students based on their inputs.

---

## 🧠 Features

### ✅ **1. Career Roadmap Generator**
Enter any career → AI generates:
- Required technical skills  
- Certifications to do  
- 12-month learning plan  
- Projects to build  
- Internship preparation steps  

Example:
```python
generate_career_roadmap("Cloud Engineer")

####✅ 2. Skills Gap Analyzer

Compares:
Your current skills
The skills needed for your target career
Provides:
Missing skills
Step-by-step learning path
Free resources
Example:
     skills_gap_analysis("python, linux basics", "Cloud Engineer")

##### ✅ 3.Resume Analyzer (ATS Score)
  -Paste your resume → AI returns:
  -Strengths & weaknesses
  -Missing keywords
  -ATS score
  -Improvement ideas
Example:
analyze_resume("Experienced student with interest in cloud computing...")

######✅ 4. Personality & Interest Test
simple 6-question test reveals:
-Personality type
-Strengths
-Suggested career roles
-skill-building plan
Example:
personality_test("""
1. I enjoy solving logical problems: Yes
2. I like working with people: Medium  
3. I prefer structured tasks: Yes  
4. I like technology: High  
5. I get bored doing repetitive work: Yes  
6. I enjoy learning new skills: High
""")

#######🛠️ Tech Stack
| Component  | Technology                    |
| ---------- | ----------------------------- |
| Language   | Python                        |
| Notebook   | Kaggle                        |
| AI Model   | Google Generative AI (gemini) |
| Tools      | GenAI API, GitHub, Kaggle     |
| Deployment | GitHub Repository             |

AI-Career-Mentor-Agent/
│
├── career_agent.ipynb          # Kaggle Notebook
├── README.md                   # Documentation
├── requirements.txt            # Libraries
└── /assets                     # Images, diagrams (optional)



