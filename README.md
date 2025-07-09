# 🦜 Langchain SQL Chatbot with Streamlit

An interactive chatbot built using **Langchain**, **Groq's LLaMA 3 model**, and **Streamlit** that allows you to chat with your **SQLite** or **MySQL** database in natural language.

## 📸 Demo

![demo](https://github.com/your-username/langchain-sql-chatbot-streamlit/assets/demo.gif)  
*(Replace this with your actual demo GIF or screenshot)*

---

## 🚀 Features

- 🧠 Chat with your database using LLM (LLaMA 3 from Groq)
- 🗄️ Supports SQLite (`student.db`) or any MySQL database
- 💬 Live chat UI with memory history
- 🔐 Secure credential handling via sidebar inputs
- ✅ Streamlit-powered interactive frontend

---

## 🧰 Tech Stack

- [Langchain](https://www.langchain.com/)
- [Groq](https://console.groq.com/) (for LLaMA 3 API)
- [Streamlit](https://streamlit.io/)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- SQLite / MySQL

---

## 📦 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/langchain-sql-chatbot-streamlit.git
cd langchain-sql-chatbot-streamlit
````

### 2. Create and Activate Environment (optional)

```bash
conda create -n sqlchatbot python=3.10 -y
conda activate sqlchatbot
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

#### Additional (for MySQL support):

```bash
pip install mysql-connector-python
```

---

## 🛠️ Usage

### 1. Place your SQLite database (`student.db`) in the project root.

### 2. Run the Streamlit App

```bash
streamlit run app.py
```

### 3. In the sidebar:

* Choose SQLite or MySQL
* If MySQL:

  * Enter host, user, password, and database name
* Enter your [Groq API key](https://console.groq.com/keys)

### 4. Chat with your data!

---

## 📁 File Structure

```
langchain-sql-chatbot-streamlit/
│
├── app.py                # Main Streamlit application
├── student.db            # Sample SQLite database (if available)
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## 📄 Example Requirements

```txt
streamlit
sqlalchemy
langchain
langchain-community
langchain-groq
mysql-connector-python
```

---

## 🔐 Groq API Key

Sign up and get your API key from [https://console.groq.com/](https://console.groq.com/)

---

## 🤝 Contributing

PRs are welcome! If you find a bug or want to add features, open an issue or submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙏 Credits

Built using:

* [Langchain](https://www.langchain.com/)
* [Groq](https://www.groq.com/)
* [Streamlit](https://streamlit.io/)

```

