# Generative AI for Everyone (Coursera)

## Welcome

- Adding **2.6 \- 4.4 trillion** annually *(McKinsey)*.  
- Raise **global GDP by 7%** in many **sectors** *(Goldman Sachs)*.  
- Impact: **10% of tasks** could be caused by policy inertia *(OpenAI)*.

  ## What is Generative AI?

- **Generative AI** can produce content (**text, audio**).  
- It is also a **developer tool**.

  ### DeepLearning.AI

- Generative AI makes **briefing systems accessible**.  
- **We are still** seeing the **blossoming** of AI applications.

  ## Types of Generation

- **Text**  
- **Audio**  
- **Video**

  ---

  # How Generative AI Works

- **AI**: A set of tools.

  ### Learning Types *(Illustrated in the diagram)*

- **AI**  
  - **Supervised Learning**  
  - **Unsupervised Learning**  
    - **Self-improvement learning** *(possibly reinforcement learning?)*.


  # Supervised Learning

- **Input (A) → Output (B)**  
  - *Example: spam filters*

  ### Applications:

- **Online advertising**  
- **Self-driving cars**  
- **Healthcare**  
- **Defect detection**  
- **Speech recognition** *(transcripts)*  
- **Restaurant reviews**

  ---

  ## AI Model Growth (2010-2020)

- **Small AI models**: Limited data usage.  
- **Large AI models**: More data, improved performance.

  ---

  ## Large Language Models (LLMs)

- **Generates text** based on input.  
- Example:  
  - **Input**: "I love acting"  
  - → **Supervised learning** is applied.  
- **LLMs predict the next word**.

  ### Scale:

- **Trillions of words** → **ChatGPT**.

  ---

  ## LLM as a Thought Partner

- **Finds information** but can produce **hallucinations** ⚠️.  
- **Back-and-forth interaction** improves context.  
- **Rewriting for clarity** is essential ⚠️.

  # Web Teaches Us LLMs

- **What happens when you have no resource of that on the internet?**  
- **Generative AI as a general-purpose technology.**  
  - **Versatile** → Used for many things.

  ---

  ## Framework of Tasks

- **Text-based tasks**:  
    
  - **Brainstorming**  
  - **Writing**  
  - **Reading**  
  - **Chatting**


- **Web-based applications**:  
    
  - **Web-based interface** → *ChatGPT, Bard, Bing, etc.*  
  - **API-based applications** → *Software-integrated AI*

  ---

  ## Writing

- **Use it as a creative partner**:  
  - **Generating names**  
  - **Developing ideas to increase skills**  
- **Provide CONTEXT \+ BACKGROUND INFO** *(for better responses).*

  ---

  ## Translation

- **Performs well**.

  ---

  ## Reading

- **Proofreading**  
- **Summarizing long articles**  
- **Summarizing text following a word limit (e.g., 300 words or fewer)**


  # Summarizing Call Center Concerns

- **Generate summaries of conversations**.  
- **Review summaries** → *Spot trends*.  
- **Use summaries in software applications**.

  ---

  ## Customer Emails

- **Email routing** → *Will need context*.  
- **Provide the list of existing departments**, *for instance*.  
- **Track customer sentiment over time**.  
- **Dashboard to track sentiments over time**.

  ---

  ## Chatting Tasks

- **Customer service chatbots** → *Good at pre-agency tasks*.  
- **Career coaching**.  
- **Recipe ideas**.

  ---

  ## IT Service Chatbot

  ### Interaction Flow:

- **Human support**  
    
- **Bot triages for humans**.  
    
- **Chatbots only** *(fully automated response)*.  
    
- **Humans remain in the loop** for **critical support cases**.  
    
- **Saves time** by reducing manual workload.


  # Advice for Deploying Chatbots

1) **Start with internal-facing chatbots**.  
2) **Deploy with human-in-the-loop**.  
3) **Allow the bot to communicate directly** *(once reliability is confirmed)*.

   ---

   # What LLMs Can vs. Cannot Do

- **When prompting an LLM, think of it as a fresh college graduate**.  
  - **Assumes**:  
    - No access to the internet or external resources.  
    - No training specific to company knowledge.  
    - No memory of previous tasks.  
    - *Essentially, it is a “college grad” every time it generates output*.

  ---

  ## Knowledge Cutoff

- **LLMs retain only the knowledge they were trained on**.  
- **Cannot learn new information dynamically unless retrained**.

  ---

  ## Hallucinations ⚠️

- **LLMs may generate inaccurate or fabricated information**.  
- **Critical for applications requiring high factual accuracy**.

  ---

  ## Input & Output Length Limitations

- **Input and output sizes are constrained**.  
- **Best practice**: Provide information in **smaller chunks** rather than overloading context.  
- **Context window limitations** → *If exceeded, crucial information may be lost*.

  ---

  ## Limitations with Structured Data

- **LLMs struggle with complex structured data formats** *(e.g., tables, databases)*.  
- **Supervised learning models perform better with structured data**.  
- **Information loss occurs when converting structured data into text-based representations**.


  # Generative AI & Data

