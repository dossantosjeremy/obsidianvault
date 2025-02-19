# **Generative AI Training Notes**

## 1\. Introduction to Generative AI

* **Definition:** Generative AI can produce content like text and audio and serves as a developer tool. (Based on the Coursera Generative AI for Everyone course)  
* **Impact:** Generative AI can add 2.6 \- 4.4 trillion annually (McKinsey) to the global GDP and raise global GDP by 7% in many sectors (Goldman Sachs), and 10% of tasks could be caused by policy inertia (OpenAI). (Based on the Coursera Generative AI for Everyone course)  
* **DeepLearning.AI:** Generative AI makes briefing systems more accessible. (Based on the Coursera Generative AI for Everyone course)  
* **Types of Generation:** Text, audio, and video. (Based on the Coursera Generative AI for Everyone course)

  ## 2\. How Generative AI Works

* **AI as a set of tools.** (Based on the Coursera Generative AI for Everyone course)  
* **Learning Types:** (Based on the Coursera Generative AI for Everyone course)  
  * Supervised Learning: Input (A) → Output (B), example: spam filters.  
  * Unsupervised Learning: Self-improvement learning (possibly reinforcement learning?).  
* **Supervised Learning Applications:** Online advertising, self-driving cars, healthcare, defect detection, speech recognition (transcripts), restaurant reviews. (Based on the Coursera Generative AI for Everyone course)  
* **AI Model Growth (2010-2020):** Small vs. Large AI models. Small AI models: Limited data usage. Large AI models: More data, improved performance. (Based on the Coursera Generative AI for Everyone course)

  ## 3\. Large Language Models (LLMs)

* **LLMs generate text based on input** and predict the next word using supervised learning. (Based on the Coursera Generative AI for Everyone course)  
* **Scale:** Trillions of words, example: ChatGPT. (Based on the Coursera Generative AI for Everyone course)  
* **LLM as a Thought Partner:** Finds information but can produce hallucinations ⚠️. (Based on the Coursera Generative AI for Everyone course)  
* **Web Teaches Us LLMs:** Generative AI as a versatile, general-purpose technology. (Based on the Coursera Generative AI for Everyone course)

  ## 4\. Framework of Tasks

* **Text-based tasks:** Brainstorming, writing, reading, chatting. (Based on the Coursera Generative AI for Everyone course)  
* **Web-based applications:** Web-based interface (ChatGPT, Bard, Bing, etc.) and API-based applications (software-integrated AI). (Based on the Coursera Generative AI for Everyone course)  
* **Writing:** Use as a creative partner: generating names, developing ideas to increase skills. Provide CONTEXT \+ BACKGROUND INFO (for better responses). (Based on the Coursera Generative AI for Everyone course)  
* **Translation:** Performs well. (Based on the Coursera Generative AI for Everyone course)  
* **Reading:** Proofreading, summarizing long articles, summarizing text following a word limit (e.g., 300 words or fewer). (Based on the Coursera Generative AI for Everyone course)  
* **Summarizing Call Center Concerns:** Generate summaries of conversations, review summaries → Spot trends, use summaries in software applications. (Based on the Coursera Generative AI for Everyone course)  
* **Customer Emails:** Email routing → Will need context. Provide the list of existing departments, for instance. Track customer sentiment over time. Dashboard to track sentiments over time. (Based on the Coursera Generative AI for Everyone course)  
* **Chatting Tasks:** Customer service, career coaching, recipe ideas. (Based on the Coursera Generative AI for Everyone course)  
* **IT Service Chatbot:** Interaction flow involving human support and automated responses. (Based on the Coursera Generative AI for Everyone course)  
  * Human support.  
  * Bot triages for humans.  
  * Chatbots only (fully automated response).  
  * Humans remain in the loop for critical support cases.  
  * Saves time by reducing manual workload.

  ## 5\. Deploying Chatbots

