This repository provides the prompt templates used in the paper entitled "Improving Explainable Recommender Systems with Veracity-Based Human Feedback."

We used three types of prompts in different stages of the study, each tailored to a specific purpose:

1. **Entity Extraction**  
To address the potential incompleteness of the existing knowledge graph (used as input to the backbone recommendation algorithm), we employed prompts to extract relevant entities using a large language model (LLM). 'prompt_entity_extraction.txt' was used during the knowledge graph augmentation phase.

2. **Explanation Generation**  
The backbone algorithm produces a recommendation path that connects a target user to an item. We used prompts to convert these paths into natural language explanations via LLM. 'prompt_explanation_generation.txt' was applied in the explanation generation stage.

3. **Pseudo-User Study**  
To conduct a preliminary evaluation prior to real-user testing, we generated diverse user personas with LLM prompts. 'prompt_pseudo_user_study.txt' was used during the pseudo-user study.

All prompt files are provided in plain text format for reproducibility.

> This repository is intended to support anonymous review. Author and affiliation information will be added after acceptance.
