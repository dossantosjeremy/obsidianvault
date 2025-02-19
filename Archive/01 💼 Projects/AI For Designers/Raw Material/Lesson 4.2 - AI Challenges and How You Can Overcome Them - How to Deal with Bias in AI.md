---
category: "[[Clippings]]"
author: "[[The Interaction Design Foundation]]"
title: "Lesson 4.2 - AI for Designers"
source: https://www.interaction-design.org/courses/ai-for-designers/lessons/4.2
clipped: 2024-05-07
published: 
topics: 
tags: [clippings]
---

Estimated time to complete: 32 mins

![An image that depicts the use of an image-generating AI tool on a laptop. The laptop is on the desk. Superimposed over this image is the prompt that's being typed into the tool. The prompt reads: "Draw me a scientist working in his laboratory".](https://public-images.interaction-design.org/courses/lesson-materials/04-02-00-prompt-scientist.jpg)

*From dystopian movies to real-life class-action lawsuits, we often see AI as something to be feared. The truth is, we know very little about it. One of the genuine concerns of AI is bias. AI that relies on historical human-generated data is likely to identify false correlations, such as women being unsuitable for hiring, or minorities being criminals. Let’s face our fears and understand the major concerns around AI and see how we might overcome the challenges.* 

When we look at the specific AI tools we’ve grown to love, whether it’s the “context-aware fill” of Photoshop or Grammarly’s tone suggestions, we see very narrow applications of AI. While AI applications make some tasks and roles redundant, professionals have accepted and adopted these tools in their work.

The scary picture of AI comes when we think about general AI or Artificial General Intelligence (AGI), and specifically, if it becomes sentient.

### What Is Human-Cognitive Bias?

Human bias refers to bias that is rooted in the beliefs, attitudes, and prejudices of individuals. It occurs when people have incomplete information and use simple heuristics to help fill in the missing information. Cognitive bias is present across individuals and groups and is fundamental to the human mind.

Psychologists, sociologists and behavioral economists have studied biases and identified several specific types of biases. For example, anchoring bias causes people to focus on, or “anchor”, their judgments around one piece of information, instead of looking at all available information objectively.

Another type of bias is confirmation bias—the tendency to look for, or selectively interpret information that confirms an individual’s beliefs.

Researchers have found that Facebook’s newsfeed algorithm tends to isolate people more than connect them. As the algorithm continually shares posts that people are most interested in, it strengthens people’s ideologies and confirms beliefs, narrowing their world-view.   

Human bias can affect hiring decisions, where an individual may favor or discriminate against a job candidate based on factors like race, gender, or age. It can also affect criminal justice proceedings, where judges, jurors, or law enforcement officers may make biased decisions based on preconceived notions about certain groups of people.

## The Three Levels of Biases

In this video, Ioana Teleanu offers tips and best practices to address AI-induced bias.

**

Show Hide video transcript

1.  00:00:00 --> 00:00:34
    
    Bias is a very important topic when  it comes to AI. Let's explore how biases can seep into systems, the implications they hold and the strategies UX designers can adopt to create unbiased experiences. The three levels of biases are systemic bias, statistical and computational, and human biases. The problem is that biased AI can lead to unfair or discriminatory outcomes,
    
2.  00:00:34 --> 00:01:02
    
    negatively affecting the user experience. These negative outcomes range from minor annoyances, like a voice recognition system struggling with certain accents, to severe implications, such as an unfair loan predictor or biased hiring processes through AI algorithms. So, what can be done? We can address systemic bias by focusing on \*values\*. Even though it might be the hardest to address, being the least obvious,
    
3.  00:01:02 --> 00:01:30
    
    it's also the most important one, having implications on the other two. To start fighting it, we need to align on the values we want it to reflect and then continuously check for the reflection of those values by assessing how well AI aligns with them. We can address computational bias through clean data, making sure that the data that's being fed doesn't contain and thus perpetuate bias.
    
4.  00:01:30 --> 00:02:00
    
    Narrowing the scope of what AI does can help with that. Addressing human bias – we can do that by \*transparency\*. Transparency is a major part of what is called 'explainable AI'. This explainability is essentially the capacity to express why an AI system reached a particular decision, recommendation or prediction. While most of these aren't necessarily in our  control as UX designers, they pertain mostly to data scientists and people in the AI research space.
    
5.  00:02:00 --> 00:02:34
    
    But still, we can advocate and evangelize them with every opportunity. Design conversations matter. And is there anything else we can do as UX designers to fight bias? For starters, we can help by conducting \*diverse and inclusive user research\*. Understand the varied needs, backgrounds  and contexts of our users to ensure your design meets their needs and doesn't favor one group over another. Another way of fighting bias in UX is by \*promoting collaborative design\*.
    
6.  00:02:34 --> 00:03:03
    
    Include users, especially those from underrepresented groups in the design process. This will help prevent the exclusion of certain perspectives and promote a more equitable design decision. You can also fight for establishing ethical guidelines for AI in UX design within your organization. This can help set the standard for unbiased design decisions. And addressing bias in AI UX design isn't just  about improving the product.
    
7.  00:03:03 --> 00:03:19
    
    It's about creating a more inclusive, fair and equitable digital world. By consciously integrating anti-bias strategies in our design processes, we can leverage AI to amplify human potential rather than restrict it.
    

**

*“While humans are the ultimate opaque system, the problem is the speed and scale with which AI can perpetuate bias is much worse.”*

*— Reva Schwartz, Research Scientist at the Information Technology Laboratory, National Institute of Standards and Technology (NIST), US Department of Commerce*.

Researchers from the National Institute of Standards and Technology (NIST) identified three levels of biases: Human, Systemic and Statistical/Computational.

![A Figure that represents categories of AI bias. From the article "Towards a Standard for Identifying and Managing Bias in Artificial Intelligence" by Reva Schwartz, Apostol Vassilev, Kristen K. Greene, Lori Perine, Andrew Burt, Patrick Hall](https://public-images.interaction-design.org/courses/lesson-materials/04-02-02-nist.jpg)

The three levels of bias—human, systemic and statistical/computational—are broad classifications. Each type of bias has multiple subcategories within.

© National Institute of Standards and Technology (NIST), All rights reserved

### Systemic Bias

Systemic bias, often referred to as institutional bias or historical bias, is embedded within systems, institutions, or organizations. The policies, practices, or structures of a system can lead to bias against one or more communities, even if individuals within the system are not intentionally biased.

For example, camera technology is known to be biased against darker skin tones. While photographs of lighter-skinned individuals show facial features well, those of darker-skinned people have poorer dynamic range. It often results in pictures where a face shows no details other than eyes. 

Google acknowledged the bias against people of darker skin and partnered with Harvard professor and sociologist Dr. Ellis Monk to develop the Monk Skin Tone Scale. It incorporated this scale to improve its phone cameras.

![An animated gif of a google search of "bridal makeup looks". Using the Monk Skin Tone Scale in the image search algorithm, the image results go from white women to black women.](https://public-images.interaction-design.org/courses/lesson-materials/04-02-03-google-bridal-makeup.gif)

Google uses the Monk Skin Tone Scale in its image search algorithm to allow users to filter search results by skin tones that represent them.

© **[Google](https://blog.google/products/search/monk-skin-tone-scale/)**, Fair Use 

Google released the scale to allow anyone to use it for research and product development.

### Statistical/Computational Bias

Statistical or computational bias refers to when the sample data does not represent the population. Artificial intelligence systems produce biased results or decisions due to biased data, biased training, or inherent algorithmic design flaws. Computational bias often reveals a systemic bias.

Statistical bias can cause significant harm to certain communities and exponentially amplify systemic biases. For example, algorithms trained on historical crime data may perpetuate bias by recommending extra policing in specific neighborhoods/communities. In the financial sector, computational bias can lead to discriminatory lending practices, impacting loan approval or interest rate decisions based on demographics. 

## How Can Designers Deal with AI Bias?

Unlike the human experience, where we get cues from our environment, AI depends on recorded data to learn from. Much of this data is biased, and AI learns these biases. 

In this video, AI Product Designer Ioana Teleanu dives into the bias and safety issues around artificial general intelligence (AGI).

**

Show Hide video transcript

1.  00:00:00 --> 00:00:34
    
    I hope you feel that AI holds incredible  potential in augmenting our thinking and work if used correctly and with understanding and owning  its limitations. Let's explore a couple of larger themes that we should always bear in mind when designing for and with AI. \*Working with bias\* – datasets have world-views. Machine learning models are inherently biased as they're being fed data that reflects
    
2.  00:00:34 --> 00:01:00
    
    the biases in our society, unless it has been cleaned up. Data that's being fed to machine learning models should be representative, inclusive, good data. It's not the data's fault that discrimination exists in society, but we have a technological opportunity of stopping or at least slowing down the spread of discrimination, non-inclusiveness, racism and more. Take this example:
    
3.  00:01:00 --> 00:01:32
    
    If you go to Midjourney and prompt it to generate an image of a scientist working in a laboratory, guess what you're going to get:  obviously, a white male. Even though the main responsibility is in the hands of data scientists, as designers we can add guardrails which could begin with a bare minimum of communicating potential biases in a transparent manner. \*Safety and Security\* – when people think about safety in the larger topic of AI, they typically start worrying about AGI becoming sentient and having
    
4.  00:01:32 --> 00:02:02
    
    malevolent agency, then deciding to exterminate the human race. Definitely not something that should be on our minds in the near, nor distant – if you ask me – future. But there are a couple of security dangers we should be aware of when designing in this space. An example comes from Microsoft Bing becoming quickly offensive, like in this Twitter screenshot. Another problem is \*data privacy\* – AI systems often rely on large large amounts of data for their functionality,
    
5.  00:02:02 --> 00:02:31
    
    some of which can be sensitive or personally identifiable information. There is a risk of this data being mishandled,  accidentally exposed or deliberately stolen. Also, machine learning models can be deceived and can be exploited by people with bad intentions. There is a thing called 'prompt injection', which is a family of related computer security exploits carried out by getting a machine learning model which was trained to follow human-given instructions
    
6.  00:02:31 --> 00:03:04
    
    to follow instructions provided by a malicious user. Building further on this, there's this concept of \*weaponized AI\*. AI provides a number of tools that are particularly useful for authoritarian governments: smart spyware, face recognition, voice  recognition, which allow widespread surveillance, deep fakes that aid in producing misinformation and so on. Then there's a problem of \*dependance on AI systems\*. Overreliance on AI systems can pose safety risks
    
7.  00:03:04 --> 00:03:30
    
    if these systems fail or make mistakes. This is particularly true in critical systems like healthcare or transportation, where errors can have significant consequences. And there's the interesting thought experiment known as 'the squiggle maximizer', which was formerly known as the paperclip maximizer. The problem presents an AI whose sole goal is to make as many paperclips as possible.
    
8.  00:03:30 --> 00:04:06
    
    A sufficiently intelligent AI would realize sooner or later that humans pose a challenge to its goal on three different counts. Humans could turn the AI off. Humans could change their goals. Humans are made of atoms, which can be turned into paperclips. In all three examples, there would be fewer paperclips in the universe. Therefore, a sufficiently intelligent AI whose sole goal is to make as many paperclips as possible would take over all the matter and energy within reach and prevent itself from being shut off or changed.
    
9.  00:04:06 --> 00:04:30
    
    Pretty scary if you think about it! And it calls for a broader, larger conversation around the safety of these systems, and the measures we're taking to prevent them from losing control in a distant future. And on a more tangible, immediate level, as designers we have the opportunity of adding safety scaffolding to the way interactions with AI systems are designed,
    
10.  00:04:30 --> 00:04:36
    
    accounting for some of the potential risks and minimizing them through our decisions.
    

**

While data scientists are primarily responsible to tackle issues such as bias and data privacy, from a technological perspective, as a designer you must be aware of this vulnerability and design safety nets to protect your users. Here are a few ways in which designers can protect users:

1.  **Recognize bias:** Inclusive design begins with recognizing the possibility of bias and abuse in AI solutions. Ensure everyone on the team is aware of these vulnerabilities so they can identify problems even during product development and testing. If we can see the problem, we can find a workaround and perhaps even solve it.
    
2.  **Incorporate safety features in the interface:** Let users report instances of errors, bias and abuse within your design. If your system produces a purely AI-generated outcome, allow users to configure different parameters and allow them to regenerate results.
    
3.  **Involve the community:** See if it is possible to have a dedicated team that reviews or moderates content. In cases of large systems, you might incentivize your users to be your first line of defense.
    
4.  **Use AI to counter AI:** Companies have developed algorithms to help detect biases in AI. Below are some examples. Each of these tools approaches the question of ethics from a different perspective:
    
    1.  **[Fairlearn](https://fairlearn.org/)**: An open source toolkit from Microsoft for data scientists and developers to **assess** and improve the fairness of their AI systems.
        
    2.  **[Accenture’s AI testing services](https://newsroom.accenture.com/news/accenture-launches-new-artificial-intelligence-testing-services.htm)**: Rely on a “Teach and Test” methodology to **train** AI systems to avoid biases.
        
    3.  **[Bias Analyzer](https://www.pwc.com/us/en/tech-effect/ai-analytics/artificial-intelligence-bias.html)**: A cloud-based application by PwC that flags potential biases in AI **outputs**.
        
    4.  **[FairML](https://dspace.mit.edu/handle/1721.1/108212)**: A toolbox developed by MIT student Julius Adebayo for auditing predictive models by analyzing the model's **inputs**.
        
    5.  **[Google's What-If tool](https://pair-code.github.io/what-if-tool/ai-fairness.html)**: This tool questions what fairness means and allows product developers to sort the data according to a different type of fairness, allowing humans to see the trade-offs in different ways to measure fairness and make decisions accordingly. 
        

## How to Manage Data to Prevent Computational Bias

To ensure a fair AI system, we must **start with clean data**. This may not always be possible, but by acknowledging that data is incomplete, you can work towards gathering better data to refine the system.

1.  Begin by understanding ***why*** **you need the data**. How will the AI system help the user?
    
2.  Identify **what type of user data** is relevant for your AI system. What characteristics and personal/individual-specific data does the system need? For example, if a person’s gender is irrelevant to the benefit the AI system offers, you can skip that data field entirely to prevent false correlations.
    
3.  Examine the existing dataset to **identify potential biases using statistical tools** and models. Does it adequately represent the diversity of your users?
    
4.  **Identify the gaps** in your data and define how you can source the information.
    
5.  When you do gather the data, **clearly explain why you collect the data** and allow users to opt out of sharing the information.
    
6.  Ensure that you **store the data securely and communicate** your security policies and measures with your users.
    
7.  After collecting the data, **format the data consistently**. Real data is not perfect. Some fields might be missing, or users may fill in data in a different format. While humans can easily spot the difference, machines might misinterpret the data.
    
8.  Continuously **update the dataset with live data** to improve the AI system.
    
9.  **Keep testing the AI system**. No algorithmic model will be perfect at the outset and will constantly need monitoring and tweaking. 
    

## The Take Away

Bias in AI is a pervasive issue with far-reaching consequences. Bias can manifest in many forms, including favoritism, discrimination, and stereotyping. It takes various forms, including human bias, systemic bias, and statistical/computational bias. Human bias arises from preconceived notions and prejudices, which can inadvertently infiltrate AI systems. Systemic bias, on the other hand, is deeply ingrained within systems, institutions, or organizations, stemming from biased policies or practices. Statistical/computational bias results from biased data, training, or algorithmic design flaws in AI systems. Addressing these multiple facets of bias is crucial to ensure fair and ethical AI applications.

Generally, bias in AI can be unintentional, but sometimes it's introduced deliberately, which raises ethical concerns. To address this complex problem, it's crucial to understand the different types and levels of bias that can emerge in AI systems. While much of the data operations fall on data scientists’ shoulders, as UX designers, we can: 

1.  Conduct diverse and inclusive user research to understand different user needs and backgrounds to ensure data and design don't favor one group.
    
2.  Promote and implement collaborative design by involving underrepresented groups in the design process to include diverse perspectives.
    
3.  Advocate for, and establish ethical guidelines for AI within your organization to set unbiased design standards. This includes collecting data responsibly and rigorously testing the algorithms.
    
4.  Build safeguards and disclaimers in interfaces to encourage users to proceed cautiously when using AI-generated results and allow them to report biased outcomes.
    

## References and Where to Learn More

Learn more about **[Anchoring Bias](https://www.interaction-design.org/literature/topics/anchoring)**.

Google’s People + AI Guidebook offers a detailed guideline on responsible data collection in **[Data Collection + Evaluation](https://pair.withgoogle.com/chapter/data-collection/)**.

For more on the Monk Skin Tone Scale, see **[Improving Skin Tone Representation across Google](https://blog.google/products/search/monk-skin-tone-scale/)**. 

**[Towards a Standard for Identifying and Managing Bias in Artificial Intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence)** is a comprehensive paper on the different categories of bias and how to manage them in AI systems. 

Watch this webinar with John Buyers, Emre Kazim and Reva Schwartz to understand biases in AI: **[AI and ethics: How can we manage harmful bias?](https://www.rics.org/news-insights/wbef/ai-and-ethics-how-can-we-manage-harmful-bias)** 

Examine this Reuters report on **[Amazon scrapping a secret AI recruiting tool that showed bias against women](https://www.reuters.com/article/us-amazon-com-jobs-automation-insight-idUSKCN1MK08G)**. 

Here’s the study in The Proceedings of the National Academy of Sciences (PNAS) on **[The spreading of misinformation online](https://www.pnas.org/doi/full/10.1073/pnas.1517441113)**. 

Find out more about the **[NIST Risk Management Framework to Improve Trustworthiness of Artificial Intelligence](https://www.nist.gov/news-events/news/2023/01/nist-risk-management-framework-aims-improve-trustworthiness-artificial)**.

## Answer Questions to Get Your Certificate

Why is it important to answer these questions?

-   You’ll significantly improve your **ability to remember** what you’ve just learnt
-   You get closer to **your Course Certificate**
-   Get a **distinction on your certificate** when you score 90% and higher
-   Research shows that when you answer questions, you’ll greatly improve your ability to transfer knowledge into new contexts, such as your **current or future workplace**.