* **Advice:** (Based on the Coursera Generative AI for Everyone course)  
  1. Start internal-facing chatbots.  
  2. Deploy with human-in-the-loop.  
  3. Allow the bot to communicate directly (once reliability is confirmed).  
* **LLM Capabilities and Limitations:** Think of LLMs as fresh college graduates with no internet access, company-specific training, or memory. (Based on the Coursera Generative AI for Everyone course)  
* **Knowledge Cutoff:** LLMs retain only the knowledge they were trained on and cannot dynamically learn new information unless retrained. (Based on the Coursera Generative AI for Everyone course)  
* **Hallucinations:** LLMs may generate inaccurate or fabricated information ⚠️. Critical for applications requiring high factual accuracy. (Based on the Coursera Generative AI for Everyone course)  
* **Input & Output Length Limitations:** Constrained input and output sizes; use smaller chunks. Context window limitations → If exceeded, crucial information may be lost. (Based on the Coursera Generative AI for Everyone course)  
* **Limitations with Structured Data:** LLMs struggle with complex structured data (e.g., tables, databases); supervised learning models are better for this. Information loss occurs when converting structured data into text-based representations. (Based on the Coursera Generative AI for Everyone course)

  ## 6\. Generative AI & Data

* Works best with unstructured data. (Based on the Coursera Generative AI for Everyone course)  
* Bias and Toxicity: Potential for toxic or harmful speech. (Based on the Coursera Generative AI for Everyone course)

  ## 7\. Tips for Prompting LLMs

* Be detailed & specific.  
* Guide the model through its answer.  
* Experiment & iterate. (Based on the Coursera Generative AI for Everyone course)  
* **Fresh College Grad Analogy:** Describe sufficient context and clarify exactly what you want it to do. (Based on the Coursera Generative AI for Everyone course)

  ## 8\. Experiment & Iterate

* Develop a process ⚠️.  
* Start with something simple\!\! (Based on the Coursera Generative AI for Everyone course)  
* **Idea Refinement:** (Based on the Coursera Generative AI for Everyone course)  
  * Be clear and specific in the prompt.  
  * Think about why the result is not ideal → Adjust accordingly.  
  * Refine the prompt.  
  * Repeat the process.  
  * ⚠️ Don’t overthink the initial prompt.  
* **Confidentiality Concerns:** Be cautious with sensitive information. Can you trust AI with confidential data? (Consider security risks in prompting). (Based on the Coursera Generative AI for Everyone course)

  ## 9\. Image Generation – Diffusion Model

* Learned through supervised learning. (Based on the Coursera Generative AI for Everyone course)  
* Noise Reduction Process: Noise → Less noise → Less noise → (iterative refinement through multiple steps). (Based on the Coursera Generative AI for Everyone course)  
* Adding Text: Helps generate better images. We instruct the algorithm to generate an increasingly less noisy version of an image. (Based on the Coursera Generative AI for Everyone course)

  ## 10\. Building Generative AI Software

* **Scope:** Build / improve the system → Creates internal value. Iterate to improve the process. Deploy & monitor performance. (Based on the Coursera Generative AI for Everyone course)  
* **Experimental Process:** (Based on the Coursera Generative AI for Everyone course)  
  * RAG (Retrieval-Augmented Generation) → Allows AI to access documents.  
  * Fine-tuning → Adapting the model to your task.  
  * Re-training → Allows you to pre-train a model for your data.  
* **Lifecycle:** Scope the project → Build system → Increases internal value. Deploy & monitor; use RAG (Retrieval-Augmented Generation) if the AI does not know the answer. (Based on the Coursera Generative AI for Everyone course)

  ## 11\. Cost Intuition

