# Description

Deploy DeepSeek R1 using Azure AI Foundry and Build a Web Chatbot

# Steps

Go to AI Foundry and create an AI hub:

![Alt text](assets/1.png)

The rest of parameters as default

Once deployed, launch the AI Foundry and create a new project:

![Alt text](assets/2.png)

Go to models and endpoints and click Deploy base model and click the Deepseek-R1 model:

![Alt text](assets/3.png)

Open the chat playground:

![Alt text](assets/4.png)

![Alt text](assets/5.png)

Now let's build a local web app. For that we use the code

We create a chat.py script and add the Azure endpoint and key from Models + endpoint section

![Alt text](assets/6.png)

# Results

We create an app.py script as well and execute them in the terminal. Click on the url that appears and the Web app is there!

![Alt text](assets/7.png)

![Alt text](assets/8.png)

Let's ask some questions to the model:

![Alt text](assets/9.png)

And it works pretty well!!
