# AWS-Llama-2-7B-Fine-tuned-model
Train (fine-tune) a Llama 2 7B large language model that should become a domain expert, capable of generating informative, accurate, and contextually relevant text responses. 

## Pre-trained Model Evaluation

### Deploy the Llama2 Model on AWS Sagemaker
The Llama2 model is successfully deployed on AWS Sagemaker. The output of the Model_Evaluation.ipynb file verifies deployment Screenshots in the report show the model deployed in the SageMaker environment
### Evaluate the Pre-trained Llama2 Text Generation Large Language Model for Domain Knowledge
Model evaluation uses input to evaluate generation of domain-specific content, based on chosen domain for fine-tuning. The model_evaluation.ipynb notebook contains relevant examples and output cells. The response of the model to domain-specific inputs is documented in the project report.

## Fine-tuning a Large Language Model

### Fine-tune a Large Language Model with a Domain-Specific Dataset
The model is fine-tuned using a dataset relevant to the chosen domain (Financial, Healthcare, IT). The model_finetuning.ipynb notebook demonstrates the fine-tuning process The dataset used for fine-tuning is set to the chosen domain in the Model_FineTuning.ipynb notebook file. Screenshots of the fine-tuning cell output are present.