* Length of prompt affects cost. Always cheaper for input than output. (Based on the Coursera Generative AI for Everyone course)  
* **Tokens:** Subparts of words. (Based on the Coursera Generative AI for Everyone course)  
  * A token is a subpart of a word.  
  * Common words are often split into multiple tokens.  
  * Example:  
    * "truth" \= 1 token.  
    * 1 token ≈ ¾ of a word.  
    * "lovely" \= 2 tokens.  
  * Approximate cost: 0.2¢ per token (depending on the model used).

  ## 12\. RAG (Retrieval-Augmented Generation)

* **Process:** (Based on the Coursera Generative AI for Everyone course)  
  1. Look through a collection of documents 📄📑📂.  
  2. Incorporate text into a prompt.  
  3. Generate answers from the new prompt with context.  
* **Benefits:** Helps LLMs generate more informed responses by leveraging external knowledge. Answers questions based on website content. (Based on the Coursera Generative AI for Everyone course)  
* **Risks:** Potential issues with clarity and reliability of information retrieved ⚠️. (Based on the Coursera Generative AI for Everyone course)

  ## 13\. LLM as a Reasoning Engine

* LLMs function as reasoning engines to process and interpret information. (Based on the Coursera Generative AI for Everyone course)

  ## 14\. Fine-Tuning

* Adapting an existing model to specific needs. (Based on the Coursera Generative AI for Everyone course)  
  * Pre-training \= Learning from a large corpus of words.  
  * Fine-tuning \= Adapting an existing model to specific needs.  
* **Applications:** (Based on the Coursera Generative AI for Everyone course)  
  * Refines how the LLM behaves.  
  * Essential when the task is complex.  
  * Mimicking writing or speaking styles.  
  * Helping LLM acquire specialized knowledge, e.g.:  
    * Medical texts.  
    * Legal documents.  
    * Financial documents.  
  * Allows a smaller model to perform a specialized task efficiently.  
* **Benefits:** Lowers cost & reduced latency for display. Can run on a laptop or PC. (Based on the Coursera Generative AI for Everyone course)

  ## 15\. Pre-Training LLMs

* Very expensive. (Based on the Coursera Generative AI for Everyone course)  
* Example: Bloomberg GPT → Processes financial NLP.  
* Best to start from a pre-trained LLM (rather than training from scratch). (Based on the Coursera Generative AI for Everyone course)

  ## 16\. Choosing an LLM

* Consider model size (LLaMA, GPT, etc.), pattern matching capabilities (important for NLP tasks), and world knowledge coverage. (Based on the Coursera Generative AI for Everyone course)  
* **Closed vs. Open-Source:** (Based on the Coursera Generative AI for Everyone course)  
  * Closed-source: More expensive. Risk of vendor lock-in (limited flexibility & dependency on provider). Typically large & powerful.  
  * Open-source: More control over data. Can run on-device (more flexible for local processing).

  ## 17\. Day-to-Day Use of Web-Based LLMs

* Applications: Writing assistant, marketer, recruiter, programmer. (Based on the Coursera Generative AI for Everyone course)

  ## 18\. Task Analysis of Jobs

* Opportunities for Generative AI in identifying automation opportunities. (Based on the Coursera Generative AI for Everyone course)  
* Augmentation vs. Automation: Help humans with a task / Fully automate a task. (Based on the Coursera Generative AI for Everyone course)  
  * Two approaches:  
    1. Augmentation  
    2. Automation  
* **Technical Feasibility & Business Value:** Assessing if AI can do it and if it adds value. (Based on the Coursera Generative AI for Everyone course)  
  * Technical feasibility: Can AI do it? → If yes, teach & automate.  
  * Business value: AI engines: RAG, fine-tuning. (Based on the Coursera Generative AI for Everyone course)  
* **Occupation Databases:** onetonline.org. (Based on the Coursera Generative AI for Everyone course)  
* **New Workflows & Opportunities:** Transforming workflows and automating tasks. (Based on the Coursera Generative AI for Everyone course)  
  * Generative AI will transform workflows.  
  * AI can generate content for websites (e.g., initiating automation).  
  * AI-powered tools help build websites.  
  * Can automate tasks for employees or customers.

  ## 19\. Teams to Build Generative AI Applications

