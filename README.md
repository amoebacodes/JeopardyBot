# JeopardyBot
This is the final project of 10617: Intermediate Deep Learning at Carnegie Mellon University, taught by Dr. Ruslan Salakhutdinov. Along with Kevin Elaba and Caroline Springer, we attempted at building a deep-learning based robot that could answer Jeopardy! questions based on Wikipedia articles. We explored various sequence-to-sequence and question-answering models. To build our Jeopardy bot, we want to do the following given a Jeopardy! question
1. Identify the relevant articles using FAISS, a fast semantic hashing method developed by Facebook.
2. Transform the Jeopardy! question into proper question form using T5 transformer.
3. Answer the proper question based on relevant articles using a lite QA model, such as RoBERTa.

Please refer to [our report](https://github.com/amoebacodes/JeopardyBot/blob/main/report.pdf) for detailed methods and results.
