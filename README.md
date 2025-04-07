# sprint_7_project
Tripleten Sprint 7th project: The objective is to build an interactive app which shows graphics from a db of vehicles announcements.

# Interactive Data Visualization with Streamlit

This project is part of my effort to strengthen my skills in software engineering, particularly in areas that intersect with data analysis and web development. I built a web application using **Streamlit** to create interactive visualizations and deployed it to the cloud using **Render**.

## My Objective

My goal with this project is to gain practical experience in managing the full cycle of a data-driven application — from setup to deployment — while reinforcing essential technical skills. This includes:

- Creating and managing virtual environments in Python  
- Performing exploratory data analysis (EDA) using Jupyter and Plotly Express  
- Developing an interactive web application with Streamlit  
- Deploying the app publicly using Render  

Although I used a dataset of used car listings in the U.S. (`vehicles_us.csv`), the core focus of this project is not data analysis itself, but rather the **end-to-end development and deployment of a functional data app**. The app could work with any CSV dataset, making it adaptable to different use cases.

## 🛠️ Technologies Used

- [Python]
- [Streamlit]
- [Plotly Express]
- [Pandas]
- [Jupyter Notebook]
- [Render]  
- [GitHub]

## ⚙️ Project Structure

```bash
├── app.py                  # Main Streamlit application
├── requirements.txt        # Python dependencies
├── vehicles_us.csv         # Dataset used in the app
├── notebooks/
│   └── EDA.ipynb           # Exploratory data analysis notebook
├── streamlit/
│   └── config.toml         # Streamlit settings for Render deployment
├── .gitignore
├── README.md

You can explore the deployed version of the app here:  
🔗 [https://sprint-7-project-lm12.onrender.com/](https://sprint-7-project-lm12.onrender.com/)

Clone the repository:

bash
git clone https://github.com/anaidmg/sprint_7_project.git
cd sprint_7_project
Create and activate a virtual environment:

bash
python -m venv vehicles_env
# Activate it
# On Windows:
.\vehicles_env\Scripts\activate
# On macOS/Linux:
source vehicles_env/bin/activate
Install the dependencies:

bash
pip install -r requirements.txt
Run the app:

bash
streamlit run app.py
