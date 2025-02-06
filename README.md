# LLM_LEARNINGs You Can Find All My LLM learnings .
1) BUILDING THE LARGE LANGUAGE MODELS FROM SCRATCH.
      -> resources : i followed the book of llm from scratch by sabastian
      1) I learned how to handel the text ie loading the dataset , preparing the dataset , creating the dataloaders . Also learned how to tokenize the text using the Byte-pair-encoder . BPE is also used in chatgpt .  [  please click for seeing it ] (https://github.com/Ayushsrinivas7/LLM_LEARNINGS/blob/main/LLM_FROM_SCRATCH/1_byte_pair_encoding.ipynb)
      2) I learned how to code entire self attention , multi head attention from scratch from scratch  using python - pytorch tested and tried to visualize the complete attention mechanism .
         [ click this link for my detailed notes  and colab note book ](https://github.com/Ayushsrinivas7/LLM_LEARNINGS/blob/main/LLM_FROM_SCRATCH/2_ATTENTION_MECHANISM.ipynb)
      3) I have built the **Entire Coustm GPT model  ie ie every parameter in the  gpt is customizable like no of transformer blocks , embed dimensions , batch size**  as part of  it  built blocks like  transformer , attention , feed forward , output projection and not every thing is customizable
         [click the link for my colab notes ](https://github.com/Ayushsrinivas7/LLM_LEARNINGS/blob/main/LLM_FROM_SCRATCH/4_mylearning__CODING__THE_GPT_2.ipynb)
         ![the architecture](https://drive.google.com/file/d/1DAD3Rbi_3vJr9YmFmWecn-1rP7zIzEWm/view?usp=sharing) 

      4) We know that **deep learning is noting but finding the weight in the name of minimizing the loss**  se here i have built the entire loss function from scratch and also tested it and written note with the examples
         [click the link to see my notes ](https://github.com/Ayushsrinivas7/LLM_LEARNINGS/blob/main/LLM_FROM_SCRATCH/5_my_learning_lossfunction_Coding_gpt2.ipynb)
      5) I **built the entire training loop for the gpt2 for cutsom data set** and trained the model with harry poter books . The model is of **124M** note . in this note book i imported the model from gpt_model.py file ie the code written in the previous colab .  I also wrote the code for loading our model with the open-ai weights ie pretrianed weights.
         [pretraining colab](https://github.com/Ayushsrinivas7/LLM_LEARNINGS/blob/main/LLM_FROM_SCRATCH/5_1_Mylerning_Building_GPT2_From_scrtach_and_pretraingipynb.ipynb) , [easy weight loading techniques colab ](https://github.com/Ayushsrinivas7/LLM_LEARNINGS/blob/main/LLM_FROM_SCRATCH/5_2Bringing_weights_from_hugginfface_lodaing_tipynb.ipynb) , ( see this colab for authors covering of various topics like memory efficient loading  )[https://github.com/rasbt/LLMs-from-scratch/tree/main/ch05]  ![entire archtecture](https://drive.google.com/file/d/1DGy_8ZKTKYgG0DUzh9iNtEgwGMnpkLMc/view?usp=sharing)
      
        
         

    
1) NOTES RELATED TO BEART BASED MOVIE REVIEW 
![WhatsApp Image 2024-11-13 at 05 32 34_997bab61](https://github.com/user-attachments/assets/e41b47af-d855-4e02-9277-5c0c43f26a1f)

# here i created a agent from scratch . 
Welcome to my project! This is a journey into building a ReAct Agent from scratch using Python and groq api . Here, I'll walk you through the learning experience, the fascinating architecture, and the functionalities behind this agent that integrates automation tools with large language models (LLMs).
LLM used : Lamma 70b 3.3 
here the main thing is Thought -> Action -> observation -> answer 
![ai agent inital 1](https://github.com/user-attachments/assets/060964fc-d62e-41b5-a2b9-826dd5fb53f5)
reference https://medium.com/the-ai-forum/create-a-react-agent-from-scratch-without-using-any-llm-frameworks-only-with-python-and-groq-c10510d32dbc

