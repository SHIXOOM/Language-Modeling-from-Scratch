# Language Modeling from Scratch
Over the past couple of months I've been working on multiple projects with agents and RAG, which made me use and interact with word embedding models alot, I also was trying to understand recommender systems and graph neural networks. So...  
I wanted to learn about word embeddings from like, the beginning, to understand it and the intuitions and mathematical concepts behind it. I specifically aimed to read Word2Vec paper and implement it from scratch, but then I gone a step back to understand earlier work for neural language models, and then the language modelling in general as statistical modelling.  

# N-Grams  
So the first step I took was learning n-grams language models from ***Speech and Language Processing: An Introduction to Natural Language Processing Computational Linguistics, and Speech Recognition with Language Models*** *Third Edition draft* from *Daniel Jurafsky*, and *James H. Martin*.

I made a small notebook that explained the main concepts I learned and a simple implementation of bigram model on a Twitter Hate Speech dataset (because the generated sentences will be funny).

Next step is ***A neural probabilistic language model*** paper from (*Bengio, Y., et al, 2003*).

# Neural Language Model  
I read, understood (as much as I can), and re-implemented ***A neural probabilistic language model*** paper (*Bengio, Y., et al, 2003*).  
*  I really learned a lot of things about language modeling.
*  And learned much more things about deep learning in application while trying to replicate the paper's results for a 1.5 week of retraining the model over and over :)
*  Things about tokenization, Stochastic Gradient Descent's senstivity to learning rate and batch size, and many more.
*  You can find everything, explanation, application, trials and discussion of what worked and what didn't in the notebook under ***Neural Language Model***.
*  Next, I will read, understand, re-explain, and re-implement Word2Vec ***"Mikolov, Tomas, et al. "Efficient estimation of word representations in vector space. (2013)"***


# I realized I am doing Language Modeling from Scratch not just word embeddings!!
