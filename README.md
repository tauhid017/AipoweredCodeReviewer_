AI-Powered Code Reviewer
This repository contains all the details required to set up and run an AI-powered code reviewer.

Project Description
The AI-powered code reviewer allows users to input a code snippet in any programming language, and it provides an intelligent review, including:

✅ Detection of the programming language used in the input code.
✅ Brief description of errors and issues in the code.
✅ Corrected version of the code with improvements.

This project is built using Flask for the backend and HTML, CSS, and JavaScript for the frontend, utilizing Google Gemini API for code analysis and suggestions.

Setup Instructions
Follow these steps to set up and run the project on your local system:
1. Clone the Repository
git clone https://github.com/tauhid017/AipoweredCodeReviewer_

2. Get a Google Gemini API Key
Sign up at Google AI and generate an API key from ai.google.dev

3. Create an Environment File
In the project directory, create a file named .env.local and store the API key:
GOOGLE_API_KEY=your_api_key_here

4. Install Dependencies
Create a requirements.txt file and add the following dependencies:
Flask
python-dotenv
google-generativeai
google-api-core

pip install -r requirements.txt

5. Run the Application
python app.py and you are god to go !

Technologies Used
Flask – Backend framework
HTML, CSS, JavaScript – Frontend
Google Gemini API – AI-powered code analysis

Contributing
Feel free to fork this repository and improve the project. Contributions are welcome!
Thank you
