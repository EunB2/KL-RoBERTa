# KL-RoBERTa

**KL-RoBERTa** is a Korean legal language model designed for Korean legal natural language understanding tasks.  
It aims to better capture legal terminology, long-form legal context, and domain-specific linguistic patterns in Korean legal texts.

KL-RoBERTa is built on **[klue/roberta-base](https://huggingface.co/klue/roberta-base)**, an encoder-based Korean RoBERTa model, and retains the original architecture and tokenizer.

The model was further pretrained using **continued pretraining** on a large-scale Korean legal corpus comprising **approximately 420 million tokens**.

The pretraining data includes diverse types of Korean legal texts:
- **Legal news articles** covering legislation, court rulings, and legal policy issues  
- **Legal books and reference materials** describing legal concepts, doctrines, and statutory interpretations  
- **Court precedents**, including full-text judicial decisions written in formal legal language  

Pretraining was conducted with the **Masked Language Modeling (MLM)** objective.  
To support long and complex legal documents, the maximum input sequence length was extended to **4,096 tokens**.
