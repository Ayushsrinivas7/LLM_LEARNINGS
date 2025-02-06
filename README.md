# This is AyushSrinivas7 (prathipati yadu vamsi ) From IIT patna  here are my entire Learnings - Notes -Projects in my LLM journey
# LLM_LEARNINGS.

You can find all my LLM learnings documented here.

## 1) Building Large Language Models from Scratch

### Resources:
I followed the book **"LLM from Scratch"** by Sebastian.

### My Learnings:

#### 1. Handling Text Data
- Learned how to **load datasets, prepare datasets, and create dataloaders**.
- Implemented **Byte-Pair Encoding (BPE) for tokenization**, which is also used in ChatGPT.
- [Click here to see colab and notes ](https://github.com/Ayushsrinivas7/LLM_LEARNINGS/blob/main/LLM_FROM_SCRATCH/1_byte_pair_encoding.ipynb)

#### 2. Implementing Attention Mechanism
- Coded **Self-Attention** and **Multi-Head Attention** from scratch using **Python & PyTorch**.
- Visualized the **complete attention mechanism**.
- [Click here for detailed notes and notebook](https://github.com/Ayushsrinivas7/LLM_LEARNINGS/blob/main/LLM_FROM_SCRATCH/2_ATTENTION_MECHANISM.ipynb)

#### 3. Building a Custom GPT Model
- Implemented a **fully customizable GPT model** where parameters like the number of transformer blocks, embedding dimensions, and batch size can be modified.
- Built core components like **Transformer, Attention, Feed Forward, Output Projection**, making the entire architecture customizable.
- [Click here for my Colab notebook ](https://github.com/Ayushsrinivas7/LLM_LEARNINGS/blob/main/LLM_FROM_SCRATCH/4_mylearning__CODING__THE_GPT_2.ipynb)

  ![GPT Model Architecture](https://drive.google.com/uc?export=view&id=1DAD3Rbi_3vJr9YmFmWecn-1rP7zIzEWm)

#### 4. Implementing Loss Function from Scratch
- Built the **entire loss function** from scratch.
- Tested it and documented **detailed notes with examples**.
- [Click here to see my notes and colab ](https://github.com/Ayushsrinivas7/LLM_LEARNINGS/blob/main/LLM_FROM_SCRATCH/5_my_learning_lossfunction_Coding_gpt2.ipynb)

#### 5. Training GPT-2 on a Custom Dataset
- **Implemented the full training loop for GPT-2** and trained the model using the **Harry Potter books** dataset.
- Built a **124M parameter model**.
- Imported the model from `gpt_model.py` (previously implemented modules).
- Implemented code for **loading OpenAI’s pre-trained weights** into the model.

  - [Pretraining Colab](https://github.com/Ayushsrinivas7/LLM_LEARNINGS/blob/main/LLM_FROM_SCRATCH/5_1_Mylerning_Building_GPT2_From_scrtach_and_pretraingipynb)
  - [Easy Weight Loading Techniques colab ](https://github.com/Ayushsrinivas7/LLM_LEARNINGS/blob/main/LLM_FROM_SCRATCH/5_2Bringing_weights_from_hugginfface_lodaing_tipynb)
  - [Comprehensive Colab by the Author on Efficient Loading](https://github.com/rasbt/LLMs-from-scratch/tree/main/ch05)

  ![Entire Architecture](https://drive.google.com/uc?export=view&id=1DGy_8ZKTKYgG0DUzh9iNtEgwGMnpkLMc)

___

# PROJECT :Redesiging _GPT2_for_SPAM_classification_&_finetuning_it.
I redesigned the entire GPT2 and finetuned the model (redesigned : the last output layer with 2 nodes for spam and no spam classification) . (for finetunning i just made the last transformer block and final layernorm  trainable ).   [SEE my git hub of normal and lora fine tunning ](https://github.com/Ayushsrinivas7/Project_GPT_Classifer). Every thing is from scratch 
note : for loading the model use the gpt2_model.py file so that you can load the model directly also see the prev colab of how to load the pretrains to our model 

![steps i followed](https://drive.google.com/uc?export=view&id=1fJ-_7pNN9ngsp5AKcD5tCMhJ6qXuXS4z) 
![Architecture ](https://drive.google.com/uc?export=view&id=1AKkTg2XnGdKqGzqgW0SLTzc3s3J3zTrr)

![loss](https://drive.google.com/uc?export=view&id=1LDxwVXJPv4X2Uxx2rWPCra8NxI69NkUq)

Also attached the finetuned the model with **fully custom built lora code ie built the lora class and replaced every linear layer with the lora linear layer so that pretrain information is retained and also the number of trainable weights is decreased ie 124 million to 2 million **
![LORA image](https://drive.google.com/uc?export=view&id=1wf-JfaUKMDZIU3CWFZmgvTVPvqovfuIv)

![Lorra loss curve](https://drive.google.com/uc?export=view&id=1sEz04dz3n9st6FvbJgQpDYTIfotBQnnw)
___
    
1) NOTES RELATED TO BEART BASED MOVIE REVIEW 
![WhatsApp Image 2024-11-13 at 05 32 34_997bab61](https://github.com/user-attachments/assets/e41b47af-d855-4e02-9277-5c0c43f26a1f)

# here i created a agent from scratch . 
Welcome to my project! This is a journey into building a ReAct Agent from scratch using Python and groq api . Here, I'll walk you through the learning experience, the fascinating architecture, and the functionalities behind this agent that integrates automation tools with large language models (LLMs).
LLM used : Lamma 70b 3.3 
here the main thing is Thought -> Action -> observation -> answer 
![ai agent inital 1](https://github.com/user-attachments/assets/060964fc-d62e-41b5-a2b9-826dd5fb53f5)
reference https://medium.com/the-ai-forum/create-a-react-agent-from-scratch-without-using-any-llm-frameworks-only-with-python-and-groq-c10510d32dbc

