<h1 align="center">LLM Landscape Research</h1>
<p align="center"><em>An exploration of the large language model ecosystem – comparing leading models, training methods, and terminology.</em></p>

---

## Major LLM Models and What Makes Them Special

---

### 1. ChatGPT (OpenAI)
**Users:** ~800 million weekly active users, ~2.5 billion messages per day  
**Developer:** OpenAI (Microsoft partner)

**Key features:**
- Strong general reasoning and coding ability  
- Fine-tuned for conversational dialogue  
- Integrated tools (image understanding, data analysis, web browsing)  
- Multimodal input  

**Special:**  
Proprietary and closed-source — the model’s architecture, weights, and training data are not publicly available.

**My opinion:**  
It’s the model I use every day. I find the interface intuitive and the performance consistent across both creative and technical tasks.

---

### 2. Claude (Anthropic)
**Users:** ~18.9 million monthly users (769.6 million app downloads as of Jan 2025)  
**Developer:** Anthropic  

**Key features:**
- 200,000-token context window (can process entire books or codebases)  
- Constitutional AI (CAI) alignment method  
- Natural, human-like dialogue style  
- Strong at complex reasoning and coding tasks  

**Why it matters:**  
Claude’s CAI approach is fundamentally different from ChatGPT’s RLHF – it follows explicit ethical principles rather than learning solely from human feedback.

**My opinion:**  
The extended context window is game-changing for analysing long documents or large codebases.

---

### 3. Google Gemini
**Users:** Over 230 million (as of early 2025)  
**Developer:** Google DeepMind  

**Key features:**
- Native multimodal design (text, image, audio, video, and code)  
- Deep integration with Google Workspace (Docs, Gmail, Maps, YouTube)  
- Context window up to 2 million tokens (experimental)  
- Real-time web data access via Google Search  
- Gemini Nano runs locally on Android devices  

**Why it matters:**  
Gemini was built as a multimodal model from the start. Real-time search integration makes it highly accurate and reduces hallucinations.

**My opinion:**  
Ideal for productivity and research within the Google ecosystem.

---

### 4. LLaMA (Meta)
**Developer:** Meta  
**Versions:** LLaMA 3.3 (70B and 405B parameters)

**Key features:**
- Fully open-source (weights and architecture available)  
- Can be run locally on personal hardware  
- Multiple model sizes (8B, 70B, 405B)  
- Multilingual (100+ languages)  
- Free to use, with minimal restrictions  

**Special:**  
Thousands of community fine-tuned versions exist for specific tasks.

**Why it matters:**  
LLaMA made state-of-the-art AI accessible to researchers, students, and independent developers.

**My opinion:**  
A breakthrough for AI accessibility and innovation — perfect for learning and experimentation.

---

### 5. Mistral
**Origin:** France  
**Funding:** $1 billion+  
**Founded by:** Former Meta and DeepMind researchers  

**Key features:**
- Efficient, high-performing smaller models  
- Mixture of Experts (MoE) architecture  
- Strong European privacy compliance  
- Open-source and commercial offerings  
- “La Plateforme” API for integration  

**Why it matters:**  
Mistral shows that efficiency and transparency can rival sheer scale. It supports European AI sovereignty and privacy-first principles.

**My opinion:**  
A strong middle ground between open-source flexibility and enterprise-grade reliability.

---

### 6. Grok (xAI)
**Developer:** xAI (Elon Musk)  
**Launched:** Late 2023  

**Key features:**
- Real-time data from X (Twitter)  
- Conversational, humorous tone  
- Image generation built-in  
- Less restrictive moderation  

**Special:**  
Exclusive to X Premium+ subscribers.  

**Why it matters:**  
Integrates real-time data directly into a model — rare in the current LLM landscape.  

**My opinion:**  
An interesting experiment in social integration, though limited in scope and reliability.

---

### 7. Perplexity AI
**Users:** 10+ million monthly  
**Founded:** 2022  

**Key features:**
- Built as an “answer engine” rather than a chatbot  
- Real-time search and citation system  
- “Copilot” mode for iterative queries  
- Academic and research-focused  

**Why it matters:**  
By citing every answer, Perplexity directly addresses the issue of hallucinations and misinformation.

**My opinion:**  
Excellent for research tasks and fact-checking, less flexible for creative use.

---

### 8. DeepSeek AI
**Origin:** China (launched 2023)  
**Flagship model:** DeepSeek-V3 (released Jan 2025)

**Key features:**
- Mixture of Experts (MoE) architecture  
- Trained efficiently using lower-cost hardware (~$6 million total)  
- Open-source with strong mathematical and coding performance  
- Innovative multi-head latent attention mechanism  

**Why it matters:**  
DeepSeek proves efficiency and design can rival vast compute budgets, reshaping global AI competition.

**My opinion:**  
An inspiring example of innovation over scale — makes high-quality AI research more accessible worldwide.

---

## Key Terminology in Large Language Models

Below is a structured list of key terms drawn from the research document.  
(Definitions are not included here)

---

### Core LLM Concepts
- Transformer Architecture  
- Tokens / Tokenization  
- Parameters  
- Training Data  
- Pre-Training  
- Fine-Tuning  
- Instruction Fine-Tuning  
- Domain Fine-Tuning  
- Safety Fine-Tuning  
- Reinforcement Learning from Human Feedback (RLHF)

---

### Model Performance and Capabilities
- Context Window  
- Knowledge Cut-off  
- Emergent Behaviour  
- Zero-Shot Learning  
- Few-Shot Learning  
- Hallucinations

---

### Interaction and Alignment
- Prompt  
- Prompt Engineering  
- Chain-of-Thought (CoT)  
- Temperature  
- Alignment  
- Constitutional AI  
- Safety Layers / Guardrails

---

### Technical and Industry Terms
- Open-Source vs Closed-Source  
- Model Weights  
- Retrieval-Augmented Generation (RAG)  
- Latency  
- Throughput

---

### Social and Ethical Aspects
- Hallucination Rate  
- Slop  
- Prompt Injection  
- Model Distillation  
- Fine-Grained Evaluation

---

## Resources I Found Particularly Useful

### "[1hr Talk] Intro to Large Language Models" — Andrej Karpathy  
**Why useful:** Explains the inner workings of LLMs, from parameters to prediction.  
**Key takeaway:** LLMs are measurable but not fully interpretable — we can adjust performance, but not fully understand how knowledge is encoded.  
**Most engaging insight:** How 10 TB of internet text is compressed into 140 GB of parameters using 6,000 GPUs.

---

### "How to Choose Large Language Models: A Developer’s Guide to LLMs"  
**Why useful:** Clear overview of when to use which model.  
**Key takeaway:** Each model excels in different areas — creativity, cost, speed, or accuracy.




