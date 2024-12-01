# Flask Healthcare Application - A Survey Tool for Income and Expenses Analysis

## Project Description
This project is a survey tool developed using Flask to collect user data on income and expenses. The data is stored in MongoDB, processed using Python, and visualized in a Jupyter notebook. The application is deployed on AWS.

## Setup Instructions

### Prerequisites
- Python 3.x
- Flask
- Pymongo
- MongoDB
- AWS Account

### Installation

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
7.	Install Dependencies:
8.	Run MongoDB: Ensure MongoDB is running on your machine.
9.	Start the Flask Application:
10.	Access the Application: Open your browser and navigate to http://localhost:5000.
Data Processing
11.	Run Data Processing Script:
12.	Load Data in Jupyter Notebook: Open data_visualization.ipynb in Jupyter Notebook and run the cells to generate visualizations.
Deployment on AWS
13.	Launch an EC2 Instance: Follow the AWS documentation to launch an EC2 instance.
14.	Install Required Software: SSH into your instance and install Python, Flask, and MongoDB.
15.	Deploy the Application: Clone the repository on your EC2 instance and start the Flask application using Gunicorn.
Visualizations
The following visualizations are generated:
●	Ages with the highest income.
●	Gender distribution across spending categories.
