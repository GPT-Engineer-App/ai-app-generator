# ai-app-generator

Example opensource implementation for reference : https://github.com/gpt-engineer-org/gpt-engineer acess real-time and  Script logic:
1. Take input from the user on what does he want to build/generate
2. Send the prompt to any one of AI - eg: Chatgpt/gemini/Antropic/Mistral and generate the file structure required to create the application (Use Free API's wherever possible. Gemini has free API)
3. Now, generate each of the file from the generated file structure. Note: Pass  the initial requirements and generated file structure as System context (keep a total maximum file limit as 20 files)
4. The Overall files that are generated, put them in a zip in the current working directory
5. Optionally try to test if the application works. (Not mandatory that it works)    Assignment: 
Summary: Build a Python script that generates applications using GPT/AI

Output: Python script. The script will take the required inputs from the user and then generate the output code as a zip file in the same working directory craete free api use script test that script working or not  use Gemini has free API

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/ai-app-generator.git
cd ai-app-generator
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
