## Streaming-->when asking anything in chatbot or give a prompt like (Explain machine learning.) , then it doesnot give entire answer directly instead it give line by line 


## There in function named streaming= true/false

1. stream = False --> give entire answer at a time

2. stream = True --> give line by line answer or in chunk.

## why need of this?
--> it take more time to give the entire output(slow service) unlike streaming which gives anwers in chunk that make llm user friendly by not to waiting.

NOTE--> (bydefault stream=False). we are not suppose to use stream everytime but when end user is human then we will use streaming but when there is code user(Json out used in another code) then we donot use streaming.{if we use streaming in json , it may break.