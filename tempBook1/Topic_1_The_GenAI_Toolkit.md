# Topic 1: The Basic GenAI Toolkit 

Generative Artificial Intelligence (GenAI) has become one of the most transformative technological advancements of recent years, enabling systems to generate text, images, code, and even entire business solutions. To make the most of these tools, it is essential to understand not only what GenAI can do, but also how to interact with it effectively. This topic introduces the fundamentals of GenAI with a focus on **Prompt Engineering**—the art and science of crafting inputs that guide AI models toward accurate, creative, and useful outputs. By mastering prompt engineering, students will gain practical skills to explore the capabilities and limitations of GenAI, preparing them to apply these tools strategically in entrepreneurial and problem-solving contexts.  

---

## 1. Prompt Engineering Basics

### 1.1 Learning Objectives
- Understand the purpose and scope of prompt engineering.
- Identify the components that make up an effective prompt.
- Identify and apply different types of prompt design patterns.
- Compare how prompt structures influence AI outputs.
- Practice prompt improvement through iteration.

### 1.2 What is Prompt Engineering?

Prompt engineering is the practice of crafting effective inputs (prompts) for large language models (LLMs) to produce accurate, relevant, and useful outputs.

Unlike traditional programming, where you write rigid code, prompt engineering is about **communicating naturally** with an AI system — and doing so **strategically**.

### 1.3 Anatomy of a Prompt

A good prompt typically includes:

1. **Instruction**: What you want the model to do.
   - _e.g., "Summarize the text below in bullet points."_
2. **Context** (optional): Background information or framing.
   - _e.g., "You are a customer support agent."_
3. **Input Data**: The text, question, or file the model will process.
   - _e.g., "Customer review: The product broke in 2 days..."_
4. **Output Format** (optional): Desired structure or style.
   - _e.g., "Respond in JSON format with sentiment and category."_

### 1.4 Why Prompt Engineering Matters

- It **boosts model performance** without changing the model itself.
- It helps tailor responses to specific **tasks and audiences**.
- It allows you to guide the model toward **more reliable, interpretable results**.

### 1.5 Example Prompt
```
You are a scientific editor. Summarize the text below into 3 bullet points for a general audience.

Text:
Prompt engineering is the practice of crafting effective inputs (prompts) to guide generative AI models like ChatGPT, Claude, or Gemini toward producing accurate, relevant, and useful outputs. It involves understanding how AI interprets language and strategically structuring prompts to achieve specific goals, whether it is summarizing text, generating code, analyzing data, or creating content. Good prompt engineering can significantly enhance the quality of AI responses, making it a critical skill for maximizing productivity and creativity with AI tools.
```

### Exercise 1: Deconstruct This Prompt

Given the prompt below, identify its components:
```
You are a legal assistant. Given the client's message, extract the key legal issue and relevant date in bullet points.

Message:
I was evicted without notice on June 3rd even though I paid rent until July...
```

### 1.6 Why Prompt Patterns Matter

Prompt patterns are reusable structures that help you get consistent, high-quality results from language models. Understanding them empowers you to choose the right style for your goal.

### 1.7 Common Prompt Types

1. **Instructional Prompts**
Directly ask the model to perform a task, e.g.:
```
"Summarize the following article in three sentences."
```
2. **Role-Based Prompts**
Assign the model a specific identity or role to guide tone and knowledge.
```
You are a career coach. Give me advice on how to negotiate a salary raise.
```
3. **Chain-of-Thought Prompts**
Encourage step-by-step reasoning or breakdown of complex tasks.
```
What is the square root of 144? Explain the steps before giving the answer.
```
4. **Zero-Shot Prompts**
Provide only the instruction and input — no examples.
```
Translate the following sentence into Portuguese: "How are you?"
```
5. **Few-Shot Prompts**
Include examples of input/output pairs to guide the model.
```
Translate the following:
English: Good morning → Portuguese: Bom dia
English: Thank you → Portuguese: Obrigado
English: I’m hungry → Portuguese:
```
### 1.8 Prompt Comparison

