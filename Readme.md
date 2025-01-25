# Personal Agentic AI Chatbot – GenAI Application 

This project is a production-ready **Personal Agentic AI Chatbot** that leverages cutting-edge technologies and models for intelligent responses. It integrates LangGraph ReAct agents with Groq and OpenAI LLMs to deliver robust and efficient interactions.

---

## **Project Layout**

### **Phase 1 – Create AI Agent**
1. **Setup API Keys** for Groq and Tavily.
2. **Configure LLMs & Tools** for conversational and search capabilities.
3. **Build AI Agent** with integrated search functionality.

### **Phase 2 – Setup Backend (FastAPI)**
1. Define **Pydantic Models** for schema validation.
2. Configure the **AI Agent** to process frontend requests.
3. Deploy and test via **Swagger UI Docs**.

### **Phase 3 – Setup Frontend**
1. Design the **User Interface** with Streamlit, including:
   - Model provider selection.
   - Model configuration.
   - System prompts and user queries.
2. Connect the **Frontend and Backend** via API URLs.

---

## **Technologies and Tools**

- **LangGraph ReAct Agents** – For conversational intelligence.
- **FastAPI** – Backend API development and calls.
- **Groq & OpenAI** – For language model functionalities.
- **Streamlit** – Lightweight, interactive frontend framework.
- **Langchain** – Tool orchestration and enhancements.
- **Uvicorn** – Application hosting.
- **Python** – Core programming language.
- **VS Code** – Development environment.

---

## **Technical Architecture**
This project follows a modular architecture:
- **LLMs** power intelligent and context-aware responses.
- **FastAPI** ensures seamless backend processing.
- **Streamlit** provides a user-friendly interface.
- **Groq and OpenAI** enhance AI capabilities with the latest in NLP technologies.

---

## **Installation and Setup**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/TusharKhandelwal95/ai_agent_chatbot_with_fast_api.git


## Setting Up a Python Virtual Environment

### Using Pipenv
1. **Install Pipenv (if not already installed):**  
```
pip install pipenv
```

2. **Install Dependencies with Pipenv:** 

```
pipenv install
```

3. **Activate the Virtual Environment:** 

```
pipenv shell
```

---

### Using `pip` and `venv`
#### Create a Virtual Environment:
```
python -m venv venv
```

#### Activate the Virtual Environment:
**macOS/Linux:**
```
source venv/bin/activate
```

**Windows:**
```
venv\Scripts\activate
```

#### Install Dependencies:
```
pip install -r requirements.txt
```

---

### Using Conda
#### Create a Conda Environment:
```
conda create --name myenv python=3.11
```

#### Activate the Conda Environment:
```
conda activate myenv
```

#### Install Dependencies:
```
pip install -r requirements.txt
```


# Project Phases and Python Commands

## Phase 1: Create AI Agent
```
python ai_agent.py
```

## Phase 2: Setup Backend with FastAPI
```
python backend.py
```

## Phase 3: Setup Frontend with Streamlit
```
streamlit run frontend.py
```

## IMPORTANT
### Make sure backend python script is running in a separate terminal



