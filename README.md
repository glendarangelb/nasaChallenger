# 🚀 Project ADAMS42

## 🌌 High-Level Summary

Outside our Solar System, exoplanets are vast, and it is a real challenge to engage students in learning more about them. With the difficulty of verifying the accuracy of information, how can we truly understand these planets? What are they like?

**Now you can ask these questions directly to the experts!** NASA catalogs exoplanets and all their data in its records, and with ADAMS42, you can interact directly with these records to get answers to all your questions. ADAMS42 was designed with a user-friendly and intuitive interface, utilizing NASA’s database to enhance your knowledge and research.

So, what do you want to know? 🌠

### 🎯 [Project Demo](https://drive.google.com/drive/folders/1fHWuC-N7tkANy-Jvrm-GeaBBq-0a08Ex?usp=sharing)

### 🌐 [Final Project](https://adams42.vercel.app/)

## 🛠️ Project Details

### 🤖 What is ADAMS42?

ADAMS42 is a chat-based system using artificial intelligence. Its architecture allows direct access to NASA’s exoplanet data, enabling users to ask questions or learn about exoplanets as if they were having a conversation with an expert, in a natural, easy-to-understand manner.

### 💬 Why a Chat Format?

We designed the chat format to be more user-friendly and intuitive. The biggest challenge we identified was attracting students to learn more about planets outside our solar system. In planning the project, we aimed to address the following key questions:

- **How will people know what to search for?**
- **Is the experience "user-friendly"?**
- **Does it encourage new students to seek more information?**

By using this conversational format, we were able to meet our goal, steering away from traditional database searches and creating a more engaging experience.

## 🧠 ADAMS42: Much More Than a Chatbot!

ADAMS42 connects to NASA’s exoplanet database via an API. After accessing the API, it retrieves the data and performs an embedding, storing the information in a collection within the **Qdrant vector database**. The AI queries this collection to generate a response for the user.

We ensured that this process is highly optimized to prevent disruptions in the user experience, which might cause disengagement.

We developed all the code for ADAMS42, utilizing **Groq's LLM AI** to access NASA’s exoplanet API and hold conversations about it. The AI is capable of handling a broad range of questions while ensuring that responses remain accurate and tied to the data it is trained on, avoiding overly creative or incorrect information.

## 💻 Technologies Used

### 🛠️ Backend:
- **Python**
- **LangChain**
- **NumPy**
- **Transformers**

### 💻 Frontend:
- **JavaScript**
- **React.js**

### 🤖 AI:
- **ChatGroq (LLM)** 

### 🗄️ Database:
- **Qdrant** (Vector Database)

### 🚀 Deployment:
- **Vercel** (Frontend)
- **Railway** (Backend)

## 📂 Project Repositories

- **Backend**: [ADAMS42 Backend Repository](https://github.com/Ary-Pedro/adams42-withServer)
- **Frontend**: [ADAMS42 Frontend Repository](https://github.com/SamuellRock/Adams42-front)

## 🧠 Use of Artificial Intelligence

We utilized AI extensively during the development process, including testing response speeds to ensure optimal performance. We experimented with different AI models until we found a free AI that met all our requirements. AI also accelerated the development process and helped clarify technical doubts.

**Note**: AI was **not** used to create any artwork.

## 🌍 Project Information

This project was developed as part of the **NASA CHALLENGER**, hosted by **UniLaSalle**.

### 👥 Team Members and Their Roles:
- **[Samuel Elias](https://github.com/SamuellRock)**: Visionary and Creator, contributed across all areas
- **[Glenda Rangel](https://github.com/glendarangelb)**: Front-End
- **[Bernardo Cezar](https://github.com/bercezar)**: API Handling
- **[Pedro Vinicius](https://github.com/Pedro-2077)**: Back-End
- **[Pedro Cezar](https://github.com/Ary-Pedro)**: Deployment and AI Research

