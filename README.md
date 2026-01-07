Career Mentor AI

Career Mentor AI is an AI-powered resume analysis and career guidance tool. It parses resumes, extracts key information (skills, experience, education), and provides personalized career recommendations and improvement suggestions.

🚀 Features

📄 Resume parsing from PDF

🧠 AI-based skill extraction

🎯 Career role recommendations

📝 Resume improvement suggestions

🔧 Easy-to-extend Python architecture

🛠️ Tech Stack

Language: Python

Libraries: spaCy / NLTK / PyPDF2 (as listed in requirements.txt)

AI/NLP: Rule-based + LLM-ready design

Database (optional): MongoDB (future scope)

📂 Project Structure
career-mentor-ai/
│── main.py              # Application entry point
│── resume_parser.py     # Resume parsing and NLP logic
│── config.py            # Configuration settings
│── requirements.txt     # Python dependencies
│── resume.pdf           # Sample resume
│── resume2.pdf          # Sample resume
│── README.md            # Project documentation
⚙️ Installation

Clone the repository

git clone https://github.com/karthi206/career-mentor-ai.git
cd career-mentor-ai

Create a virtual environment (recommended)

python -m venv venv
source venv/bin/activate  # On Windows: venv\\Scripts\\activate

Install dependencies

pip install -r requirements.txt
▶️ Usage

Run the main application:

python main.py

Make sure the resume PDF path is correctly set inside main.py or config.py.

📌 Example Output

Extracted skills: Python, Machine Learning, SQL

Suggested roles: Data Scientist, ML Engineer

Resume feedback: Add more quantified achievements

🧩 Future Improvements

🌐 Web interface (Streamlit / Flask)

🤖 Integration with OpenAI / Gemini

🗂️ Job matching with real-time job APIs

📊 Resume scoring system

👥 User profiles & history
