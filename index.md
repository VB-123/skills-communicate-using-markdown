# Understanding Large Language Models (LLMs)
![LLMs](https://github.com/VB-123/skills-communicate-using-markdown/assets/127195382/38fb03b5-cad1-44c1-b171-ee9212c2cac7)
In recent years, LLMs have emerged as grounbreking advancements in the field of Artificial Intelligence. These are sophisticated neural networks trained on vast amounts of text data to understand and generate human like text. 
LLMs are charaterized by their unprecedented scale, with hundreds of billions of parameters, enabling them to grasp complex linguistic patterns and generate coherent texts, across diverse topics. Examples of prominent LLMs include OpenAI's GPT series, Google's BERT etc.
## Using LLMs
A pre- trained LLM, can be used to genrate text, in apps that we build. An example from python:
``` python
import openai
api_key = "API_KEY"
prompt = "Once upon a time"
response = openai.Completion.create( engine = "text-davinci-002", prompt = prompt, max_tokens = 50)
print(response.choices[0].text.strip()
```