| Pattern           | Use Case                               | Example Role/Task                              |
|------------------|----------------------------------------|------------------------------------------------|
| Instructional     | Clear single-step tasks                 | “Summarize this paragraph.”                    |
| Role-Based        | Tone/personality alignment              | “You are a financial advisor…”                |
| Chain-of-Thought  | Complex reasoning, multi-step problems  | “Explain each step before giving the answer.”  |
| Zero-Shot         | Fast and generic tasks                  | “Translate to Spanish…”                       |
| Few-Shot          | Custom structure or format              | “English → French examples…”                  |

### Exercise 2: Prompt Comparison Activity

Use the following task and try prompting it in three different styles.

**Task**: Recommend three books for someone interested in artificial intelligence.

### 1.9 Why Iteration Matters

Prompting is often **not a one-shot process**. Even good prompts may return incomplete, vague, or misleading results. The key is to **test, analyze, and refine**.

Iteration helps you:
- Clarify vague requests
- Add or remove unnecessary detail
- Adjust tone or output format
- Explore different framing approaches

### 1.10 The Iterative Prompting Process

1. **Draft the initial prompt**  
   _Write a basic version of your request._

2. **Review the output**  
   _Is it accurate? Detailed enough? In the right tone or format?_

3. **Refine the prompt**  
   _Add missing instructions, clarify goals, or adjust roles._

4. **Test again**  
   _Compare outputs, note improvements, and repeat if needed._

### Exercise 3: Prompt Iteration and Debugging Examples

**Poor Prompt:**
```
Explain climate change.
```
**Improved Prompt (Iteration 1):**
```
Explain climate change in simple terms for a high school student, using 3 key points.
```
**Improved Prompt (Iteration 2):**
```
Explain climate change in simple terms for a high school student. Use 3 bullet points and include one analogy related to daily life.
```

### Exercise 4: Prompt Experiment Classwork

```
You support retail sales analysis at Contoso. The VP of Regional Sales needs an assessment to guide monthly discount strategies.
Task: Compare net ‘ Sales’ for this observation to average for all ‘Product’ sold under this ‘Discount Band’, and ‘ Sales’ for this ‘Product’ in this ‘Month’.
| Segment | Country | Product | Discount Band | Sales | Month | Year |
| Government | United States of America | Montana | Medium | 178500.35 | October | 2014 |

Step 1 – Chain-of-Thought (show your work):
1. Compare Averages: Current vs average Sales with this Product and Discount Band, and vs average Sales with this Product and Month.
2. Compare Segment: Calculate and compare this point to performance of this Product in each other Segment in this Country.
3. Compare Country: Calculate and compare this point to all performance in the Country, and performance in all Countries.
4. Compare Product: Calculate and compare this point to all performance of this Product, and performance of all Products.
5. Compare and Discuss: Review this point in comparison to historical, country, and product performance, and infer overall performance.
Step 2 – Analysis:
Write a concise paragraph identifying trends and discussing likely drivers behind any variance.
Step 3 – Prediction:
Based on findings, advise whether Contoso should continue, adjust, or halt this Discount Band.
```

### 1.11 Tips for Troubleshooting and Improving Prompts

- If output is **too generic**: Add specific instructions or examples.
- If output **hallucinates**: Ask the model to “only use provided information.”
- If output **misses important parts**: Reframe the prompt with clearer structure.
- If output is **inconsistent**: Use role and format specifications.

**Hallucination** is when a model confidently outputs incorrect or invented information.
  
### 1.12 Assessing Prompt Quality

Five criteria to judge the effectiveness of a prompt-output pair:

| Criterion         | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **Relevance**     | Is the response aligned with the prompt's intent?                          |
| **Completeness**  | Does the answer cover all requested aspects?                               |
| **Clarity**       | Is the response easy to understand and well-structured?                    |
| **Factual Accuracy** | Are the claims and data points correct and verifiable?                 |
| **Format**        | Does the output follow the requested format or style?                      |

**Techniques to Reduce or Identify Hallucinations**
- Ask the model to **cite its sources** or say "Only use the provided text/file."
- Clarify that the model should say **“I don't know”** if unsure.
- Specify that the answer should be based **only on the uploaded file** or context.

