# resume-job-matcher
LLM-powered resume reviewer that matches resumes to job postings and provides feedback
# Resume Job Matcher

This project analyzes resumes against job postings and provides:

- Match percentage
- Missing skills
- Recommended keywords
- Resume rewording suggestions
- Estimated improved match after updates

## How it works

1. Extracts skills from resumes and job descriptions
2. Compares skill overlap
3. Identifies gaps
4. Suggests improvements based on job language

## Features

- Random resume vs random job comparison
- Multi-industry skill matching (data, finance, marketing, etc.)
- Feedback generation for weak matches
- Estimated improvement scoring

## Tech Stack

- Python (Jupyter Notebook)
- Rule-based NLP
- Skill taxonomy system
- Planned: Groq LLM integration + web UI

## Future Improvements

- LLM-powered bullet rewriting
- Resume tailoring per job
- Frontend using Lovable
