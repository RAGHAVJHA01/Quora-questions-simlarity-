# About data set
# Quora-questions-simlarity-
Where else but Quora can a physicist help a chef with a math problem and get cooking tips in return? Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

Currently, Quora uses a Random Forest model to identify duplicate questions. In this competition, Kagglers are challenged to tackle this natural language processing problem by applying advanced techniques to classify whether question pairs are duplicates or not. Doing so will make it easier to find high quality answers to questions resulting in an improved experience for Quora writers, seekers, and readers.
https://www.kaggle.com/c/quora-question-pairs

# complete detail of Bert Simlarity
Sentence similarity is one of the most explicit examples of how compelling a highly-dimensional spell can be.

The thesis is this:

Take a line of sentence, transform it into a vector.
Take various other penalties, and change them into vectors.
Spot sentences with the shortest distance (Euclidean) or tiniest angle (cosine similarity) among them.
We instantly get a standard of semantic similarity connecting sentences.

used transformer method to find the simlarity between questions
BERT, as we previously stated — is a special MVP of NLP. And a massive part of this is underneath BERTs capability to embed the essence of words inside densely bound vectors.

We call them dense vectors because each value inside the vector has a value and has a purpose for holding that value — this is in contradiction to sparse vectors. Hence, as one-hot encoded vectors where the preponderance of proceedings is 0.

