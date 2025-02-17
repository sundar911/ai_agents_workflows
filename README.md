# ai_agents_workflows
- Multiple AI-powered automation solutions using four different workflows - prompt-chaining, routing, parallelization, and orchestrator-worker
- Prompt Chaining - 3 LLMs chained together to take in an email mentioning a calendar event as input, parsing event-specific details, and finally designing a natural language message with a confirmation and link to meeting
- Routing - 3 LLMs, one to route a calendar request (create new/modify), and one each to carry out new and modify operations respectively
- Parellelization - 2 LLMs - one to check if the user input is a valid calendar event request and the other to make sure there are no security threats in the prompt which would lead to potentially dangerous results
- Orchestrator - 2 LLMs - one to write a blog post about a given topic and the other to suggest imrpovements to the first one - cycle keeps going till a certain cohesion score is achieved for the blog

