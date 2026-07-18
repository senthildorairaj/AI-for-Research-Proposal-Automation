## README: AI for Research Proposal Automation

### Project Overview
This project developed a comprehensive, AI-assisted system designed to automate and optimize the creation of NIH research proposals. Beginning with raw scientific papers and culminating in a fully evaluated, NOFO-aligned proposal, the workflow seamlessly integrates document ingestion, innovative idea generation, detailed proposal drafting, and an automated evaluation process utilizing LLM-as-Judge methodologies.

### Business Problem
Organizations and researchers frequently face challenges in aligning vast archives of prior work with specific funding opportunities, extracting relevant expertise, ideating novel research proposals, and generating high-quality grant text under tight deadlines. This system addresses these pain points by streamlining the proposal development process, making it more efficient, consistent, and less prone to missed opportunities.

### Key Features
- **Topic Extraction:** Automatically identifies the primary funding topic from NOFO documents.
- **Research Paper Relevance Assessment:** Filters and ranks research papers using semantic search and FAISS vector embeddings based on NOFO topic.
- **Proposal Ideation:** Generates 5 distinct, fundable research ideas, each with a title, description, citation, NOFO alignment, and file path of the supporting paper.
- **Proposal Blueprint Preparation:** Crafts a complete research proposal following a structured template, leveraging selected ideas and referenced research papers.
- **Proposal Evaluation (LLM-as-Judge):** Assesses the generated proposal against NIH criteria (Innovation, Significance, Approach, Investigator Expertise) providing scores, justifications, strengths, weaknesses, and recommendations in JSON format.

### Recommendations for Future Enhancements
1.  **Add Multi-Paper Idea Synthesis:** Enhance the LLM's capability to combine insights from multiple related papers, fostering richer and more innovative proposal ideas.
2.  **Add Multi-Model Evaluation:** Integrate evaluation using multiple LLMs (e.g., GPT-4, Claude, Llama 3) to compute consensus scores, variance, and confidence intervals, thereby reducing single-model bias.
3.  **Add a UI or Dashboard:** Develop a user-friendly interface (e.g., Streamlit or Gradio) for seamless interaction, allowing users to upload papers, select ideas, generate proposals, view evaluations, and download PDFs.

### Resources
**Note:** Due to space constraints, some of the larger research files have been removed from this repository. However, the core logic and pipeline remain intact, and can be used with your own datasets.