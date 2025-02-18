We built a Named Entity Recognition (NER) model using XLM-RoBERTa to extract key entities like names, organizations, and locations from text. Instead of using RobertaForTokenClassification, we implemented a custom model with XLM-RoBERTa as a backbone, manually extracting logits for classification. We trained it on English and Persian datasets using Hugging Face Transformers, optimizing token alignment and processing efficiency.
</br>Features
</br>✅ Custom Model Implementation – We used XLM-RoBERTa as a backbone instead of RobertaForTokenClassification and manually extracted logits.
</br>✅ Hugging Face Integration – We leveraged Hugging Face Transformers for training and inference.
</br>✅ Optimized Token Alignment – We improved entity mapping with subword tokenization.

