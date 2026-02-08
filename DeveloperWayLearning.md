Here is your final, definitive **Senior Developer’s AI Master Plan**.

This curriculum is optimized for a 10-year veteran who learns by coding. It skips the academic fluff, focuses on building, and targets the modern 2026 stack (LLMs, RAG, MCP).

### **The Strategy: Top-Down Engineering**

* **Phase 1:** Drive the car (Use libraries to build apps).
* **Phase 2:** Build the engine (Code the math from scratch).
* **Phase 3:** Build the roads (Connect AI to real-world data).

---

### **Phase 1: The "Hello World" (Weeks 1-4)**

**Goal:** Build and deploy a computer vision model and a text classifier.
**Time Commitment:** ~10 hours/week.

* **Course:** **[Practical Deep Learning for Coders (Fast.ai)](https://course.fast.ai/)**
* **Action Plan:**
1. **Watch Lessons 1-3:** Focus on Image Classification.
2. **Watch Lesson 4:** Focus on NLP (Natural Language Processing) and Hugging Face.
3. **The "Hello World" Task:** Open a Google Colab notebook and train a model to classify "Hot Dog vs. Not Hot Dog" using your own images.


* **Key Concept:** `fine_tune()` — Taking a model Google spent millions on and adapting it to your data in 30 seconds.

---

### **Phase 2: The "Internals" Speed Run (Weeks 5-8)**

**Goal:** Build GPT (Generative Pre-trained Transformer) from scratch in raw Python.
**Time Commitment:** ~8 hours/week (Heavy coding).

* **Course:** **[Neural Networks: Zero to Hero (Andrej Karpathy)](https://karpathy.ai/zero-to-hero.html)**
* **The "Speed Run" Playlist (Watch ONLY these):**
1. **Video 1 (Micrograd):** *Building micrograd.* (The "Hello World" of backpropagation).
* *Rule:* You must type every line of code he types.


2. **Video 2 (Makemore):** *The Bigram Language Model.* (Your first text generator).
3. **Video 7 (GPT):** *Let's build GPT: from scratch.* (The architecture behind ChatGPT).
4. **Bonus:** **[State of GPT (Microsoft Build)](https://www.youtube.com/watch?v=bZQun8Y4L2A)** (High-level system design overview).



---

### **Phase 3: The "Systems" (Weeks 9-10)**

**Goal:** Build an app that uses AI to answer questions about your own private data (PDFs/Code).
**Time Commitment:** ~5 hours/week.

* **Topic A: RAG (Retrieval Augmented Generation)**
* **Course:** **[DeepLearning.AI: Retrieval Augmented Generation (RAG)](https://www.google.com/search?q=https://www.deeplearning.ai/short-courses/retrieval-augmented-generation-rag/)**
* **Goal:** Learn how to chunk text, create embeddings, and store them in a Vector Database so LLMs don't hallucinate.


* **Topic B: MCP (Model Context Protocol)**
* **Resource:** **[Anthropic MCP Quickstart](https://modelcontextprotocol.io/introduction)**
* **Goal:** Build a simple local server that lets an AI agent read your file system or database.



---

### **Summary Checklist**

| Phase | Resource | Outcome |
| --- | --- | --- |
| **1** | [Fast.ai Lesson 1](https://course.fast.ai/) | **Deployed Image Classifier** (working app). |
| **2** | [Karpathy Video 1](https://karpathy.ai/zero-to-hero.html) | **Autograd Engine** (math in pure Python). |
| **3** | [Karpathy Video 7](https://karpathy.ai/zero-to-hero.html) | **GPT Implementation** (Transformer from scratch). |
| **4** | [DeepLearning.AI](https://www.deeplearning.ai/short-courses/) | **RAG Chatbot** (Talk to your PDFs). |

**Final Advice:**
Start **Fast.ai Lesson 1** tonight. Don't install anything locally yet—just use **Google Colab** (free GPU in the browser) to get your first win.

Good luck. You have a fun 3 months ahead of you.
