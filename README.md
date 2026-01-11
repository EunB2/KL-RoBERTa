# KL-RoBERTa

**KL-RoBERTa** is a Korean legal language model designed for Korean legal natural language understanding tasks.  
It aims to better capture legal terminology, long-form legal context, and domain-specific linguistic patterns in Korean legal texts.

KL-RoBERTa is built on **[klue/roberta-base](https://huggingface.co/klue/roberta-base)**, an encoder-based Korean RoBERTa model, and retains the original architecture and tokenizer.

The model was further pretrained using **continued pretraining (domain-adaptive pretraining)** on a large-scale Korean legal corpus, including legal news articles, legal books, and court precedents.  
Pretraining was conducted with the **Masked Language Modeling (MLM)** objective, and the maximum input length was extended to **4,096 tokens** to support long legal documents.
