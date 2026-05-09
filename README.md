# RoadmapOpenAIProject
This is the Project url("https://roadmap.sh/projects/openai-api-python") which required to call OpenAI API directly through the backend instead to writing the message to OpenAI chat interface on Web.

Now before seeing this repo you should understand that the openai api is not free. So if you want, you can only use openai Library which was the requirement of the project but use a different api key like gemini api key which for some reason is free to some extend for newly created once "All hail GEMINI".

I am showing you to use both so follow the instructions:

1. Go to "https://aistudio.google.com" to create Gemini API or go to https://platform.openai.com/ to create a OpenAI API key.
2. create a python or jupyter notebook or use colab(most prefered option if you want to key the file on cloud and run without setting up the environments and want a easy API KEYS secreats Access).
3. download the libraries and import them(don't know which once then you have not open my notebook yet it was in the first cell of the notebook)
4. run the cells one by one the code should work.

if you want, you can also use gradio and create a similar chat interface as the one we use for AI chats.


# Results
By comparing both the responses from a same model with low(0.2) and high(0.8) temprature we can conclude that 
## With low temprature 
Models Thinking becomes Very deterministic, predictable, and repetitive.
Due to which it tends to pick most likly token nest and give factual answers.
## With high Temprature
Models Thinking becomes random, More diverse and creative.
Due to which it tends to explore low probablity tokens and give a imaginative or unexpected output 
