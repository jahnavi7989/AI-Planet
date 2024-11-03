Market-Research-Agent
Description
Market-Research-Agent is a powerful application designed to provide users with comprehensive financial and market analyses of companies using publicly accessible internet data. Utilizing multiple AI agents, each with specialized expertise in various aspects of financial and market research, this tool gathers, analyzes, and compiles relevant data into an informative report. The output enables users to make well-informed decisions based on factual, detailed insights.

Key technologies utilized in this project include CrewAI, Langchain, Streamlit, Python, and Google Gemini Flash 1.5 LLM.

Demo
To see Market-Research-Agent in action, watch the demonstration video: Market_research.mp4.

Installation
To set up this project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/psrane8/Market-Research-Agent.git
Navigate to the project directory:

bash
Copy code
cd Market-Research-Agent
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Ensure all dependencies are installed as directed above.

Run the Streamlit app:

bash
Copy code
streamlit run app.py
Open your browser 
Create a .env file in the project directory with the following environment variables:

makefile
Copy code
GOOGLE_API_KEY=your_google_api_key
SERPER_API_KEY=your_serper_api_key
Type the name of a company in the app to generate an analytical report.

Credits
This project leverages the following technologies and APIs:

CrewAI
Langchain
Google Gemini Flash 1.5
Streamlit
SerperAPI
Python

