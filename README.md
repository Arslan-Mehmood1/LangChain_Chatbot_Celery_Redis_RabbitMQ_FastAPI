# LangChain_Chatbot_Celery_Redis_RabbitMQ_FastAPI

This project is a an implementation of a LangChain chatbot, designed to handle both asynchronous and synchronous processing using Celery, Redis, and RabbitMQ. The chatbot is integrated with FastAPI to provide a robust and efficient API for real-time communication. User session chat history is intelligently managed using Redis, ensuring a seamless and personalized user experience.

**Key Features:**
- **LangChain Integration:** Utilizes LangChain Agents for building chatbot.
- **Celery for Asynchronous Tasks:** Implements Celery for handling background tasks and long-running processes efficiently.
- **Redis for Session Management:** Leverages Redis to manage user session data and chat history, enhancing performance and scalability.
- **Redis for Message Queuing:** Can leverage the Redis to manage message queues to communicate with Celery workers..
- **RabbitMQ for Message Queuing:** Can leverage RabbitMQ to manage message queues to communicate with Celery workers.
- **FastAPI for Web API:** Provides a FastAPI-based web API for real-time interaction with the chatbot.

**Technologies Used:**
- Python
- LangChain
- Celery
- Redis
- RabbitMQ
- FastAPI

**Getting Started:**
To get started with this project, clone the repository and follow the instructions in the README.md file.
