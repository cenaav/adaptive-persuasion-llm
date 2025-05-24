# Adaptive Persuasion in Conversational AI

[![Cite This Repository](https://img.shields.io/badge/Cite-this%20repository-blue.svg?style=flat-square)](https://github.com/cenaav/adaptive-persuasion-llm#cite-this-repository)
[![DOI](https://zenodo.org/badge/DOI/10.1109/ICWR59012.2025.11006192.svg)](https://doi.org/10.1109/ICWR59012.2025.11006192)

This repository contains code and resources associated with the paper:

**Adaptive Persuasion in Conversational AI: An LLM-Driven Framework for Dynamic Strategy Switching via Personality and Sentiment Analysis**  
📌 *Published in: 2025 11th International Conference on Web Research (ICWR)*  
🔗 [IEEE Xplore Link](https://ieeexplore.ieee.org/document/11006192)

---

## 📄 Abstract

Recent advances in persuasive communication and conversational AI have driven the development of adaptive frameworks that integrate dynamic strategy adjustment within large language model architectures. In this study, we introduce a novel framework that effectively integrates real-time sentiment analysis with comprehensive personality profiling based on the Big Five model to enable adaptive strategy switching during multi-turn dialogues.

Our methodology also leverages a reinforcement learning-inspired weight adaptation mechanism that continuously readjusts the relative influence of stable personality traits and transient emotional states, thereby optimizing the selection of persuasive techniques.

Furthermore, by incorporating a Retrieval-Augmented Generation (RAG) paradigm alongside the LLaMA model, the proposed framework produces contextually coherent and individually tailored responses that draw upon historical interaction data and strategic knowledge repositories.

Experimental evaluations reveal that our adaptive system significantly enhances persuasive efficacy and user engagement, underscoring its potential to advance the state-of-the-art in personalized conversational agents.

---

## 🔍 Project Overview

This repository implements a **conversational AI system** that adapts its persuasive strategies during dialogues. Key components include:

- **Big Five Personality Profiling**: Represents users via a five-dimensional vector (Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism).
- **Real-Time Sentiment Analysis**: Classifies user utterances as positive, neutral, or negative to guide response tone.
- **Dynamic Strategy Switching**: Selects persuasive strategies (e.g., emotional, logical, credibility-based, informative) using a weighted formula, updated via reinforcement learning-inspired logic.
- **Context-Aware Responses**: Integrates RAG with LLMs to produce coherent, tailored replies based on historical data and strategic knowledge.

This framework is ideal for applications in customer engagement, marketing, education, and more, enhancing both persuasion and user interaction.

---

## 👥 Contributors

- [Mansoureh Motahari Nezhad](https://github.com/mansourehmotahari)  
- [Maysam Avakh Kisomi](https://github.com/cenaav)  
- [Fatemeh Gholinezhad](https://github.com/USERNAME3)

---

## 🔑 Keywords

#ConversationalAI #PersuasiveAI #SentimentAnalysis #PersonalityProfiling #LLM #RAG #NaturalLanguageProcessing #AIResearch #ICWR2025 #AdaptiveChatbot

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/personalized-persuasive-chatbot.git
cd personalized-persuasive-chatbot
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook
```bash
jupyter notebook notebooks/Sentiment_Analysis_BERT_LLM_Groq.ipynb
```
Execute the notebook cells sequentially to:
- Preprocess data
- Conduct sentiment and personality analysis
- Simulate strategy switching
- Generate responses using the LLM

---

## 🛠️ Technical Details

| Component            | Details                                              |
|---------------------|------------------------------------------------------|
| **Notebook**        | `Sentiment_Analysis_BERT_LLM_Groq.ipynb`            |
| **Sentiment Model** | `twitter-roberta-base-sentiment` (HuggingFace)      |
| **Language Model**  | `llama-3.1-8b-instant` (via Groq API)              |
| **Dataset**         | PersuasionForGood                                  |
| **Strategies**      | Emotional, Logical, Credibility, Informative, etc.  |

### Notebook Breakdown
1. **Install Dependencies**: Sets up libraries like `langchain`, `sentence-transformers`, and `langchain-groq`.
2. **Data Preprocessing**: Loads and prepares sample text and persuasion datasets (e.g., via `gdown`).
3. **Sentiment Analysis**: Employs BERT/RoBERTa models for multilingual sentiment classification.
4. **Personality Profiling**: Builds user profiles based on Big Five traits.
5. **Strategy Selection**: Uses a weighted formula to choose persuasive strategies, updated dynamically.
6. **Response Generation**: Leverages Groq’s LLM API for contextually relevant replies.

---

## 📊 Performance Results

The adaptive chatbot significantly outperforms static and dynamic baselines:

| Metric              | Static Strategy | Dynamic Strategy | Adaptive Strategy |
|---------------------|-----------------|------------------|-------------------|
| **Dialogue Turns**  | 9 ± 1.8         | 12.7 ± 2.4       | 14.5 ± 3.9        |
| **Donation (USD)**  | 0.5             | 17.5             | 20.0              |
| **Empathy Score**   | 1.5             | 3.2              | 3.2               |

These results highlight the system’s superior engagement and persuasive capabilities.

---

## 📂 Repository Structure

```
├── README.md
├── notebooks/
│   └── Sentiment_Analysis_BERT_LLM_Groq.ipynb
├── paper/
│   └── [Paper-related files]
├── assets/
│   └── [Images, diagrams, etc.]
├── requirements.txt
```

---

## 📚 Citation

If you use this work, please cite our paper:

```bibtex
@inproceedings{motahari2025personalized,
  title={Personalized Persuasive Chatbot: Dynamic Strategy Adaptation Using LLMs, Sentiment, and Personality Analysis},
  author={Motahari Nezhad, Mansoureh and Avakh Kisomi, Maysam and Gholinezhad, Fatemeh},
  booktitle={2025 11th International Conference on Web Research (ICWR)},
  year={2025},
  organization={IEEE},
  doi={10.1109/ICWR59012.2025.11006192}
}
```

---

## 📜 License

This project is licensed under the **Apache-2.0 License**.

---

## 📧 Contact Us

For inquiries or collaboration, contact:
- **Mansoureh Motahari Nezhad**: mansoureh_motahari@alumni.iust.ac.ir / motahari.mansoureh@gmail.com
- **Maysam Avakh Kisomi**: sinaavakh@gmail.com
- **Fatemeh Gholinezhad**: f.gholinezhad@gmail.com

---

## 🌟 Why This Project?

This repository offers a cutting-edge solution for building **adaptive, persuasive conversational AI**. Whether you’re a researcher, developer, or AI enthusiast, explore this codebase to:
- Dive into LLM and RAG integration
- Experiment with sentiment and personality-driven AI
- Develop your own intelligent chatbot

---
