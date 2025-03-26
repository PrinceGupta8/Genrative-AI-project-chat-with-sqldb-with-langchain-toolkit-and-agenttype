# Langchain: Chat with SQL Database

This project is a **Streamlit-based AI chatbot** that allows users to interact with **SQL databases** using **natural language**. It supports **both SQLite and MySQL** databases and utilizes **Groq's LLaMA3-8B-8192 model** for intelligent query generation and response handling.

## Features

- **SQL Database Chat**: Query SQLite or MySQL databases in natural language.
- **Multi-Database Support**: Choose between **SQLite** or **MySQL**.
- **AI-Powered Query Processing**: Uses Langchain and Groq LLaMA3 for intelligent responses.
- **Interactive UI**: Built with Streamlit for ease of use.
- **Session History Management**: Stores chat history for better user experience.

## Tech Stack

- **Python**
- **Streamlit**
- **LangChain**
- **SQLAlchemy**
- **SQLite / MySQL**
- **Groq (LLaMA3-8B-8192)**

## Installation

### Prerequisites

- Python 3.8+
- SQLite / MySQL database
- Groq API Key

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/PrinceGupta8/sql-chatbot.git
   cd sql-chatbot
   ```
2. **Create a virtual environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the application**
   ```bash
   streamlit run app.py
   ```

## Usage

1. **Enter your Groq API Key** in the environment variables or Streamlit input box.
2. **Select Database** (SQLite or MySQL) from the sidebar.
3. **Provide database credentials** (for MySQL users).
4. **Ask SQL-related questions** in the chat input box.
5. **Receive AI-generated SQL responses** based on your queries.

## Example

**User Input:**

```
Show me the list of students who scored above 80 in Mathematics.
```

**AI Response:**

```sql
SELECT * FROM students WHERE subject = 'Mathematics' AND score > 80;
```

## API Keys

- Get your **Groq API Key** from [Groq](https://groq.com/).
- Set this as an environment variable (`groq_api_key`) or input it in the Streamlit UI.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.

---

🚀 **Enhance your SQL interactions with AI-powered queries!**

