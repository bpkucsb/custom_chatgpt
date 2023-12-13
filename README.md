# custom_chatgpt_for_condo_rules
I train a chatbot to understand my building's rules so residents can quickly find out what they need to do to be in complience in various situations such as getting remodeling projects approved, using guest parking or moving furniture

This project is based on a tutorial by Baris Sen in https://textcortex.com/post/train-chatgpt-on-custom-data

Below are the package version I installed in my conda environment

```
gpt-index==0.4.24
gradio==3.24.1
langchain==0.0.118
openai==0.28.1
pypdf2==3.0.1
```

My first question for the custom chatbot concerns how you get a remodeling project approved in our building. The chatbot lists the necessary steps

<img width="1252" alt="Screen Shot 2023-12-12 at 6 17 51 PM" src="https://github.com/bpkucsb/custom_chatgpt/assets/13769127/4e5360f0-13b8-4f69-9e30-2525e6dbab11">

My second question asks how residents can secure parking if they have guests over. The chatbot correctly refers us to guest parking passes used in our building

<img width="1258" alt="Screen Shot 2023-12-12 at 6 20 58 PM" src="https://github.com/bpkucsb/custom_chatgpt/assets/13769127/27646c9a-88d3-4698-a245-ab1cd92b9aa4">


My third question asks the chatbot what I should do if I'm expecting a couch to be delivered. The chatbot again correctly lists the rules governing large furniture deliveries.

<img width="1373" alt="Screen Shot 2023-12-12 at 6 15 33 PM" src="https://github.com/bpkucsb/custom_chatgpt/assets/13769127/5f069433-5095-423d-863e-ea95e89ac89f">
