# ApexRetail-
Ecommerce product recommendation agent
This project aims to develop an ecommerce product recommendation system that returns a list of recommended products based on users preferences.

---

## File Explanation
The file structure is  :

```
    ├── backend/
    │   ├── app.py
    │   ├── bq-results-20240205-004748-1707094090486.csv
    │   ├── chatbot.py
    │   ├── dockerfile
    │   ├── requirements.txt
    ├── frontend/
    │   ├── app.py
    │   ├── dockerfile
    │   ├── requirements.txt
    ├── .gitignore
    └── README.md
```

- `backend/ app.py`: This file contains the backend code for the application.

- `backend/ bq-results-20240205-004748-1707094090486.csv`: This is the CSV file used as the dataset in this project. Dataset obtained from Google Cloud Platform - BigQuery  database : **thelook_ecommerce** table: **order_items, inventory_items, users**.

- `backend/ dockerfile`: Dockerfile is used to build a Docker image for backend application. It includes instructions on how to set up the environment and dependencies needed for backend.

- `backend/ chatbot.py`: This file contains the code used to create the Langchain framework and LLM , which is used to create the recommendation system.

- `backend/ requirements.txt`: This file lists the Python dependencies required for backend application. 

- `frontend/ app.py`: This file is the main script for the frontend of the application and is developed using the Streamlit framework. 

- `frontend/ Dockerfile`: Similar to the backend dockerfile, this file is used to build a Docker image for frontend application. It includes instructions on setting up the environment and installing dependencies.

- `frontend/ requirements.txt`: This file lists the Python dependencies required for frontend application.

- `README.md`: Markdown file that  contains documentation for the project. 

---

## Application

### How to use

In this application, there are two methods used as a product recommendation system: manually and chatbot. Users can choose one of the methods.

**Manual**

For this method, users can input their product preferences in the fields provided.


**ChatBot**

For this method, users can chat with an assistant who helps users find products according to their preferences.



