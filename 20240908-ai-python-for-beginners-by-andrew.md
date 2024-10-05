# Course: AI python for beginners by Andrew

Course: [AI python for beginners: basic of AI python coding](https://learn.deeplearning.ai/courses/ai-python-for-beginners/lesson/8/combining-text-and-calculations)

A course to produce some code using an AI bot instead of yourself. 

- A way to use LLM prompts with variables
  
  Example:
  ```python
  from helper_functions import print_llm_response
  print_llm_response("What is the capital of France?")
  ```

- Use functions in AI programs
  
  Example: 
  ```python
  name = "Tommy"
  potatoes = 4.75
  prompt = f"""Write a couplet about my friend {name} who has about {round(potatoes)}potatoes"""}
  # Calls a function named `get_llm_response` with prompt as its argument. 
  # This function is supposed to generate a response based on the `prompt`.
  # The response is then assigned to the variable `response`.
  response = get_llm_response(prompt)
  print(response)
  ```




