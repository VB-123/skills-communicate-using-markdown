# Python integrated with Open AI!
## Use chatGPT directly from your favourite code editor!
### Getting started...

## Task 2: Adding Images
![Image for getting started](https://octodex.github.com/images/filmtocats.png)

## Task 3: Adding Code samples
``` python
 # python scripts
import openai 
openai.api_key = 'YOUR_API_KEY'
messages = [ {"role": "system", "content": 
			"You are a intelligent assistant."} ] 
while True: 
	message = input("Enter the query : ") 
	if message: 
		messages.append( 
			{"role": "user", "content": message}, 
		) 
		chat = openai.ChatCompletion.create( 
			model="gpt-3.5-turbo", messages=messages 
		) 
	reply = chat.choices[0].message.content 
	print(f"ChatGPT: {reply}") 
	messages.append({"role": "assistant", "content": reply}) 
```

## Task 4: Making lists
How to use chatGPT with python?
- [ ] Head to chatGPT's website and get an API key
- [ ] Using the pip command install the `openai` package for python.
- [ ] Use the `import openai` statement to start using chatGPT in your code editor, as in the example above.
