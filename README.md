# NLP Chatbot for Restaurant Operations

**GitHub Repository**: [NLP_Chatbot-Dialog_flow](https://github.com/2005-PriyanshuSaini/NLP_Chatbot-Dialog_flow)

## 🧠 Overview

This project presents an intelligent chatbot designed to assist in managing restaurant operations. By leveraging natural language processing, it streamlines customer interactions, handles inquiries about the menu and services, and facilitates order processing, enhancing overall efficiency.

## 🚀 Features

- **Natural Language Understanding**: Processes customer queries related to menu items, orders, and restaurant services using NLP techniques.
- **Order Management**: Tracks orders, provides real-time updates, and ensures efficient communication between staff and customers.
- **Database Integration**: Utilizes MySQL to store and retrieve menu items, order details, and customer information.
- **Frontend Interface**: Developed a user-friendly interface using JavaScript for seamless customer interactions.
- **Backend Framework**: Implemented using Python's FastAPI for handling API requests and managing chatbot logic.

## 🛠️ Technologies Used

- **Backend**: Python (FastAPI)
- **Database**: MySQL
- **Frontend**: JavaScript, HTML, CSS
- **NLP Libraries**: spaCy, NLTK (as applicable)

## 📂 Project Structure

NLP_Chatbot-Dialog_flow/
├── main.py
├── db_helper.py
├── generic_helper.py
├── frontend
├── startup.txt
├── requirements.txt
├── README.md

## 📝 Installation

Clone the Repository
Begin by cloning the repository and navigating into the project directory:

git clone https://github.com/2005-PriyanshuSaini/NLP_Chatbot-Dialog_flow.git
cd NLP_Chatbot-Dialog_flow

Create and Activate a Virtual Environment
Set up a virtual environment to manage project dependencies.

For Windows:
python -m venv env
env\Scripts\activate

For macOS/Linux:
python3 -m venv env
source env/bin/activate

Install Required Dependencies
Install the necessary Python packages using the requirements.txt file:

pip install -r requirements.txt

Open Terminal 1 and run the command:
uvicorn main:app --reload
This will start the FastAPI server at http://127.0.0.1:8000

Open Terminal 2 and authenticate ngrok with your token by running:
./ngrok config add-authtoken [your-token]

Still in Terminal 2, expose your local server by running:
ngrok http 8000
Copy the https link provided by ngrok (for example: https://your-subdomain.ngrok.io)

Go to your fulfillment or webhook settings and paste the ngrok https URL as the webhook URL.
Make sure to include the correct route if necessary (for example: https://your-subdomain.ngrok.io/webhook)

## 📸 Screenshots
![Landing Page](image.png)
![chat window](image-2.png)
![Ending page](image-1.png)

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.