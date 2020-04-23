# MS-BERT, Using Neurological Examination Notes to Further Pre-train BlueBERT for Multiple Sclerosis Severity Classification

## Motivation
Language models are evolving at an unprecedented rate. This can be observed through the development of models such as: [Transformers](https://github.com/huggingface/transformers), [BERT](https://arxiv.org/abs/1810.04805) (Bidirectional Encoder Representations from Transformers), [ELMo](https://arxiv.org/abs/1802.05365), [BioBERT](https://arxiv.org/abs/1901.08746), [BlueBERT](https://github.com/ncbi-nlp/bluebert), [XL-Net](https://arxiv.org/abs/1906.08237), and [Transformers-XL](https://arxiv.org/abs/1901.02860). These language models have created new possibilities by achieving strong results with moderate amounts of data in many Natural Language Processing tasks. 

That said, researchers have shown the value of transfer learning - pre-training a language model on a known task, and then performing fine-tuning - using the trained language model as the basis of a new purpose specific model. For example, the first task, pre-training a language model, has been applied to the biomedical domain by pre-training models on scientific text, and biomedical and clinical literature (hence the development of BlueBERT).

While BlueBERT poses as a strong language model for health care applications, we can further pre-train BlueBERT by using huggingface transformers and real clinical notes in order to generate a language model which is better suited for clinical applications we are working with. In our case, we aimed to develop a language model that is able to achieve good results in predicting Multiple Sclerosis (MS) severity.

Hence, this article looks at further pre-training BlueBERT, to develop what we call Multiple Sclerosis-BERT (or MS-BERT for short), and how this language model may be used for clinical prediction tasks with an [AllenNLP](https://allennlp.org/) Framework.

MS-BERT is a model developed by students at the University of Toronto along with the Data Science and Advanced Analytics (DSAA) department at St. Michael's Hospital.

## Tutorial
In this section we take you through pre-training MS-BERT and using MS-BERT (with an AllenNLP Framework) for Multiple Sclerosis Severity Classification.

### Data De-Identification

### BERT Pre-Training

### Note Level Embeddings

### AllenNLP Pipeline

## Outcomes

## Conclusion

## Acknowledgements
We would like to thank the researchers and staff at the Data Science and Advanced Analytics (DSAA) department, St. Michael’s Hospital, for providing consistent support and guidance throughout this project. We would also like to thank Dr. Marzyeh Ghassemi, and Taylor Killan at the University of Toronto for providing us the opportunity to work on this exciting project.
