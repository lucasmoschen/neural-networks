# Neural Networks

Applied mathematics doctoral course with Neural Networks and Deep Learning Approach

This course is built by professor [Renato Souza](https://github.com/rsouza/NeuralNetworks_Course) and includes several topics:

- Supervised Machine Learning: Concepts and Process Workflow
- Neuron and Layers
- Universal approximation theorem
- Forward and BackPropagation, Gradient Checking
- Activation Functions
- Bias, Variance, Overfitting, Underfitting, Regularization
- Optimization, Batch and Mini-Batch
- Frameworks: PyTorch / Tensorflow
- Types of Neural networks

My partner [Lucas Resck](https://github.com/lucasresck) and I concluded the course with a work on Deep generative models for data creation (Deep fakes), exploring its first use in porn celebrities and how it became famous after [Barack Obama's video](https://www.buzzfeed.com/craigsilverman/obama-jordan-peele-deepfake-video-debunk-buzzfeed) was published.

After that, its usage only increased, with applications from entertainment videos and audios to [politics](https://www.technologyreview.com/2020/02/19/868173/an-indian-politician-is-using-deepfakes-to-try-and-win-voters/).

Technical Background 
---

- **Encoder-Decoder Networks:** Four neural networks are used alone or combined to create this kind of media: Two networks with narrower layers towards the center so that there is a encode in the latent space.
- **Convolucional Neural Networks:** Learn filters that move through the entrance forming a map of abstract features.
- **Generative Adversarial Networks:** A dispute between a neural network that generates fakes and a neural network that discriminates fakes from real ones.
- **Recurrent Neural Networks:** Handles sequential variables. After processing $x^{(i-1)}$ the network remembers the internal state and can use $x^{(i)}$.
 
Nowadays, CycleGan is a great tool used to deal with audio input. 