- **Works best with unstructured data**.  
- **Bias and toxicity**:  
  - Some LLMs can output **toxic or harmful speech**.

  ---

  # Tips for Prompting LLMs

- **Be detailed & specific**.  
- **Guide the model through its answer**.  
- **Experiment & iterate**.

  ---

  ## Fresh College Grad Analogy

- **Be detailed & specific** → Describe sufficient context.  
    
- **Describe & clarify exactly what you want it to do**.  
    
- **Guide the model to think through its answer**:  
    
  - Step 1  
  - Step 2  
  - Step 3 *(Break down complex queries into structured steps).*

  ---

  # Experiment & Iterate

- **Develop a process** ⚠️.  
- **Start with something simple**\!\!

  ### Idea Refinement

- **Be clear and specific** in the prompt.  
- **Think about why the result is not ideal** → Adjust accordingly.  
- **Refine the prompt**.  
- **Repeat the process**.

  ⚠️ **Don’t overthink the initial prompt**.

  ---

  # Confidentiality Concerns

- **Sensitive information** → Be cautious when using AI tools.  
- **Can you trust AI with confidential data?** *(Consider security risks in prompting).*


  # Image Generation – Diffusion Model

- **Learned through supervised learning**.  
- **Training on 100,000 images**.  
- **Noise reduction process**:  
  - Noise → Less noise → Less noise → *(iterative refinement through multiple steps)*.  
- **Adding text to help generate better images**.  
- **We instruct the algorithm to generate an increasingly less noisy version of an image**.

  ---

  # Software Application

- **Labeled data → Train & run model**.  
- **Prompt instructs text**.  
- **Call the LLM model to clarify information**.  
- **Trying generative coding yourself**:  
  - **Code in Python** ⭕.

  ---

  # Building Generative AI Software

- **Scope**:  
  - Build / improve the system → *Creates internal value*.  
  - **Iterate to improve the process**.  
  - **Deploy & monitor performance**.


  # Building AI Software – Experimental Process

- **RAG (Retrieval-Augmented Generation)** → *Allows AI to access documents*.  
- **Fine-tuning** → *Adapting the model to your task*.  
- **Re-training** → *Allows you to pre-train a model for your data*.

  ---

  # Lifecycle of a Generative AI Project

- **Scope the project** → **Build system** → *Increases internal value*.  
- **Deploy & monitor**:  
  - If the AI **does not know the answer**, use **RAG** *(Retrieval-Augmented Generation)*.

  ---

  # Cost Intuition

- **Length of the prompt affects cost**.  
- **Always cheaper for input than output**.

  ### Tokens:

- **A token is a subpart of a word**.  
- Common words are often split into multiple tokens.  
  - Example:  
    - `"truth"` \= **1 token**.  
    - **1 token ≈ ¾ of a word**.  
    - `"lovely"` \= **2 tokens**.  
- **Approximate cost: 0.2¢ per token** *(depending on the model used)*.


  # RAG (Retrieval-Augmented Generation)

1) **Look through a collection of documents** 📄📑📂.  
2) **Incorporate text into a prompt**.  
3) **Generate answers from the new prompt with context**.  
- **RAG helps LLMs generate more informed responses** by leveraging external knowledge.  
- **Answers questions based on website content**.  
  - ⚠️ *Potential risks: clarity and reliability of information retrieved*.

  ---

  # LLM as a Reasoning Engine

- **LLMs function as reasoning engines** → *Process and interpret information*.

  ---

  # Fine-Tuning

- **Pre-training** \= *Learning from a large corpus of words*.  
- **Fine-tuning** \= *Adapting an existing model to specific needs*.

  ### Applications of Fine-Tuning:

- **Refines how the LLM behaves**.  
- **Essential when the task is complex**.  
- **Mimicking writing or speaking styles**.  
- **Helping LLM acquire specialized knowledge**, e.g.:  
  - **Medical** texts.  
  - **Legal** documents.  
  - **Financial documents**.  
- **Allows a smaller model to perform a specialized task efficiently**.  
  


  # Lower Cost & Latency Considerations

- **Lower cost & reduced latency for display**.  
- **Can run on a laptop or PC**.

  ---

  # Pre-Training LLMs

- **Very expensive**.  
- **Example: Bloomberg GPT** → *Processes financial NLP*.  
- **Best to start from a pre-trained LLM** *(rather than training from scratch)*.

  ---

  # Choosing an LLM

- **Model size** *(LLaMA, GPT, etc.)*.  
- **Pattern matching capabilities** *(important for NLP tasks)*.  
- **World knowledge coverage**.  
- **Banking AI**:  
  - **100%: Rich world knowledge** *(functions as a brainstorming partner)*.

  ### Trying Different Models & Choosing What Works Best

- **Closed vs. Open-source**:  
  - **Closed-source**:  
    - **More expensive**.  
    - **Risk of vendor lock-in** *(limited flexibility & dependency on provider)*.  
    - **Typically large & powerful**.  
  - **Open-source**:  
    - **More control over data**.  
    - **Can run on-device** *(more flexible for local processing)*.

  ---

  # Day-to-Day Use of Web-Based LLMs

