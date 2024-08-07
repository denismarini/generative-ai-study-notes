# Generative AI Glossary
<p align="center">
<img src="../gallery/glossary_word_cloud.png"  height="400"/>
</p>

## General Concepts

| **Term**                    | **Definition**                                                                                                                                                                                                  |
|-----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Generative AI**           | A branch of artificial intelligence focused on generating new content, such as text, images, music, or other data, using algorithms and models.                                                                 |
| **Neural Network**          | A computational model inspired by the human brain, consisting of layers of interconnected nodes (neurons) that process data and learn patterns.                                                                 |
| **Deep Learning**           | A subcategory of machine learning that uses neural networks with many layers (deep networks) to model complex patterns in large datasets.                                                                       |
| **Training Data**           | The dataset used to train a machine learning model, consisting of input-output pairs that guide the learning process.                                                                                           |
| **Ethical AI**              | The practice of designing and implementing AI systems in a fair, transparent manner aligned with ethical principles to avoid harm and bias.                                                                     |
| **Explainability**          | The ability to understand and interpret the decisions made by AI models, crucial for trust and accountability in AI systems.                                                                                    |
| **Bias**                    | Systematic error introduced by a model that leads to incorrect or unfair results, often due to imbalances in the training data.                                                                                   |
| **Overfitting**             | A modeling error that occurs when a machine learning model learns the noise and details in the training data to the extent that it negatively impacts its performance on new data.                               |
| **Synthetic Data**          | Data generated by a model that mimic real-world data, often used to augment training datasets or to protect privacy.                                                                                             |
| **Jailbreak (LLM)**         | In the context of a Large Language Model (LLM), jailbreak refers to the process of circumventing the restrictions and security measures implemented by the model developers.                                     |
| **Unsupervised Learning**   | A type of machine learning where the model learns patterns from unlabeled data, without explicit supervision or labeled examples.                                                                                |

## Models and Architectures

| **Term**                                   | **Definition**                                                                                                                                                                                                  |
|--------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Transformer**                            | A type of neural network architecture that uses self-attention mechanisms to process input data in parallel, particularly effective for natural language processing tasks.                                       |
| **GPT (Generative Pre-trained Transformer)** | A cutting-edge generative language model developed by OpenAI, capable of producing human-like text based on a provided prompt.                                                                                   |
| **BERT (Bidirectional Encoder Representations from Transformers)** | A transformer-based model designed to understand the context of words in a text by considering both the left and right context at all layers.                                          |
| **GAN (Generative Adversarial Network)**   | A type of generative model consisting of two neural networks, a generator and a discriminator, that compete with each other to produce realistic data.                                                           |
| **Autoencoder**                            | A type of neural network used for unsupervised learning that aims to learn efficient representations of data by encoding the input data into a lower-dimensional latent space and then reconstructing it.        |
| **VAE (Variational Autoencoder)**          | A generative model that learns to encode input data into a probabilistic latent space, from which new data can be generated through sampling.                                                                    |
| **Latent Space**                           | A high-dimensional space in which data is encoded into a compressed form, often used in generative models like autoencoders and GANs to represent the characteristics of input data.                             |
| **Latent Variable**                        | An unobserved variable inferred from observed data, used in generative models like VAEs and GANs to represent underlying structures.                                                                             |
| **Recurrent Neural Network (RNN)**         | A type of neural network designed to handle sequential data by maintaining a hidden state that captures information from previous steps in the sequence.                                                          |
| **Long Short-Term Memory (LSTM)**          | A type of RNN designed to capture long-range dependencies better by using special gating mechanisms to control the flow of information.                                                                          |
| **StyleGAN**                               | An adversarial generative network known for its ability to produce highly realistic images with controllable attributes by manipulating the latent space.                                                         |
| **Feed-Forward Network**                   | An artificial neural network where connections between nodes do not form cycles. Information moves in one direction: from input nodes to output nodes, passing through any hidden nodes.                         |
| **ReLU (Rectified Linear Unit)**           | A popular activation function used in neural networks that returns zero for negative inputs and the input itself for positive inputs, promoting sparsity and alleviating the vanishing gradient problem.         |
| **tanh (Hyperbolic Tangent)**              | A commonly used activation function in neural networks that squashes input values to the range [-1, 1], making it effective for outputs that range from -1 to 1.                                                  |
| **Diffusion Model**                        | A type of generative model that learns to generate data by reversing a diffusion process, often used to generate high-quality images.                                                                            |
| **Diffusion Probabilistic Model**          | A type of generative model that frames data generation as a diffusion process, gradually denoising a sample to produce realistic data.                                                                           |
| **Encoder**                                | A component of a neural network, particularly in sequence-to-sequence models, that processes input data and converts it into a contextual or fixed-dimensional representation.                                   |
| **Decoder**                                | A component of a neural network, particularly in sequence-to-sequence models, that takes the contextual representation produced by the encoder and generates the output sequence.                                 |
| **Context or Feature Representation**      | A fixed-dimensional vector or set of vectors produced by the encoder in a neural network, summarizing important information from the input data.                                                                 |

## Techniques and Mechanisms

| **Term**                    | **Definition**                                                                                                                                                                                                  |
|-----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Attention Mechanism**     | A technique used in neural networks, especially transformers, to dynamically focus on different parts of the input sequence, improving model performance on tasks like translation and summarization.            |
| **Self-Attention**          | A mechanism in neural networks, particularly in transformer models, that allows each element in the input sequence to pay attention to all other elements, improving model understanding and generation.         |
| **Encoder-Decoder Attention** | A mechanism used in sequence-to-sequence models where the decoder focuses on different parts of the encoder's output at each step of the output sequence generation.                                      |
| **Word Embedding**          | A representation of words in a continuous vector space where words with similar meanings have similar representations.                                                                                         |
| **Tokenization**            | The process of converting text into smaller units (tokens), such as words or subwords, that can be processed by a language model.                                                                               |
| **Context Windows**         | A technique used in various natural language processing algorithms where a limited portion of surrounding text (context window) is considered to analyze and understand the meaning of a word or phrase.        |
| **Beam Search**             | A search algorithm used in sequence generation tasks to find the most probable sequence of tokens by exploring multiple possible sequences simultaneously.                                                      |
| **Fine-Tuning**             | The process of further training a pre-trained model on a specific dataset to adapt it to a particular task or domain.                                                                                           |
| **Regularization**          | Techniques used to prevent overfitting by adding a penalty to the model's complexity, ensuring better generalization to unseen data.                                                                            |

## Learning Paradigms

| **Term**                    | **Definition**                                                                                                                                                                                                  |
|-----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Reinforcement Learning (RL)** | A type of machine learning where an agent learns to make decisions by interacting with an environment and receiving feedback in the form of rewards or penalties.                                            |
| **Zero-Shot Learning**      | The ability of a model to perform tasks or generate content without having seen any examples during training, relying on generalization from related tasks.                                                     |
| **Few-Shot Learning**       | The ability of a model to learn new tasks with very few training examples, demonstrating flexibility and adaptability.                                                                                           |
| **Transfer Learning**       | A machine learning technique where a pre-trained model is adapted to a new task with limited data, leveraging knowledge gained from the original task.                                                         |
