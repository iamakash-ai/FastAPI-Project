FastAPI Sample Project
This is a sample FastAPI project that demonstrates how to create a simple API using FastAPI.

Installation
Install Python:
  - If you haven’t already, download and install Python from the official Python website.
  - Create a Virtual Environment (Optional):
It’s recommended to create a virtual environment to isolate project dependencies.
Open your terminal or command prompt and navigate to your project directory:
cd path/to/your/project

Create a virtual environment (optional but recommended):
`python -m venv venv`

Activate the Virtual Environment:
Activate the virtual environment:
On Windows:
`venv\Scripts\activate`

On macOS and Linux:
source venv/bin/activate

Install FastAPI and Uvicorn:
Run the following command to install FastAPI and Uvicorn:
pip install fastapi uvicorn

Create a Requirements File
Generate a Requirements File:
To create a requirements.txt file, run the following command:
pip freeze > requirements.txt

This will list all installed Python modules along with their versions in the requirements.txt file.
Add Dependencies to requirements.txt:
Open the requirements.txt file and add the names of any additional modules you want to include.
For example:
fastapi==0.68.0
uvicorn==0.15.0

Running the FastAPI Project
Start the Development Server:
In your terminal, navigate to your project directory.
Run the following command to start the development server:
uvicorn main:app --reload

The --reload flag enables automatic code reloading during development.
Explore the API Documentation:
Visit http://127.0.0.1:8000 in your browser or use a tool like Swagger UI to explore the automatically generated API documentation.
