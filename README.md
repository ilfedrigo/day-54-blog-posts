## Overview
In my 54 day of coding in Python I developed a simple blogging application using Flask, a micro web framework for Python. 

The application fetches blog posts from an API, displays them on the homepage, and allows users to view individual posts.

## Technologies Used
- Python
- Flask
- HTML/CSS
- Requests library

## Project Structure
- `main.py`: This file contains the main Flask application code. It fetches blog posts from an API, creates `Post` objects, and renders templates to display the posts.
- `post.py`: This module defines the `Post` class, which represents a single blog post. Each `Post` object has attributes such as ID, title, subtitle, and body.
- `index.html`: This HTML template displays all the blog posts on the homepage. It iterates over the list of `Post` objects and generates cards for each post.
- `post.html`: This HTML template is used to display individual blog posts. It shows the title, subtitle, and body of the selected post.

## Getting Started
- Just run the application locally with Python3 and Flask
