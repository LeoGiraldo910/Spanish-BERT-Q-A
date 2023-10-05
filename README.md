# Spanish-BERT-Q-A
This model is a fine-tuned on SQuAD-es-v2.0 and distilled version of BETO for Q&amp;A.
This model was fine-tuned on the same dataset but using distillation during the process as mentioned above (and one more train epoch).

The teacher model for the distillation was bert-base-multilingual-cased. It is the same teacher used for distilbert-base-multilingual-cased AKA DistilmBERT (on average is twice as fast as mBERT-base).

Model Description: The DistilBERT model was proposed in the blog post Smaller, faster, cheaper, lighter: Introducing DistilBERT, adistilled version of BERT, and the paper DistilBERT, adistilled version of BERT: smaller, faster, cheaper and lighter. DistilBERT is a small, fast, cheap and light Transformer model trained by distilling BERT base. It has 40% less parameters than bert-base-uncased, runs 60% faster while preserving over 95% of BERT's performances as measured on the GLUE language understanding benchmark.