* Identifying & Scoping: Key for project success. (Based on the Coursera Generative AI for Everyone course)  
* Roles: (Based on the Coursera Generative AI for Everyone course)  
  * Data engineers → Organizing & ensuring data quality.  
  * Data scientists → Analyzing data & deriving insights.  
  * Project managers → Coordinating project execution.  
  * Prompt engineers → Not necessarily a dedicated role.  
* Prompt Engineers: Not necessarily a dedicated role. Automation potential exists across many sectors. (Based on the Coursera Generative AI for Everyone course)

  ## 20\. RLHF – Reinforcement Learning from Human Feedback

* Allows LLMs to learn from human responses. (Based on the Coursera Generative AI for Everyone course)  
* Two-step process:  
  1. LLM generates responses.  
  2. Uses feedback to refine and train itself further.

  ## 21\. AGI – Artificial General Intelligence

* AI can theoretically perform any task a human can. (Based on the Coursera Generative AI for Everyone course)  
* Example: Completing a PhD thesis.  
* Used as a reasoning engine.  
* **Responsible AI Considerations:** Fairness, transparency, privacy, security, and ethical use. Ensuring AI is deployed for beneficial purposes. (Based on the Coursera Generative AI for Everyone course)

  ## 22\. Encouraging AI-Centric Mindsets

* Promote AI adoption & exploration.  
* Brainstorm when things go wrong → Learn from mistakes & refine approaches.  
* Work with a diverse team. (Based on the Coursera Generative AI for Everyone course)  
* AI amplifies knowledge and leads to new discoveries & niches. (Based on the Coursera Generative AI for Everyone course)

  ## 23\. Prompting for Everyone – LinkedIn Learning

* **Key Concepts:** (Based on the LinkedIn Learning "Prompting for Everyone" course)  
  * Generative AI can generate new content.  
  * LLMs are trained to predict the next token.  
    * Trained on internet, books...  
  * Text-to-Image Models like Stable Diffusion, DALL·E, MidJourney.  
  * Transformers Architecture: "Attention is all you need" (reference to the foundational paper on Transformers)  
  * Zero-shot Learning vs. Few-shot Learning:  
    * Zero-shot learning: AI makes predictions without prior examples.  
    * Few-shot learning: AI learns from a few examples to improve accuracy.  
* **Prompting Basics:** (Based on the LinkedIn Learning "Prompting for Everyone" course)  
  * A prompt is a natural language instruction guiding the AI's response.  
  * LLMs do not "think" but rather generate text based on probabilities of word sequences.  
  * Download all the files.  
  * Links and resources.

  ## 24\. Components of a Prompt

* Instruction (Think questions and opinions) (Based on the LinkedIn Learning "Prompting for Everyone" course)  
* Examples and data (Based on the LinkedIn Learning "Prompting for Everyone" course)

  ## 25\. Prompt Engineering

* Requires domain knowledge. (Based on the LinkedIn Learning "Prompting for Everyone" course)  
  * Formulate good & bad structured data.  
  * Use prompt engineering, iterate & require exploration.  
* **Prompt engineering tools:** (Based on the LinkedIn Learning "Prompting for Everyone" course)  
  * Modify outputs according to code, not a concept.  
  * Human feedback loop (Allows refining responses based on human evaluation)  
  * Scale feedback loop  
  * Reinforcement learning with human feedback (RLHF)

  ## 26\. Model Response

* Stochastic \= Random (LLM outputs are probabilistic rather than deterministic) (Based on the LinkedIn Learning "Prompting for Everyone" course)  
* **Delimiters** (Based on the LinkedIn Learning "Prompting for Everyone" course)  
  * Prompting using natural language requires rules and patterns.  
  * Use \<|end of prompt|\> to set boundaries for models that do not naturally detect mile changes.  
  * Parameter to tweak variability  
    * Temperature (Higher values increase randomness, lower values make outputs more deterministic)  
    * Top-p (Nucleus Sampling) (Limits sampling to the most probable tokens)  
