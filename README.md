# resources

## Word level token embedding
tokenclassification: https://huggingface.co/transformers/task_summary.html \
rasa: https://rasa.com/docs/rasa/nlu-training-data/ \
Vietnamese ner but multilingual model: https://github.com/dat821168/bert_vn_ner

check fine tuning ner for other language
https://github.com/dbmdz/berts/issues/24 ner dbmdz

https://gist.github.com/stefan-it/feb6c35bde049b2c19d8dda06fa0a465

ner chinese

in summary: fine tune phobert using vlsp2016
vlsp need to be modified
use run_ner.py in transformers


check legacy sample codes
https://github.com/huggingface/transformers/tree/master/examples/pytorch/token-classification


ner with lstm: https://github.com/pth1993/vie-ner-lstm

ner spacy
https://github.com/amrrs/custom-ner-with-spacy/blob/main/pvr_custom_ner_training2.ipynb
https://www.youtube.com/watch?v=mmCmqOWHC5A&ab_channel=1littlecoder


evaluate
https://towardsdatascience.com/how-to-compute-f1-score-for-named-entity-recognition-in-keras-6f28b31dccca \
https://wandb.ai/abhigyan/Named%20Entity%20Recognition/reports/NER-Report--Vmlldzo0MDM0NjE \
https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html \
http://www.davidsbatista.net/blog/2018/05/09/Named_Entity_Evaluation/

Positional embedding
https://datascience.stackexchange.com/questions/51065/what-is-the-positional-encoding-in-the-transformer-model/51225#51225


## Syllables level embedding

Word2vec \
https://github.com/datquocnguyen/PhoW2V \
https://www.aclweb.org/anthology/2020.findings-emnlp.364.pdf 

Bert \
https://github.com/bino282/bert4news



## Note
pandas don't know if nan (string) is any different from nan(NaN)
