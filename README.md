# Machine Learning Front End

## Overview
This project involved building two separate Flask applications:
1. **API Server** - A Flask-based service hosted on Azure that processes JSON inputs, runs a machine learning model, and returns salary predictions based off user inputs.
2. **Front-End Application** - A separate Flask web app featuring a form where users can submit input values and see the returned estimated salary.

## Accomplishments

### ✅ Created a Flask-Based Front-End Application
- Developed a Flask app using a `templates` folder.
- Built `base.html` and `index.html` for a structured layout.
- Designed a web form with dropdowns, ensuring **all fields are required**.
- Implemented an empty option in dropdowns prompting users to make selections.
- Configured the form to **POST data** to the `/predict` route.

### ✅ Integrated with ML API on Azure
- Set up an API server on Azure to process inputs.
- Updated `app.py` to reference the correct `api_url`.
- Verified responses by testing the API with **Postman**.

### ✅ Thorough Testing of Front-End Application
- Checked that required fields return **proper validation errors**.
- Ensured input values align with the API’s expected format.
- Confirmed that submitted selections return **a predicted salary**.
- Cross-checked predictions with API results from Postman.

### ✅ Styled the Web Application Using Bootstrap 5.3
- Enhanced design using Bootstrap 5.3.
- Ensured **responsive formatting** by testing browser resizing.
- Correctly placed Bootstrap elements across `base.html` and `index.html`.

### ✅ Successfully Deployed Front-End to Azure
- Hosted the front-end Flask application on Azure.
- Conducted final validation to confirm the page loads correctly.
- Verified that form submissions return predictions without errors.

---

