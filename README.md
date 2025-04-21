# Leveraging-Large-Language-Models-for-Automated-Code-Understanding-and-Comment-Generation

This project, by Mozhan Saeedidehshali, explores the use of LLMs—specifically CodeT5 and LLaMA 3.2—for generating documentation and understanding isolated code snippets in both zero-shot and few-shot learning settings.
The models were tested on Java and Python code from the CodeSearchNet and CoNaLa datasets. The goal was to assess the models' ability to produce clear, accurate code comments under different prompting strategies, using both task-specific and general-purpose LLMs.
Datasets Used:
- CodeSearchNet (Java subset)
- CodeSearchNet (Python subset)
- CoNaLa (Python)
Models Tested:
- CodeTrans (Java)
- CodeTrans (Python)
- LLaMA 3.2 (Zero-shot, One-shot, Two-shot)
Evaluation Metrics:
- BLEU-2
- ROUGE-1, ROUGE-2, ROUGE-L
- METEOR
- Cosine Similarity (semantic similarity)
Key Findings:
- CodeT5 outperformed LLaMA 3.2 in zero-shot tasks, especially on Java.
- LLaMA 3.2 significantly improved with one-shot and two-shot prompts, especially on Python.
- Few-shot learning was most effective when dataset structure matched the documentation task.
- Python code performed better than Java, likely due to simpler syntax and higher model representation.
