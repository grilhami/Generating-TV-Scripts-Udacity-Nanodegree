# Generating-TV-Scripts-Udacity-Nanodegree

For the Project of the Udacity Nanodegree, I generated my own Simsons TV scripts using RNNs. I'll be using part of the Simpsons dataset of 
scripts from 27 seasons. The Neural Network I was able build generated a new TV script for a scene at Moe's Tavern.

Language is in many ways the seed in intelligence. We as humans use language to convey informations beetween each other. But 
unfortunately, computers can't really understand human languages. New breatktrough in AI has led to more technolgies in language 
understanding called Natural Language Processing (NLP).

# Dependencies:

-Numpy

-Tensorflow

-Floyd (from FloydHub for cloud computing)

# While doing this project, I was introduced to...

# Natural Language Processing (NLP)

NLP is the study that focuses on the interactions between human language and computers. By using NLP, developers can organize and 
structure knowledge to perform tasks such as automatic summarization, translation, named entity recognition, relationship extraction, 
sentiment analysis, speech recognition, and topic segmentation. 

More on NLP:

https://blog.algorithmia.com/introduction-natural-language-processing-nlp/

https://en.wikipedia.org/wiki/Natural_language_processing

# Recurrent Neural Network (RNN)

As we read, we understand each words based on our understanding of the previous word. This is exactly what Recurrent Network do. Unlike 
traditional neural nets (that given an input produces an output), RNN hadles sequences of inputs. This means that it takes it's input not 
jsut based on the current example, but also what it preceived one step back in time. RNNs have been used in a variety of problems: speech 
recognition, language modeling, translation, image captioning. Ther are many kinds of RNNs that exist out there.

More on Recurrent Neural Network:

https://deeplearning4j.org/lstm.html

http://colah.github.io/posts/2015-08-Understanding-LSTMs/

# Long Short Term Memory (LSTM) Network

Although RNNs have been used in a variety of problems, they have some issues long-term dependencies. Thankfully, Long Short Term Memory 
(LSTM) Network doesn't have this problem.LSTM is special kind of RNN that can handle long-term dependencies. In fact, it is explicitly 
designed to avoid long-term dependency problems. 

More on LSTM:

http://colah.github.io/posts/2015-08-Understanding-LSTMs/

https://ayearofai.com/rohan-lenny-3-recurrent-neural-networks-10300100899b


# Word Embedding and Word2Vec

In short, Word embedding turn text into numbers. Like I mantioned before, computers can't understand human language. They won't work
on just strings of plain text. Method like Word Embedding is used to trans form input texts to vectors on continuous values. Word2Vec is 
used as a predictive model to learn word embeddings from raw text because it's particularly computanionally-efficient.

More on Word Embedding and Word2Vec:

https://www.quora.com/What-is-word-embedding-in-deep-learning

https://en.wikipedia.org/wiki/Word2vec

https://www.tensorflow.org/tutorials/word2vec

