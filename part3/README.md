## prompt chaining (for complex task)---> very large prompt

## note --> if give very large and complex prompt/task to a LLM model it wouldnot give best output thatswhy we subtask(break the large prompt into subtask and provide each subtask to LLM), the ouput of one subtask is further used in nest prompt is call prompchaing.

## why it need?(explain with example)

1. prompt--> extract skill -->LLM call1
2. prompt--> extract JD skills--> LLM call2
3. prompt--> match the skills and generate a score--> LLM call3
4. prompt--> if score>60 call HR else send rejection email-->LLM call4

## these steps are example of prompt chaining and it is used because:

1. Help in debugging --> (if we are getting any error , we will check each prompt step by step and discover the bug easily)

2. Modularity --> (if there is an error in step3 then we have to fix only step3 not the entire prompt)

3. Can use different model --> (if we have different variety of task respective of difficulty level, the we can use different LLM model for different task)

4. Retry step --> (we can use any particular prompt several times until  we get best result.)
