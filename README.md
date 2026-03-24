# 🤖 Gemini Chatbot (Streamlit + LangChain)

An interactive AI chatbot built using **Streamlit**, **LangChain**, and **Google Gemini API**. This app allows users to ask questions and receive real-time responses with customizable model settings.

---

## 📌 Overview

This project demonstrates how to integrate **Google Generative AI (Gemini)** with **LangChain** and deploy it as a simple web app using **Streamlit**.

Users can:
- Enter their Google API key
- Select Gemini models
- Adjust response creativity and length
- Ask questions and get AI-generated answers instantly

---

## 🚀 Features

- 💬 Interactive chatbot interface  
- 🤖 Google Gemini AI integration  
- ⚙️ Customizable parameters:
  - Model selection  
  - Temperature control  
  - Max token output  
- 🔐 Secure API key input  
- 📄 Prompt-based query handling  
- ⚡ Fast and lightweight UI  

---

## 🛠️ Tech Stack

- Python  
- Streamlit  
- LangChain  
- Google Generative AI (Gemini API)  
- python-dotenv  

---

## 📂 Project Structure

```
📁 gemini-chatbot
│── main.py
│── .env
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/gemini-chatbot.git
cd gemini-chatbot
```

---

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows**
```bash
venv\Scripts\activate
```

**Mac/Linux**
```bash
source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Setup Environment Variables

Create a `.env` file in the root directory and add:

```
LANGCHAIN_API_KEY=your_langchain_api_key
```

---

## ▶️ Run the Application

```bash
streamlit run main.py
```

---

## 💡 How It Works

1. Loads environment variables using `dotenv`
2. Defines a prompt template using LangChain
3. Initializes the Gemini model
4. Processes user input through a pipeline:

```
Prompt → Gemini Model → Output Parser
```

5. Displays the response using Streamlit UI

---

## 🧠 Available Models

- gemini-3-flash-preview  
- gemini-1.5-turbo  
- gemini-2  
- gemini-2-100b  

---

## 📸 Screenshot

_Add your app screenshot here_

---

## 🔧 Future Improvements

- Chat history support  
- Streaming responses  
- Voice-based interaction  
- Deployment on cloud  

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Vaibhav**

---

## ⭐ Support

If you found this helpful, give it a ⭐ on GitHub!