* **COT (Chain of Thought)**  
  * Cleaning thought process.  
  * Force LLM to follow a reasoning path. (Based on the LinkedIn Learning "Prompting for Everyone" course)

  ## 27\. Performance

* Performance defined in a prompt (Performance can be directly influenced by how a prompt is structured) (Based on the LinkedIn Learning "Prompting for Everyone" course)  
* Use language (Crafting a prompt with clear and precise wording improves outcomes) (Based on the LinkedIn Learning "Prompting for Everyone" course)

  ## 28\. Functions in a Prompt \- Performance

* Creating a flowchart is a way of structuring and giving factors. (Based on the LinkedIn Learning "Prompting for Everyone" course)  
* Include at least questions & metrics. (Based on the LinkedIn Learning "Prompting for Everyone" course)

  ## 29\. Clean Files \- AI Model Awareness

* Always double-check inputs from AI (Based on the LinkedIn Learning "Prompting for Everyone" course)  
* Preengineering your prompts \= use a library of prompts (Based on the LinkedIn Learning "Prompting for Everyone" course)

  ## 30\. Using AI to Plan a Project

* Feed the AI details, goals, and challenges. (Based on the LinkedIn Learning "Prompting for Everyone" course)

  ## 31\. Giving AI a Good Brief

* Provide as much detail as necessary. (Based on the LinkedIn Learning "Prompting for Everyone" course)  
* Guide me with ideas → Stop and wait for my output. (Based on the LinkedIn Learning "Prompting for Everyone" course)

  ## 32\. LinkedIn Learning Course Summary: Prompting for Everyone

* Based on the LinkedIn Learning "Prompting for Everyone" course.  
  * **Understanding Generative AI and LLMs**  
    * Generative AI creates new content by predicting the next token based on trained data  
    * AI models do not inherently "think" but generate outputs based on probability  
    * Text-to-Image Models  
    * Transformer Architecture  
    * Zero-Shot Learning  
  * **The Core of Prompting**  
    * Components of a Good Prompt  
    * Prompt Engineering  
    * Prompt Engineering Tools  
  * **Model Behavior & Response Variability**  
    * Understanding Model Responses  
    * Tuning AI Outputs  
    * Chain of Thought (CoT)  
  * **Performance Optimization in Prompting**  
    * Defining Performance in a Prompt  
    * Balancing AI and Human Input  
    * Boosting Productivity with AI  
  * **AI in Practical Applications**  
    * Task Automation with AI  
    * Using AI for Argumentation & Critical Thinking  
    * Generating Better Ideas with AI  
  * **Ensuring AI Reliability & Secure Workflows**  
    * Best Practices for Data Handling  
    * Maintaining Secure Workflows

  ## 33\. Prompt Engineering \- IBM

* Prompt engineering (Based on IBM content)  
  * Writing a prompt that is effective & direct  
  * IBM Prompt Lab, specialized tools & books  
  * Interview Pattern  
  * Chain of Thought  
  * Tree of Thought  
  * Zero-shot  
  * Few-shot  
* **What is a Prompt?** (Based on IBM content)  
  * IBM makes clear that a clear sentence matters  
  * Two key factors for success:  
    * Clarity  
    * Contextual relevance  
* **Boosting Performance with Prompt Engineering** (Based on IBM content)  
  * Best performance model synergy  
  * Model hard-coded constraints  
  * Enhance model reactivity  
* **Process of Defining Effective Prompts** (Based on IBM content)  
  * Understanding model behavior  
  * Technical learning  
  * Iterative Process:  
    1. Define goal  
    2. Apply prompt  
    3. Analyze response  
    4. Test & refine  
    5. Iterate on the process  
