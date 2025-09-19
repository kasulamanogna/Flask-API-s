# Flask Web Application: To-Do List API & Student Score Management

## Overview

This project is a beginner-friendly Flask web application that demonstrates both RESTful API development and dynamic web page rendering. It features:

- A **To-Do List API** with full CRUD (Create, Read, Update, Delete) functionality using JSON.
- **Student Score Management** with form handling, score calculation, and result display using Jinja2 templates.
- Examples of handling different HTTP methods (`GET`, `POST`, `PUT`, `DELETE`) and dynamic URL routing.

## Features

- **To-Do List API:**  
  - Retrieve all to-do items  
  - Retrieve a specific item by ID  
  - Add a new item  
  - Update an existing item  
  - Delete an item

- **Student Score Management:**  
  - Submit student scores via web forms  
  - Calculate average scores  
  - Display pass/fail results dynamically

- **Jinja2 Templating:**  
  - Render HTML pages with dynamic data  
  - Use control structures and variables in templates

## Getting Started

1. **Clone the repository**  
   ```
   git clone <your-repo-url>
   cd <project-folder>
   ```

2. **Set up a virtual environment (optional but recommended)**  
   ```
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install dependencies**  
   ```
   pip install flask
   ```

4. **Run the application**  
   ```
   python app.py
   ```
   or for other modules:
   ```
   python jinja.py
   python api.py
   ```

5. **Access the app**  
   - Open your browser and go to `http://127.0.0.1:5000/`

## Project Structure

```
/flask
  |-- app.py
  |-- jinja.py
  |-- api.py
  |-- getpost.py
  |-- templates/
      |-- index.html
      |-- about.html
      |-- form.html
      |-- result1.html
      |-- results.html
      |-- getresults.html
  |-- static/
      |-- favicon.ico
  |-- sample.json
```

## API Endpoints

- `GET /items` — List all to-do items
- `GET /items/<id>` — Get a specific item
- `POST /items` — Add a new item (JSON body)
- `PUT /items/<id>` — Update an item (JSON body)
- `DELETE /items/<id>` — Delete an item

## License

This project is for educational purposes.

---

**Happy Coding!**
