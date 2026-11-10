# DSC 180A Methodology Assignment 4

**Name:** Aarushi Jain  
**Email:** aaj013@ucsd.edu  
**Section:** D28 
**Mentor:** Ryan Lingo (Honda Research Institute)

**1. What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic has been how different memory systems help AI agents keep context over time. Comparing a structured LLM-maintained wiki with standard retrieval augmented generation (RAG) showed me that how knowledge is stored and organized can matter as much as the model itself.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
I would like to study whether an LLM wiki can stay accurate as new data keeps arriving. Using NHTSA recalls and complaints that are released over time, I would update the wiki incrementally and measure whether its answers drift, contradict older entries, or miss new safety issues compared to a RAG system rebuilt from scratch.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**  
I would build a stronger evaluation set. Instead of a small set of hand-written questions, I would create a larger labeled benchmark of questions about specific vehicles, components, and recall dates, so we can measure accuracy and hallucination rates for both systems more reliably.

**4. What other techniques would you be interested in using in your project?**  
I am interested in knowledge graphs to link vehicles, components, and recalls, hybrid search that combines keyword and embedding retrieval, rerankers to improve which documents get passed to the model, and using an LLM as a judge to score answers at scale.
