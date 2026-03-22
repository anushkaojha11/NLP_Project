# Multimodal and Agentic RAG for Grade 10 Mathematics Tutoring

## Overview
This project aims to develop a curriculum-aligned mathematical tutoring system using Retrieval-Augmented Generation (RAG). The system is designed for Grade 10 mathematics based on the Nepalese curriculum and focuses on generating structured, step-by-step solutions for exam-oriented problem solving.

The proposed approach extends traditional RAG systems by incorporating multimodal capabilities and agentic workflows to improve both accuracy and reliability.

---

## Key Ideas

### 🔹 Retrieval-Augmented Generation (RAG)
The system retrieves relevant worked examples from the textbook and uses them as context for generating solutions, ensuring that outputs are grounded in curriculum-specific knowledge.

### 🔹 Multimodal Learning
The system supports both text and diagram-based problems by:
- Extracting and processing images from textbooks  
- Generating structured descriptions of diagrams  
- Using joint text-image representations for retrieval  

### 🔹 Agentic Workflows
We incorporate advanced RAG workflows using LangGraph:
- **Self-RAG**: Enables self-reflection and iterative correction  
- **CRAG (Corrective RAG)**: Improves retrieval quality through relevance evaluation  
- **Adaptive RAG**: Selects optimal strategies based on question complexity  

---

## Dataset
The dataset is derived from the Nepal Grade 10 Mathematics textbook and includes:
- Chapter-wise textual content  
- Worked examples with step-by-step solutions  
- Exercise problems  
- Diagram-based questions (multimodal component)  

---

## System Architecture
The system consists of four main components:
1. **Input Processing** – Handles both text and image inputs (via OCR for user queries)  
2. **Multimodal Retrieval** – Retrieves relevant examples using combined embeddings  
3. **Agentic Workflow Layer** – Implements Self-RAG, CRAG, and Adaptive RAG  
4. **Generation Layer** – Produces structured solutions using large language models  

---

## Experiments (Planned)
The project will evaluate:
- Baseline LLM vs RAG performance  
- Retrieval and prompting strategies  
- Impact of multimodal inputs on geometry problems  
- Effectiveness of agentic workflows on correctness and reliability  

---

## Current Status
This is the **initial version of the repository**.

The project is currently in the design and proposal phase. Implementation, experiments, and results will be added progressively.

---

## Future Work
The repository will be continuously updated to include:
- Implementation details  
- Model configurations  
- Experimental results and analysis  
- Usage instructions and reproducibility steps  

---

## Note
This README will be **progressively expanded** as the project develops.