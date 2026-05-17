## Why RNNs struggle with long-term dependencies
Traditional RNN process text sequentially and pass information from one step to another through hidden states. However, when sequence become long, earlier information gradually become weaker during training.This is also called as Vanishing gradients problem.Because of this, RNN often fail to remember important word or context that appeared much earlier in the sequence.
## How LSTM help with memory
Long Short-Term Memory (LSTM) network are improved version of RNNs designed to remember information for longer periods.
Special Gates of LSTM are-Forget Gate, Input Gate, Output Gate
These gates control which information should be stored, updated or removed form the memory.This helps LSTMs capture long term dependencies more effectively than traditional RNNs.
## What Attention solves in sequence to sequence Tasks
Attention mechanism helps model focus on the most important words in the input sequence while genrating predictions. Instead of relying on the final hidden state, attention allows the model to look at all important parts of the sequence dynamically.
This improves performance in task such as  Machine Translation, Text Summarization, Chatbots, Q&A.
Attenstion helps to solve the information bottelneck problem found in traditional encoder-decoder architecture.
## Why transformers are important in modern NLP and Generative AI
Transformers are modern DL architecture that rely entirely on attention mechanism instead of recurrent processing. key adavntaf=ge of transformers include- better parallel processing, faster training, Improved understanding, high stability.Transforemers are foundation of modern NLP and Gen AI model such as GPT,Gemini, Claude etc. They are widely used in application like Text generation and document reading & undersatnding. 
# Dataset Source Link-'C:\\Users\\DELL\\Desktop\\bitsom_ba_2511333_Kashid_Ashish_Assignment5\\BITSoM BA - Module 5 - Dataset\\ai_project_synthetic_datasets\\part_3_nlp_sequence_modeling'