---

## 2. Useful GenAI Tools 

### ChatGPT
ChatGPT is a versatile AI language model developed by OpenAI, capable of interpreting natural language, performing various statistical analyses, coding in Python, and generating data visualizations such as bar charts, pie charts, scatter plots, and histograms. It supports data uploads in formats like CSV, XLSX, PDF, and JSON (up to 50MB) and can integrate with cloud storage like Google Drive and OneDrive. ChatGPT excels in broad AI capabilities including data analysis, summarization, and storytelling. It requires web browsing for real-time data updates.
Access ChatGPT here: [https://chat.openai.com/]

### Claude.ai
Claude.ai is an AI assistant with strong natural language processing capabilities and expanding tools for data analysis. It supports data uploads and can process data using JavaScript within its Analysis Tool. Claude.ai can perform complex calculations, data manipulation, and create visualizations through its Analysis Tool and Artifacts feature. It primarily analyzes uploaded data and does not rely on real-time web browsing.
Access Claude.ai here: [https://claude.ai/]

### Perplexity
Perplexity is a research-focused AI platform emphasizing data-driven insights and real-time web search integration. It allows file uploads for analysis and uses coding capabilities within its Deep Research mode to identify patterns, trends, and anomalies. Perplexity integrates web search for broader context and is particularly strong in providing current data and research-backed answers.
Access Perplexity here: [https://www.perplexity.ai]

### Grok
Grok is a conversational AI developed by Elon Musk’s xAI, designed to provide witty, insightful, and real-time responses. Integrated with X (formerly Twitter), Grok emphasizes reasoning and humor, offering a more personality-driven interaction style. It supports real-time data access and is positioned as a competitor to ChatGPT and Gemini. Access Grok here: [https://x.ai]

### Meta AI
Meta AI is Meta’s suite of generative AI tools embedded across Facebook, Instagram, WhatsApp, and Messenger. It offers multimodal capabilities including text, image, and video generation, and supports real-time chat, creative content generation, and productivity tasks. Meta AI is powered by the Llama 4 model and is accessible via Meta’s apps and a standalone assistant. Access Meta AI here: [https://www.meta.ai]

### Copilot
Copilot is Microsoft’s AI assistant integrated across tools like Word, Excel, PowerPoint, Outlook, and Teams. It leverages large language models to help users draft content, analyze data, summarize meetings, and automate workflows. In Excel, it can generate formulas, create charts, and explain data trends. In Word and PowerPoint, it assists with writing, editing, and designing presentations. Copilot is deeply embedded in Microsoft 365, enhancing productivity through natural language commands. Access Copilot here: [https://copilot.microsoft.com]

### Gemini
Gemini is Google’s family of multimodal AI models integrated into Google Workspace and available via the Gemini web app. It assists users in drafting, summarizing, brainstorming, analyzing documents, and generating code. Within Docs, Gmail, and Sheets, Gemini enhances productivity by offering smart suggestions, data insights, and content generation. It also supports image understanding and code interpretation through its advanced model versions. Access Gemini here: [https://gemini.google.com]

### NotebookLM
NotebookLM is a personalized AI research assistant from Google designed to help users work with their own documents. It can summarize large texts, generate FAQs, suggest outlines, timelines, and even podcast scripts. Unlike general-purpose chatbots, NotebookLM focuses on grounded responses based solely on the sources provided by the user, making it ideal for academic, legal, and research-based tasks.
Access NotebookLM here: [https://notebooklm.google]

### Napkin
Napkin is a visual storytelling AI tool that transforms plain text into professional diagrams, infographics, and flowcharts. It is ideal for business presentations, educational content, and social media visuals. Users can customize visuals with icons, connectors, and themes, and export them in formats like PNG, PDF, and SVG. Access Napkin here: [https://www.napkin.ai]

### Gamma
Gamma is an AI-powered content creation platform for building presentations, documents, and websites. It uses natural language prompts to generate scrollable, interactive content with modern design. Gamma is ideal for pitch decks, proposals, and educational materials, and supports real-time collaboration and publishing. Access Gamma here: [https://gamma.app]

### AI Studio
Google AI Studio is a development platform for building with Gemini, Google’s multimodal AI models. It supports chat, code execution, file analysis, and video generation. Designed for both beginners and developers, AI Studio enables rapid prototyping and integration of AI into applications with a user-friendly interface. Access AI Studio here: [https://aistudio.google.com]

### SciSpace
SciSpace is an AI research assistant tailored for academic reading, comprehension, and exploration of scientific literature. It allows users to upload PDFs of scholarly articles and interact with them through a chat-based interface that explains complex concepts, defines technical terms, and summarizes content section-by-section. SciSpace is particularly strong in STEM fields and integrates citation tracing, question generation, and concept mapping. It is ideal for literature review, paper comprehension, and academic study.
Access SciSpace here: [https://scispace.com/]

---

## 3. Applications of Generative AI for Entrepreneurs  

Generative AI (GenAI) opens new opportunities for startups by lowering costs, speeding up creativity, and enabling small teams to produce high-quality outputs. Here are some of the most common applications relevant to entrepreneurs:  

### 1. Text and Content Creation  
- **What it does:** Write blog posts, product descriptions, social media captions, or even full business reports.  
- **Why it matters:** Saves time, improves consistency, and helps create a strong online presence.  

### 2. Copywriting and Marketing Material  
- **What it does:** Generates ads, landing page text, email campaigns, and personalized customer messages.  
- **Why it matters:** Entrepreneurs can quickly test different messages and find what resonates with their audience.  

### 3. Image and Art Generation  
- **What it does:** Create logos, product designs, illustrations, and concept art.  
- **Why it matters:** Startups can create professional visuals without hiring expensive designers in the early stages.  

### 4. Video Generation and Editing  
- **What it does:** Generate short promotional videos, explainer animations, or even realistic avatars for pitches.  
- **Why it matters:** Video is a powerful communication tool, and GenAI reduces production time and costs.  

### 5. Music and Audio Creation  
- **What it does:** Compose background music, generate jingles, or create soundtracks for videos and ads.  
- **Why it matters:** Entrepreneurs can add professional audio branding to their product without needing a composer.  

### 6. Speech and Voice Cloning  
- **What it does:** Generate natural-sounding voiceovers for videos, podcasts, or apps.  
- **Why it matters:** Provides multilingual and cost-effective voice solutions for marketing and customer support.  

### 7. Code Generation and Software Prototyping  
- **What it does:** Helps write, debug, or improve code; can also create quick prototypes of apps or websites.  
- **Why it matters:** Reduces development time, especially for non-technical founders.  

### 8. Data Analysis and Insights  
- **What it does:** Summarizes trends, visualizes datasets, and extracts insights from customer feedback or market data.  
- **Why it matters:** Entrepreneurs can make data-driven decisions without needing a large analytics team.  

---

## 4. Homework Assignment – Exploring GenAI Tools  

**Objective:** Discover real-world GenAI tools and their entrepreneurial applications.  

**Instructions for Teams:**  
1. Form your startup teams (2–3 members).  
2. Choose one application area from the list above.  
3. Research **existing GenAI tools** in each area (e.g., Jasper for text, MidJourney for images, Runway for video, Soundraw for music, GitHub Copilot for code).  
4. Prepare a short presentation (5–7 minutes) that includes:  
   - The **type of application** (e.g., video generation).  
   - The **tool name(s)** and what they do.  
   - At least one **example use case** relevant to startups.  
   - A reflection: *How could your startup use this tool?*  

**Deliverable:** In-class presentation next session, with slides or a live demo if possible.  

---

## 3. Ethical Considerations and Wrap-Up Reflections

- Responsible use: data privacy, bias, hallucinations, transparency
- Examples of misuse and how to avoid them
- When *not* to use AI or when to rely on human judgment
- What did you learn about AI tools that surprised you?
- Which AI tasks are you most comfortable with?
- What task in your work would you most like to streamline with AI?
- What did you learn about prompt engineering?

