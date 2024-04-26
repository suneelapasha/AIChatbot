# AIChatbot

AI-powered chatbot with Node.js 

# Quickstart Packages:

- **dotenv**: zero-dependency module that loads environment variables from a .env file into process.env.
- **nodemon**: utility that will monitor for any changes in your source and automatically restart your server.
- **readline-sync**:for interactively running to have a conversation with the user via a console
- **openai**: OpenAI API library for Node.js projects. This library provides convenient access to the OpenAI API from applications written in server-side JavaScript.

## Installation :

`npm install dotenv nodemon openai readline-sync`

## [get an API key](https://platform.openai.com/account/api-keys)

.env file

OPENAI_API_KEY=...


## [Postman](https://www.postman.com/downloads/)
Postman is an API platform for building and using APIs. 

- use [web version](https://web.postman.co/home)

## [get an key](https://platform.openai.com/account/api-keys)

.env file

POSTMAN_API_KEY=...

## Installation :
`npm install`

## Start:

`npm start`

## Send API REQUEST:
```
curl -X POST http://localhost:4000/sendMessage \
  -H 'Content-Type: application/json' \
  -d '{
    "input": "what are the opening hours ?",
  }'
```