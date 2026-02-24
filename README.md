# University Course Data Scraping

## Objective
This project is part of the **AI/ML & Web Scraping Data Entry Intern** assignment.  
The goal is to scrape universities and their courses from the web and submit the data in a structured Excel file.

## Repository Contents
- **`scraper.py`** — Python script that dynamically scrapes university and course data from the web.  
- **`university_courses_submission.xlsx`** — Submission-ready Excel file containing 6 universities with 5 courses each.  
- **`README.md`** — Project overview, instructions, and notes.  
- **`.gitignore`** — Ignores temporary files and Python cache.  

## How to Run
1. Ensure Python 3.x is installed.  
2. Install required libraries:  

```bash
pip install requests beautifulsoup4 pandas
```

3. Run the scraper:
```bash
python scraper.py
```
4. The Excel file (university_courses_submission.xlsx) will be generated or updated automatically in the project folder.

##Notes:

1. Universities Included: University of Texas at Austin, MIT, Stanford University, Harvard University, University of Oxford, University of Cambridge.

2. Courses: Each university includes 5 courses with details: course name, level, discipline, duration, fees, and eligibility (if available).

3. Data Integrity: Relational linking between universities and courses is maintained via unique IDs.

4. Temporary Excel files (~$…) are ignored using .gitignore.
