# ResumeAI (browser-only version)

Single-file app: open `index.html` in a browser, or serve the folder:

    npx serve .        # or: python3 -m http.server 8000

## What it does
- Landing page, demo analysis, light/dark mode
- Local sign-up / sign-in (stored in localStorage; demo auth, not production security)
- PDF/DOCX upload, in-browser text extraction (pdf.js, mammoth via cdnjs)
- Rules-based scoring, skills, ATS checks, recommendations
- Job description matching, per-account history, print-to-PDF report

## Not included
Backend, database, real auth, LLM analysis, chat assistant, profile page.
Needs internet for the cdnjs libraries (pdf.js, mammoth).
