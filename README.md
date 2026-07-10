# Virtual Identity Card — Flask Web App

## Overview
A personal virtual identity card built with Python and Flask. The app renders a styled HTML page displaying personal information in a clean card format — served using Flask's template rendering and static file support.

Built as part of **Dr. Angela Yu's 100 Days of Code: The Complete Python Pro Bootcamp** — Day 56.

## What It Does
- Serves a personal identity/business card as a web page
- Uses Flask's `render_template()` to serve an HTML file
- Applies custom CSS styling via Flask's static file handling
- Demonstrates separation of concerns between Python logic, HTML structure, and CSS styling

## Technologies Used
- Python 3
- Flask (web framework)
- HTML5
- CSS3

## How To Run
```bash
pip install flask
python main.py
```
Then open your browser and navigate to `http://localhost:5000`

## Project Structure
```
day-56-virtual-card/
├── main.py           # Flask application
├── templates/
│   └── index.html    # HTML card template
├── static/
│   └── assets/
│       └── styles.css  # Card styling
└── README.md
```

## Key Concepts Learned
- Flask `render_template()` for serving HTML files
- Flask static file handling for CSS and assets
- Jinja2 templating basics
- Structuring a Flask project with templates and static folders

## About
Built as part of [100 Days of Code](https://www.udemy.com/course/100-days-of-code/) by Dr. Angela Yu.
