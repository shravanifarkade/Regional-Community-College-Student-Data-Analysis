# Regional Community College Student Data Analysis

## Purpose of the Project
The purpose of this project is to use **Amazon QuickSight** to analyze student enrollment data from Regional Community College. The project aims to uncover insights about professor effectiveness, course costs, and student satisfaction. By preparing datasets, building analyses, dashboards, Q Topics, Scenarios, and a Data Story, the project helps the college board understand key factors affecting student experience and provides actionable recommendations to improve outcomes without increasing course costs.

---

## Purpose of this README File
This README file documents the project, describes all created resources, and provides context for anyone reviewing the repository. It ensures that the project can be understood and reproduced, even without direct access to Amazon QuickSight. It also serves as a professional summary of work completed for submission or sharing.

---

## Dataset
- **Dataset Used:** Student Enrollment Statistics Sample Dataset (QuickSight)
- **Fields Included:**
Student Type, NationalOrigin, Gender, StudentClassification,
Course, Grade, TestScore, Semester, CourseId, Professor,
Credit, CostPerCourse, EvaluationScore, StudentName, StudentId,
AcademicYear, EnrollmentDate, GraduationDate, Major, Age


- **Calculated Field:**
Student Type = ifelse({Age} < 30, "Youth", "Adult Continuing Education")

- **Dataset Refresh Schedule:** Weekly, 12:00 AM on Sundays (local time zone)

---

## QuickSight Resources Created
### Datasets
- `Q - Student Enrollment` → includes calculated fields and renamed fields.

### Analyses
- `Q - Student Enrollment Analysis` → contains 6 visuals:
1. Student Majors by Year (Bar Chart)  
2. Proportion of Student Types (Pie Chart)  
3. Professors with Best Avg Evaluations  
4. Courses with Best Avg Evaluations  
5. Professors with Highest Avg Course Costs  
6. Courses with Highest Avg Course Costs  

### Dashboards
- `Student Enrollment Dashboard` → published dashboard with Q&A enabled and all visuals included.

### Topics
- `Regional Community College Student Data` → Q Topic for interactive analysis
- **Named Entities:**
1. Student Details  
2. Course Details  
3. Professor Evaluation  

### Scenarios
- `Improving Student Satisfaction Without Increasing Costs`  
- Starter Question: “How do we improve professor evaluations, while avoiding an increase in cost per course?”  
- Includes follow-up questions exploring factors influencing professor evaluations, course costs, and student types.

---

## Verified Q&A Questions
Examples of questions verified in the topic:
- Which instructors got the best average evaluations?  
- Which courses are the most expensive?  
- Which majors have highest average test scores?  
- What is the average cost per credit?  

---

## Data Story
- Demonstrates strategies to improve student satisfaction while minimizing costs.  
- Includes visuals:  
- Student Majors by Year  
- Proportion of Student Types  
- Avg Evaluation Score by Course  
- Avg Cost per Course  
- Prepared by: **Shravani Amol Farkade**

---

## Submission Files
- `Shravani_QuickSight_Project.docx` → contains all screenshots, visuals, scenario threads, verified Q&A answers, and data story.  
- `README.md` → project description and documentation.

---

## Author
**Shravani Amol Farkade**  
Division: A | Branch: Information Technology  
Email: shravanifarkade1604@gmail.com
---

## Notes
- All screenshots were captured for documentation purposes as per project submission guidelines.  
- Project completed using Amazon QuickSight sample datasets.

