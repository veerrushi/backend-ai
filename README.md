# Java Spring AI Chatbot

A simple AI-powered chatbot built using **Spring Boot** and **Spring AI**, integrated with **OpenAI's Chat Model**.

## Features
- Chat with an AI model using OpenAI API
- Uses **Spring Boot** for backend services
- Implements **Spring AI** for seamless AI model interaction
- Open-source and easy to deploy

## Prerequisites
Ensure you have the following installed:
- **Java 17+**
- **Maven**
- **Spring Boot**
- **OpenAI API Key** (stored securely as an environment variable)

## Getting Started

### 1. Clone the Repository
```sh
https://github.com/veerrushi/backend-ai.git
cd backend-ai
```

### 2. Set Up Environment Variables
Create an `.env` file or set the variable in your system:
```sh
export OPENAI_API_KEY=your_api_key_here
```

### 3. Run the Application
Using **Maven**:
```sh
mvn spring-boot:run
```

### 4. Test the API
Use **Postman** or **cURL** to test:
```sh
curl --location 'http://localhost:8080/api/v1/chat?inputText=what%20is%20java%3F'
```

## Project Structure
```
/src/main/java/com/example/ai_chatbot
    ├── controller
    │   ├── ChatController.java
    ├── service
    │   ├── ChatService.java
    ├── Application.java
```

## API Endpoints
| Method | Endpoint       | Description       |
|--------|--------------|-----------------|
| GET   | `/api/v1/chat`  | Sends a message to OpenAI and receives a response |

## Contributing
Feel free to fork this repo and submit pull requests.
---
### 🚀 Happy Coding!
