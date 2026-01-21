# NLP-APP Using OOP


## 📝 Project Description

This project is a **menu-driven NLP (Natural Language Processing) application** developed using **Python and Object-Oriented Programming (OOP)** principles.

The application allows users to  **register, log in** , and then perform multiple **language-related AI tasks** such as **sentiment analysis, language translation, and language detection** using  **Google Gemini AI** .

The project is designed in a  **class-based architecture** , ensuring modularity, reusability, and scalability.

Sensitive information like API keys is securely managed using **environment variables** with `python-dotenv`.


## 🧠 Core Features of the Project

### 🔐 1. User Authentication System

* User **Registration**
* User **Login**
* In-memory database using Python dictionary
* Prevents duplicate email registration

---

### 🧩 2. Object-Oriented Design (OOP Based)

* **BaseModel class** handles AI model configuration
* **AppFeatures class** inherits from BaseModel
* Clear separation of responsibilities
* Promotes **code reusability and maintainability**

---

### 🤖 3. AI-Powered NLP Functionalities

After login, users can choose from the following NLP tasks:

#### ✅ a) Sentiment Analysis

* Analyzes user input text
* Determines whether the sentiment is **positive, negative, or neutral**
* Uses Gemini AI for accurate contextual understanding

Example:

<pre class="overflow-visible! px-0!" data-start="1880" data-end="1943"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre!"><span><span>Input</span><span>:</span><span></span><span>I</span><span></span><span>am</span><span></span><span>very</span><span></span><span>happy</span><span></span><span>today</span><span>
</span><span>Output</span><span>:</span><span></span><span>Positive</span><span></span><span>sentiment</span><span>
</span></span></code></div></div></pre>

---

#### 🌐 b) Language Translation

* Translates user-provided text into **Bangla (Bengali)**
* Uses AI-based contextual translation instead of word-by-word translation

---

#### 🔍 c) Language Detection

* Automatically detects the language of the given sentence
* Supports multilingual input

---

### 🔄 4. Interactive Menu-Driven Interface

* Easy-to-use command-line menus
* Smooth navigation between features
* Continuous usage without restarting the app

---

### 🔐 5. Secure API Key Management

* Uses `.env` file to store API keys
* Prevents hard-coding sensitive credentials
* Follows industry best practices


## ⚙️ Technologies Used

* **Python 3**
* **Object-Oriented Programming (OOP)**
* **Google Gemini AI (Generative Model)**
* **python-dotenv**
* **Environment Variables (.env)**


## 🧱 Project Architecture (High Level)

<pre class="overflow-visible! px-0!" data-start="2639" data-end="2814"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre!"><span><span>BaseModel
 └── Handles Gemini model </span><span>configuration</span><span>

AppFeatures
 ├── </span><span>User</span><span> Registration & </span><span>Login</span><span>
 ├── Sentiment Analysis
 ├── </span><span>Language</span><span> Translation
 └── </span><span>Language</span><span> Detection
</span></span></code></div></div></pre>


## 💻 Requirements

* **Python 3.10 or higher**
* **pip** or **conda**
* A valid **Google Gemini API key**


## ▶️ How to Run the Project


* Create a virtual environment:

  ```bash
  conda create -n geminiapp python=3.11 -y
  ```
* Activate virtual environment:

  ```bash
  conda activate geminiapp
  ```
* Install required packages:

  ```bash
  pip install -r requirements.txt
  ```
* Configure Environment Variables:

  Create a `.env` file in the project root directory (`NLP-APP`) and add your Gemini API key:

  ```bash
  GEMINI_API_KEY=your_api_key_here
  ```
* Run the Application:

  ```bash
  python app.py
  ```


## 🎯 Learning Outcomes

* Practical understanding of **OOP concepts** (inheritance, encapsulation)
* Hands-on experience with **AI-based NLP**
* Secure API handling using environment variables
* Building scalable, menu-driven Python applications
* Integrating **Generative AI models** into real projects


## 👨‍💻 Author

**Bijoy Dewanjee**


### 📜 License

This project is open-source and free to use for learning purposes.
