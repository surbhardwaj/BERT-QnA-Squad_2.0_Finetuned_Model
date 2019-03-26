# BERT-for-Question-Answering on Squad (Fine-tuned Model)
BERT which stands for Bidirectional Encoder Representations from Transformations is the SOTA in Transfer Learning in NLP.
It is based on the concept of TRANSFORMER - Self Attention. It has various transformer layer stacked over one other.
BERT base has L=12 layers and hidden size 768 whereas BERT Large has L=24 layers and hidden size=1024. It has an identical model as OpenAI GPT, with only difference that BERT uses Bidirectional self attention layers and which has really made a big difference. 

BERT is used for various tasks like NextSentencePrediction, BertForMultipleChoice, BertForQuestionAndAnswering. It has achieved SOTA performances on each of these tasks. 

For BERT to perform QnA task, a linear head is added at the top of BERT layers with two outputs for start and end logits of the answer. Later, these logits are used to get the best indices for the answers in the passage. 

I had fine-tuned the BERT-Base(12 layers) model on Squad-2.0 dataset. 






# Requirements
For running the code follwing dependies are required :

pip install pytorch-pretrained-bert

# Link for model Download
Below is the link for downloading Bert-on-Squad-V2.0 :

https://drive.google.com/file/d/1hktnjAJOdOwPxTK3R-KST9-kUQFYPusM/view?usp=sharing


