# Spanish-BERT-Q-A
This model is a fine-tuned on SQuAD-es-v2.0 and distilled version of BETO for Q&amp;A.
This model was fine-tuned on the same dataset but using distillation during the process as mentioned above (and one more train epoch).

The teacher model for the distillation was bert-base-multilingual-cased. It is the same teacher used for distilbert-base-multilingual-cased AKA DistilmBERT (on average is twice as fast as mBERT-base).

