# Audit Log Prompts and Responses: ChatGPT App

**Learning Objective:** Save Prompt and Responses on Phone for Audit Log purposes.

**Open AI model used**- gpt-3.5-turbo

**Steps involved**:
1. Obtain an OpenAI secret key from https://platform.openai.com/api-keys.
2. Refer https://platform.openai.com/docs/api-reference for the api endpoint you want to use, and do a similar  HTTP POST request from the app.
3. Display the response of the API on UI.
4. Save the promt and response to the database
5. View logs

**Testing:**

1. Set value for API secret in the MainActivity.java class
2. If possible, test the app on an android device. You might come across some errors while testing on emulator because of different environment settings.

# Screenshots:
Main Activity:

<img width="197" alt="image" src="https://github.com/RavirajWadnerkar/ChatGPT_Audit_Log_Prompts_and_Responses/assets/47893967/e5220bb4-6199-4be7-8d6c-7afbde6c0745">

Saving prompt and response:

<img width="237" alt="image" src="https://github.com/RavirajWadnerkar/ChatGPT_Audit_Log_Prompts_and_Responses/assets/47893967/15cee48c-b9d8-4f8f-8927-0397da06fd7c">

Displaying the logs:

<img width="237" alt="image" src="https://github.com/RavirajWadnerkar/ChatGPT_Audit_Log_Prompts_and_Responses/assets/47893967/3fd0aa6e-d5f0-42ae-9f9d-857d452bceb0">



