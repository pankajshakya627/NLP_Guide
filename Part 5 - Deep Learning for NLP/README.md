# Part 5: Deep Learning for NLP

This section introduces the modern era of NLP. Deep Learning allows models to learn features automatically, leading to state-of-the-art performance in almost every NLP task.

## 🎯 Learning Objectives
By the end of this section, you will be able to:
*   Understand the shift from sparse vectors to dense Word Embeddings.
*   Explain the math behind Word2Vec (Skip-gram).
*   Trace the data flow in RNNs and understand Backpropagation Through Time (BPTT).
*   Understand how LSTMs and GRUs solve the vanishing gradient problem.
*   Master the Self-Attention mechanism that powers Transformers.

## 📂 Section Contents

### [5.1 Introduction to Deep Learning for NLP](5.1_Introduction_to_Deep_Learning.md)
Why Deep Learning? A high-level overview of Neural Networks in the context of language processing.

### [5.2 Word Embeddings](5.2_Word_Embeddings.md)
Representing meaning in vector space:
*   **Word2Vec:** CBOW vs. Skip-gram architectures.
*   **Math Spotlight:** The Softmax loss function and objective for Skip-gram.
*   **GloVe & FastText:** Alternative embedding strategies.

### [5.3 Recurrent Neural Networks (RNNs)](5.3_Recurrent_Neural_Networks.md)
Processing sequences:
*   **Architecture:** Hidden states and time-steps.
*   **Math Spotlight:** Forward pass equations and **Backpropagation Through Time (BPTT)** gradients.

### [5.4 Long Short-Term Memory (LSTM)](5.4_Long_Short-Term_Memory.md)
Solving long-term dependency issues:
*   **Gates:** Input, Forget, and Output gates.
*   **Math:** Detailed equations for cell state updates.

### [5.5 Gated Recurrent Units (GRUs)](5.5_Gated_Recurrent_Units.md)
A simplified, efficient alternative to LSTMs:
*   **Gates:** Reset and Update gates.
*   **Comparison:** When to use GRUs vs. LSTMs.

### [5.6 Transformers](5.6_Transformers.md)
The architecture that changed everything:
*   **Self-Attention:** The core mechanism.
*   **Math Spotlight:** A complete solved matrix example of calculating **Query, Key, Value** and **Attention Scores**.
*   **Positional Encoding:** Handling sequence order without recurrence.