* **Best Practices in Prompt Creation** (Based on IBM content)  
  * Relevant context  
  * Precision  
  * Clarity  
  * Concise language  
* **Common Prompt Engineering Principles** (Based on IBM content)  
  * Clear prompts  
  * Confidence & Understanding  
  * Adjacent Examples  
  * Comparison of Model Outputs  
  * Crafting the Right Multi-Prompt Strategy  
* **WatsonX AI Prompt Lab \- Spellbook Build App** (Based on IBM content)  
  * Experimenting with Prompts  
    * Best performance  
    * Certification  
    * Question answering  
    * Automatic summarization  
* **Experiments in Prompts** (Based on IBM content)  
  * Edit test prompts  
  * Use local prompt spaces  
  * Work with examples  
* **Refining Prompts** (Based on IBM content)  
  * Loop through prompts to refine AI model outputs.  
  * Context & clarity are key to successful prompting.  
  * Ask: What is the best way to prompt?  
  * Design model for correct outputs.  
  * Provide clear context.  
  * Offer examples.  
* **Testing Prompt Effectiveness** (Based on IBM content)  
  * Ask ChatGPT: How can I do it?  
  * Test token prompts for optimization.  
  * Text prompts instruct AI to give an LLM guidance:  
    1. Test AI parameters  
    2. Narrow examples  
    3. Generate in an LLM-based format  
* **Zero-Shot Learning for Models** (Based on IBM content)  
  * Evaluate outputs flexibly  
  * Train models to test narrow-focused feedback  
  * Use optimized examples for few-shot learning  
  * Chain of Thought setup helps a lot.  
* **Iterative Question Approaches** (Based on IBM content)  
  * Backward & Forward Reasoning  
  * Chain of Thought Approaches  
  * Pattern-Based Prompting  
  * Simulated Conversations for Training  
* **Chain of Thought: Planning Approach** (Based on IBM content)  
  * Improves AI’s reasoning through structured questioning. (Based on IBM content)  
  * Works well with LLM feedback models and iterative questioning. (Based on IBM content)  
  * How it works:  
    * Prompt → Q & A → Plan Q  
  * Build logical reasoning in AI-generated responses. (Based on IBM content)  
* **Tree of Thought Approach** (Based on IBM content)  
  * Structured questioning for multi-layered evaluation. (Based on IBM content)  
  * Each thought or idea launches another. (Based on IBM content)  
  * This prevents AI from only generating a single response. (Based on IBM content)  
* **Evaluating Prompt Quality** (Based on IBM content)  
  * Check key factors in prompt engineering:  
    * Context & analysis  
    * Clarity of thought  
    * Precision & structure  
    * Objective granularity  
    * Summaries  
    * Avoid generic & vague data  
    * Model consistency & clarity  
* **Prompt Labs** (Based on IBM content)  
  * Ensuring the quality & accuracy of AI-driven responses.  
  * Providing LLMs for guided responses.  
  * Using multiple AI models for evaluation.  
  * Container prompts & transcripts for AI model training.  
* **Image Prompting Strategies** (Based on IBM content)  
  * Image prompts affect accuracy of model outputs.  
  * Choosing the right parameters changes AI-rendered images.  
  * Autotagging summaries help refine prompts.  
  * Style & art nuances impact output.  
  * Well-known brands & aesthetics influence generated visuals.  
* **Quality Boosters for AI Image Generation** (Based on IBM content)  
  * Example: High resolution settings.  
  * Notable terms:  
    * "High resolution," "2K," "4K," "hyper-detailed," "sharp focus," "complementary colors."  
  * Texture:  
    * Sharp, crisp details, fine lines, blurred backgrounds.  
  * Repetition:  
    * Using multiple image variations for refinement.  
  * Weighted Terms:  
    * Assigning emotional or aesthetic weight to specific elements.  
    * Example: "warm:10" (assigns a high weight to warmth in an image)  
  * Fixed Deformed Generators:  
    * Pixel distortion techniques.

  