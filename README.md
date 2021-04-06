# Sentiment Analysis using Recurrent Neural Networks

## Instructions

### 1. Installing Dependencies
Can be installed using `pip install` **or** `conda install` for *Anaconda environment*

- Python 3.7 
- Libraries 
  - pytorch (1.2.0)
  - tensorflow (2.0.0)
  - gensim (3.8.3)
  - tqdm (4.56.0)
    
### 2. Architecture

![Image of Yaktocat](https://i.postimg.cc/QNp5pFwd/sdf.png)                                            
                                                                                                       
The layers are as follows:                                                                             
- **Tokenize:** This is not a layer for LSTM network but a mandatory step of converting our words into 
- **Embedding Layer:** that converts our word tokens (integers) into embedding of specific size        
- **LSTM Layer:** defined by hidden state dims and number of layers                                    
- **Fully Connected Layer:** that maps output of LSTM layer to a desired output size                   
- **Sigmoid Activation Layer:** that turns all output values in a value between 0 and 1                
- **Output:** Sigmoid output from the last timestep is considered as the final output of this network  
