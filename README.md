# Chaii-2021
This repositiory contains work done by us while trying for the Chaii-2021 challenge. For the challenge we have to design a model to predict answers for questions from articles written in Hindi and Tamil. To make this model we first started to learn and explore concepts about NLP and NLU. We learnt about transformers expecially BERT.   
We went through various articles and other resources to get an idea on how to proceed with this problem. Some of the really helpful articles were:
- https://towardsdatascience.com/nlp-building-a-question-answering-model-ed0529a68c54  
- https://medium.com/saarthi-ai/build-a-smart-question-answering-system-with-fine-tuned-bert-b586e4cfa5f5
- https://towardsdatascience.com/illustrated-guide-to-transformers-step-by-step-explanation-f74876522bc0#:~:text=Encoder%20Layer&text=The%20Encoders%20layers%20job%20is,by%20a%20fully%20connected%20network. ( to learn about working of transformers)
- https://towardsdatascience.com/bert-explained-state-of-the-art-language-model-for-nlp-f8b21a9b6270 ( to learn more about how bert works)

We thought before moving on to Hindi and Tamil we should first try and make a model to predict answers to questions in English. So we used distilBERT( for faster training) to make a model to predict answers to questions from the Stanford question and answering dataset. The train-v2.0.json file is the training dataset from SQUAD. The bert qna.ipynb has the model that we implemented. 
