# Notes on my learning of AI Agents on N8N
* AI Agents are nothing more than pairing a trigger/request to AI and that will then trigger something else. 
* From Nick Saraev's video:
* Tutorial from [N8N Themselves](https://www.youtube.com/watch?v=yzvLfHb0nqE)
	* Use the chat trigger, send messages to a UI
	* AI Memory: The ai agent is able to understand the context 
	* User messages and system messages
* What an AI agent is
	* LLM generates text based on input text. 
	* Gueses what is the next word based on the input
	* LLM: Adds goal - oriented functionality - it is the task completion part. it also has the ability to use tools 
	* Agent: Takes the input text, feeds it into an LLM, makes multiple thoughts, can ingest the output of a tool, ingest it back in an llm and decide what the next step is - and finally outputs that. 
* Not everything needs an AI Agent. 
* We can combine deterministic steps with the power of LLMs. 
* Create a new workflow.
* Add a first step

**Notes**
* Not everything needs an AI Agent
* Some AI Features, e.g. sentiment analysis... could be done without an AI agent
* How AI Agents work
	* They have dependencies they need to work
	* The chat modelv is always required. It is the LLM, used under the hood = it processes semantic text. 
* There are several types of AI agents: tools agent is the one we will use regularly and the most common 
* Text from the previous node: It is basically the task that we give the AI agent to complete.
* A way to control the output of the AI assistant is through the system message. 
* There are some best practices for system messages. 
* The user message: Actual task, the thing you want the ai agent to perform. The system message dfefines the context, behavior and rules regarding how the task should be completed. 
* Barebone of system messages
	* Should define the role of the assistant. 
	* Then the style, e.g. tone: Be concise and avoid jargon, what words, what lengths of the text... 
	* Adding boundaries to the tasks. A good example of boundaries: do not hallucinate, or don't make assumptions. Clarify your questions. 
	* System messages: Giving context - example the time we are right now. 
* You can add system messages through the expression field, which combines normal text with javascript. 
* Example: Today is $now. 
* E.g. output in german. 


Examples you can use already today. 
#role
You are a helpdesk assistant for a software company, guiding users with
troubleshooting and feature explanations.
#behavior
Be professional yet approachable. Do not guess answers; ask clarifying
questions when needed.
#capabilities and restrictions
You can troubleshoot common errors, explain software features, and
suggest documentation links. You cannot access private user data, or
provide legal or financial advice.
#output
Provide direct answers with clear steps if applicable. Use bullet points for
multi-step instructions. Include links to documentation where relevant.


**Memory**
* Job of the AI is to determine the next text to output depending on the input. 
* It does not remember the previous input. 
* Chat GPT uses a memory under the hood. 
* When it sends messages to the model it sends a stack of messages. 
* We need to use a memory tool.
* Session memory: Creates an array of messages or stack of messages based on previous messages. 
* Chat-based use-case: we can bring the number up. 
* The order through which the AI called the dependencies. 

* Chat trigger node: it has complicated settings, we should check them out in the documentation. 
* Executions tab - if the workflow was run in the editor it will be indicated, if not it was in the production. 
* You can copy the data to the editor and see the state, the runs...


**AI Agent Part 2**
[Gmail draft writing assistant](https://www.youtube.com/watch?v=lkudvrC3AOU)

* Each time you receive an email, you want to digest the content of that email and direct it to the pipeline of the AI Agent, generate a draft and post that draft.
* We can create test events and fetch them 
* The define below cvan be used to dselect the schema we want to import
* Action being asked to the chat model: Write a reply to the following email, then add it as a draft to the email thread. 
* If we want to add variables and code we need to turn it into an expression. 
* From: Subject, Message, From
* We can wrap it into some tags like email  and /email
* We can use directly a model. 

![[Pasted image 20250215171528.png]]



- I get that all the content will be addressed in the model itself. 
* Tool description: Telling the AI that you can use this tool to create drafts in gmail. 
* We can then decide which tools get to be modified by the AI or not, we are able to put guardrails to the AI to make it predictable. 

* We can use the expression and adding the from AI method, and add into parentheses what you want your model to do (see below) - we are basically defining the key - name of the AI variable we want the AI to inject - we can also give it a description, we can also decide on the data type - e.g. 'string, boolean' - and we can also give it a default value. 

![[Pasted image 20250215175622.png]]


We can populate the fields depending on the input. 

If we prepopulate we are basically saying the AI they cannot control it. 

We need to be careful about 

We should definitelly as much as possible add a system prompt which would help to configure the style, the copy... etc. 

Provide examples to the LLM

Use other tools, e.g. HTTP Requests. 