# LFED: Literary Fiction Evaluation Dataset for Large Language Models

## Abstract

The rapid evolution of large language models (LLMs) has created a need for comprehensive assessments of their performance across various dimensions. LFED is a dataset designed to evaluate the capabilities of LLMs in understanding and reasoning over long literary fiction texts. This dataset includes 95 literary novels, originally written in Chinese or translated into Chinese, covering a wide range of topics from different centuries. We developed a taxonomy of 8 question categories to guide the creation of 1,304 questions. Our experiments with various state-of-the-art LLMs demonstrate significant challenges in addressing questions related to literary fictions, with ChatGPT achieving an accuracy of only 57.08% in a zero-shot setting.

## Introduction

Numerous datasets have been developed for machine reading comprehension tasks. However, these passage-based datasets are inadequate for evaluating the advanced capabilities of LLMs. LFED addresses this gap by providing a challenging dataset with long documents that require complex reasoning, such as character relationship reasoning and counterfactual reasoning.

## Dataset Overview

LFED consists of a diverse collection of 95 literary fictions, either originally written in Chinese or translated into Chinese. The dataset includes 1,304 questions categorized into 8 types:

1. Character Relationships
2. Characterization
3. Literary Style
4. Role Behavior
5. Event Relations
6. Fiction Plot
7. Background Topic
8. Counterfactual Reasoning

### Question Taxonomy

The questions are designed to cover the core aspects of literary fictions, such as content, character relationships, storyline, writing techniques, and thematic values. This systematic approach ensures the questions are comprehensive and challenging.

## Data Collection Process

The dataset was collected through a rigorous crowdsourcing process with multiple quality control steps. The novels were selected based on their complex narratives, character development, profound themes, and rich linguistic expressions. We manually checked each novel to ensure it met specific criteria, including literary value, genre diversity, and alignment with contemporary human values.

### Annotation Pipeline

1. **Collecting Literary Fictions**: Novels were selected based on recommendations from Douban, a Chinese community site for book and movie reviews.
2. **Creating Questions**: Crowdsourced workers read the novels and created questions based on a defined taxonomy.
3. **Annotating Questions**: Questions were annotated and reviewed to ensure quality.
4. **Experts Checking**: Experts reviewed the questions for accuracy.
5. **Penultimate Dataset**: Agreement checks were conducted to ensure consistency.
6. **Final Dataset**: The dataset was filtered and finalized for public release.

## Usage

LFED can serve as a comprehensive and challenging benchmark for assessing the capabilities of LLMs in fact understanding, logical reasoning, contextual comprehension, common-sense reasoning, and value judgment.

## Evaluation

We evaluated several state-of-the-art LLMs on LFED under zero- and few-shot settings. The results indicate that long literary fiction comprehension poses significant challenges for these models, with ChatGPT achieving an accuracy of 57.08% in a zero-shot setting.

## Dataset Availability

The LFED dataset is publicly available at https://github.com/tjunlp-lab/LFED.git.

## Contact

For any queries or contributions, please contact the corresponding author at linhaoyu@tju.edu.cn.