# Leveraging-Large-Language-Models-for-Automated-Code-Understanding-and-Comment-Generation
In this project, I tested CodeT5 and LLaMA 3.2 to see how good they are at generating useful comments for code snippets — no fine-tuning, just pure zero-shot and few-shot prompts.
🧪 Datasets
- CodeSearchNet (Java + Python)
- CoNaLa (Python)
⚙️ Models
- CodeTrans (Java + Python, based on CodeT5)
- LLaMA 3.2 (zero-shot, one-shot, two-shot)
📏 Metrics
- BLEU-2, ROUGE-1/2/L
- METEOR
- Cosine Similarity (for semantic closeness)
🔍 What I found:
- CodeT5 crushed zero-shot tasks, especially on Java
- LLaMA 3.2 got way better when I gave it examples (few-shot)
- Python results were stronger overall (probably 'cause it's cleaner and more common in pretraining)
- Shorter outputs had better precision; longer ones = more fluff, not necessarily more meaning
