# ResumeAI — Resume Analysis Website

**ResumeAI** is a browser-based resume analysis website that helps users review their resumes, identify skills, check ATS-style criteria, receive improvement recommendations, and compare resume content with a job description.

**GitHub Repository:** https://github.com/uduthaprashanth66/resume-ai

**Live Demo:** https://resume-analyser25.netlify.app/

## 1. Project Overview

ResumeAI is a web application developed using HTML, CSS, and JavaScript. It provides a user-friendly interface for analyzing resume content and displaying feedback in a structured report.

The application supports resume document uploads, browser-based text extraction, rules-based resume scoring, skills analysis, ATS-style checks, job description matching, and report printing.

This project demonstrates the practical application of front-end web development, JavaScript programming, document processing, and website deployment.

## 2. Problem Statement

Job applicants may find it difficult to identify missing information, relevant skills, and areas for improvement in their resumes. ResumeAI aims to simplify this process by providing basic resume checks and recommendations through a single web interface.

## 3. Project Objectives

- Develop a simple and user-friendly resume analysis website.
- Support PDF and DOCX resume uploads.
- Extract text from resumes directly in the browser.
- Evaluate resume content using predefined rules.
- Identify skills and check basic ATS-style criteria.
- Provide recommendations for improving resume content.
- Compare resume content with a job description.
- Generate a structured report that can be printed or saved as PDF.
- Deploy the website using Netlify and maintain the source code on GitHub.

## 4. Features

- **User Interface:** Interactive landing page with a clean layout.
- **Demo Sign-Up and Sign-In:** Browser-based demonstration authentication.
- **Resume Upload:** Supports PDF and DOCX files through client-side libraries.
- **Text Extraction:** Extracts text from uploaded documents in the browser.
- **Resume Scoring:** Calculates a score using predefined rules.
- **Skills Analysis:** Checks resume content for relevant skills.
- **ATS-Style Checks:** Evaluates selected resume criteria using programmed rules.
- **Recommendations:** Displays suggestions for improving resume content.
- **Job Description Matching:** Compares resume text with a provided job description.
- **Analysis Report:** Displays results in an organized format.
- **Report Printing:** Allows users to print or save the report as PDF through the browser.
- **Light and Dark Mode:** Provides a theme-switching option.

## 5. Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the website |
| CSS3 | Styling and layout |
| JavaScript | Application logic and interactive features |
| PDF.js | PDF text extraction |
| Mammoth.js | DOCX text extraction |
| Browser localStorage | Local demo account and data storage |
| Git | Version control |
| GitHub | Source code hosting |
| Netlify | Website deployment |

PDF.js and Mammoth.js are loaded through CDN links in the current implementation, so an internet connection is required for document extraction.

## 6. Working Methodology

1. The user opens the ResumeAI website.
2. The user accesses the available interface and demo sign-in feature.
3. The user uploads a supported resume or tries the available demo analysis.
4. The application extracts resume text in the browser.
5. JavaScript applies predefined rules to evaluate resume content.
6. The application checks skills and selected ATS-style criteria.
7. The user can enter a job description for comparison.
8. The website displays the score, analysis results, and recommendations.
9. The user can print the report or save it as PDF using the browser's print dialog.

## 7. Installation and Execution

### Requirements

- A modern web browser
- Internet connection for external document-processing libraries
- Visual Studio Code (optional)
- Live Server extension (optional)

### Steps to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/uduthaprashanth66/resume-ai.git
   ```

2. Open the project directory:

   ```bash
   cd resume-ai
   ```

3. Open the `resumeai` folder.

4. Open `index.html` in a web browser, or use the Live Server extension in Visual Studio Code.

## 8. Deployment

The ResumeAI website is deployed using Netlify, while GitHub is used to maintain the source code.

When GitHub is connected to Netlify for continuous deployment, updates pushed to the repository can be published automatically.

**Live Website:** [Add your actual Netlify URL here]

## 9. Project Structure

```text
resume-ai/
└── resumeai/
    ├── index.html
    └── README.md
```

## 10. Limitations

- Resume analysis uses predefined rules rather than a trained AI model or large language model.
- Sign-up and sign-in are demonstration features using browser localStorage, not secure production authentication.
- The current version does not include a backend server or centralized database.
- Stored browser data is not synchronized across devices.
- PDF and DOCX text extraction depends on external libraries and document compatibility.
- ATS-style scores are basic indicators and do not guarantee results from real applicant tracking systems.

## 11. Future Enhancements

- Integrate a genuine AI model or AI service for advanced resume analysis.
- Implement secure authentication.
- Develop a backend and database with appropriate privacy protections.
- Improve resume parsing and error handling.
- Provide more detailed job-specific skill matching.
- Add automated testing and accessibility improvements.
- Improve privacy controls and data management.

## 12. Learning Outcomes

This project provides practical experience in:

- Front-end web development using HTML, CSS, and JavaScript.
- Interactive user interface development.
- Browser-based document text extraction.
- Rule-based text analysis and scoring.
- Browser local storage.
- Git and GitHub version control.
- Static website deployment using Netlify.
- Technical documentation and project presentation.

## 13. Academic Project Details

- **Project Title:** ResumeAI — Resume Analysis Website
- **Student Name:** Prashanth Udutha
- **Course / Department:** B.Tech CSE (AI & ML)
- **College / University:** [Parul university]

## 14. Conclusion

ResumeAI provides a simple and accessible platform for reviewing resume content and identifying potential areas for improvement. The project demonstrates the use of front-end web technologies, browser-based document processing, rules-based analysis, and cloud deployment.

It also provides a foundation for future improvements, including secure authentication, backend integration, and advanced AI-powered resume analysis.

## 15. License

No open-source license has been specified for this project. Please confirm the intended usage and licensing terms before distributing or reusing the source code.
