# Gen-AI-app-using-Vertex-AI
Creating serverless Gen AI app using vertex AI for Insurance Company.

## We are developing Gen AI app and doing below following tasks:
1. Create application from Prompts
2. Design effective prompts
3. Engineer and manage prompts
4. Generate Image in Vertex AI Studio

## What we would learn in this section:
1. Designed a prompt in Vertex AI Studio.
2. Deployed it as a serverless application using Cloud Run with a few clicks.
3. Directly opened and interacted with your generative AI model through a web interface.
4. Working on different Types of Prompts (Direct prompts / multi shot prompts / Chain of thoughts prompts(CoT)).
5. Comparing the results of same prompt from different system settings and temperature.
6. Generate Media in vertex AI studio.



### Create application from Prompts
In this we are creating Vertex AI Gen AI App using serverless Cloud Run. I have used gemini 2.5 flash model. This is basic model where we are saving the system instructions seperately, to give a AI assistant with relevant role. for example :

*"You are an expert AI assistant for an insurance underwriting department.
Your primary goal is to help underwriters by accurately and concisely summarizing client information and highlighting potential risk factors.
Maintain a professional and objective tone.
Focus only on the information provided in the prompt. Do not invent details. "*

by saving this prompt and deploy the app in cloud run using python code. This will deploy the app to get the ** Insurance Risk Summary - Prototype **

<img width="1270" height="748" alt="image" src="https://github.com/user-attachments/assets/3a3db58e-d0fc-40ea-b009-be992853f8a2" />

In the chatbot section if we ask the Question about any insurance risk factor questions - It should process your input based on the logic and system instructions you defined in Vertex AI Studio.