- **Writing assistant**.  
- **Marketer**.  
- **Recruiter**.  
- **Programmer**.


  # Task Analysis of Jobs

- **Opportunities for Generative AI**.  
- **Identifying automation opportunities**.  
- **A job consists of a collection of tasks** → *Which tasks do we perform?*.

  ---

  ## Augmentation vs. Automation

- **Augment**: *Help humans with a task*.  
- **Automate**: *Fully automate a task*.  
- **Two approaches**:  
  1) **Augmentation**  
  2) **Automation**

  ---

  ## Potential for Automation & Augmentation

1. **Technical feasibility**:  
   - *Can AI do it?* → If yes, **teach & automate**.  
2. **Business value**:  
   - **AI engines**: *RAG, fine-tuning*.

   ---

   ## Business Value Considerations

- **How valuable is it for AI to augment or automate?**  
- **How much time is spent on this task?**  
- **Does automating this task make it**:  
  - **Cheaper?**  
  - **Faster?**  
  - **More consistent?**  
  - → *If yes, it creates business value\!*.

  ---

  # Occupation Databases

- **Source for additional job analysis**:  
  - [**onetonline.org**](https://www.onetonline.org)  
- **Generative AI applications** → *Growing potential for automation*.


  # New Workflows & Opportunities

- **Generative AI will transform workflows**.  
- **AI can generate content for websites** *(e.g., initiating automation)*.  
- **AI-powered tools help build websites**.  
- **Can automate tasks for employees or customers**.

  ---

  # Teams to Build Generative AI Applications

- **Identifying & scoping AI opportunities** → *Key for project success*.  
- **Prompt engineers** → *Not necessarily a dedicated role*.  
- **Automation potential exists across many sectors**.

  ### Roles in AI Teams:

- **Data engineers** → *Organizing & ensuring data quality*.  
- **Data scientists** → *Analyzing data & deriving insights*.  
- **Project managers** → *Coordinating project execution*.

  ---

  # RLHF – Reinforcement Learning from Human Feedback

- **Allows LLMs to learn from human responses**.  
- **Two-step process**:  
  1) **LLM generates responses**.  
  2) **Uses feedback to refine and train itself further**.

  ---

  # AGI – Artificial General Intelligence

- **AI can theoretically perform any task a human can**.  
- **Example**: *Completing a PhD thesis*.  
- **Used as a reasoning engine**.

  ### Responsible AI Considerations:

- **Fairness**.  
- **Transparency**.  
- **Privacy**.  
- **Security**.  
- **Ethical use** → *Ensuring AI is deployed for beneficial purposes*.


  # Encouraging AI-Centric Mindsets

- **Encourage AI adoption & exploration**.  
- **Brainstorm when things go wrong** → *Learn from mistakes & refine approaches*.  
- **Work with a diverse team**.

  ---

  # Intelligence & Power

- **AI has the power to amplify knowledge**.  
- **Can lead to new discoveries & niches**.


  # **Summary**

  ### **Part 1: Introduction to Prompting and Generative AI**

  #### **Key Concepts**

- **Prompting for Everyone – LinkedIn Learning**:  
    
  - Download all files, links, and resources for reference.


- **Generative AI**:  
    
  - Can generate new content.  
  - **LLMs (Large Language Models)** are trained to predict the next token (word, phrase, etc.).  
  - They are trained on **internet, books, and large datasets**.


- **Text-to-Image Models**:  
    
  - **Stable Diffusion**, **DALL·E**, **MidJourney** are examples of AI models that generate images from text.


- **Transformers Architecture**:  
    
  - *"Attention is all you need"* *(Reference to the paper introducing the Transformer model, which powers GPT and similar models.)*


- **Zero-shot Learning vs. Few-shot Learning**:  
    
  - **Zero-shot learning**: AI makes predictions without prior examples.  
  - **Few-shot learning**: AI learns from a few examples to improve accuracy.

  #### **Prompting Basics**

- **A prompt** is a **natural language instruction** that tells the AI what to do.  
- **Designing a prompt**:  
  - **LLMs have only been trained to predict the next word**, meaning they don’t "think" like humans but rather generate sequences based on probabilities.

  ---

  ### **Takeaways from Part 1**

  ✅ Generative AI is built on **transformer models** and trained on vast datasets.  
    ✅ Prompting is how we **communicate with AI models**, shaping the output we get.  
    ✅ **Zero-shot and few-shot learning** are ways AI generalizes or adapts to tasks.  
    ✅ **Text-to-image models like Stable Diffusion** convert words into visuals.

  ---

  **Next Steps:**  
    1️⃣ **Download all resources** from the LinkedIn Learning course for future reference.  
    2️⃣ **Explore text-to-image tools** like DALL·E or MidJourney to understand their potential.  
    3️⃣ **Experiment with zero-shot and few-shot prompts** to see how AI responds differently.  
    4️⃣ **Start crafting simple prompts** to understand how AI interprets them.

  ---

  I'll proceed with the next image now. 🚀

  