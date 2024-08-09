# Full-Stack AI Chatbot with OpenAI API
## Overview
Have you ever wondered how you could **receive more reliable, comprehensive information conversationally** when you need information about specific topics? For example, when you need to know about the application process of foreign universities, you might need to conduct detailed, time-consuming research on your own from zero. Wouldn't it be nice if you had a chatbot where you could ask questions and receive entry points for your more specific research? 

This project provides a solution to this problem by creating an **AI chatbot with OpenAI GPT and the MERN stack website**. In addition to the chatbot feature, this application stores user information and chat history in the database (MongoDB) and conducts in-depth user authentication with JWT tokens and HTTP-only cookies. 

Developers can utilize this project to provide a further customized chatbot by fine-tuning the OpenAI GPT. In the future, I plan to fine-tune this GPT model in the application process and the student lives at foreign universities. 

## The Technologies Used:
* NodeJS: backend
* MongoDB: database for user information and chat history 
* Vite and ReactJS: frontend 
* JWT and HTTP-only cookies: user authentication
* Material-UI: UI features 

## How to Install This Project 
First of all, you need to clone this project through this GitHub repository. 
```
git@github.com:reikawa13/FullStack-Customized-AI-Chatbot.git
```
Secondly, you need to set up the .env file of the project. To get the OpenAI keys, you need to create your own project on the OpenAI website and add your billing information. To set up the MongoDB URL, you also need to set up a project on MongoDB's website. You can create your own JWT_SECRET and COOKIE_SECRET, as well as the port number. 
```
OPEN_AI_SECRET=YOUR_SECRET_KEY
OPENAI_ORGANIZATION_ID=YOUR_SECRET_KEY
MONGODB_URL=YOUR_SECRET_KEY
JWT_SECRET=YOUR_SECRET_KEY
COOKIE_SECRET=YOUR_SECRET_KEY
PORT=YOUR_SECRET_PORT
```
Lastly, you need to run the following command in both the /frontend and /backend directories. 
```
npm run dev
```

