# AI Research Agent - Journey Log

## Day 1 - Setup
Python 3.11.9 confirmed
venv created and activated
crewAI 1.13.0 installed

Mistake: ran pip install outside venv
Fix: activate venv first, then install

Always create .gitignore before git add — never let venv/ get committed.
GitHub's file size limit is 100MB — never push large folders like venv/, node_modules/ etc.
Always check your branch name — local master must push to GitHub's main using git push origin master:main.