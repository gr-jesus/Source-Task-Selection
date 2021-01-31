# Source Task Selection for Transfer Deep Reinforcement Learning

## Abstract:
Deep Reinforcement Learning (DRL) combines the benefits of Deep Learning and Reinforcement Learning. However, it still requires long training times and a large number of instances to reach an acceptable performance. Transfer learning (TL) offers an alternative to reduce the training time of DRL agents, using less instances and in some cases improving performance. In this work, we propose a transfer learning formulation for DRL across tasks. A relevant problem to TL is how to select a proper pre-trained model that will be useful for the target task. In order to solve the latter problem we consider the entropy of feature maps in the hidden layers of the convolutional neural network and their actions spaces as relevant features to select a pre-trained model which is fine-tuned for the target task. We report experimental results of the proposed methodology when using Deep Q-Networks for learning to play Atari games. Results reveal that most of the time our proposed method is capable of selecting source tasks that improve the performance of a model trained from scratch.
Keywords: Transfer Learning, Deep Reinforcement Learning, Source Task Selection

## Code:
In order to share our code with the community we share it as colab notebooks. According to the process of the proposed method the pre-trained models (weights) for the thirty games in numpy array format can be downloaded in the next link, this files are used for load the weigths in the tensorflow models. The colab notebooks for our approach are the next:

- Experience Replay evaluation: [Link](https://colab.research.google.com/drive/1fHP33bdLESTmDG9avOXTe4ayLCLZtZix?usp=sharing)
- Hyperparameters search for the regresion models: [Link](https://colab.research.google.com/drive/1Hs0SxB0CfUK27Or2ksYkhanlZW3zbGAL?usp=sharing)
- Fine-tune and Train from scratch: [Link](https://colab.research.google.com/drive/1KTFaEkQSzVv1ARxuyKxjMoQKwVUw4G63?usp=sharing)

## Files:
We share the necessary files for run the code:

- Experience Replay for evaluate in the pre-trained models: [Link](https://www.google.com/url?q=https%3A%2F%2Fmega.nz%2Ffile%2FpldVXILK%23uIV1WwbCLqX5cRXGurPQUvPsyGn-_6UMGsXx7neCwXQ&sa=D)
- Weights of the pre-trained models: [Link](https://www.google.com/url?q=https%3A%2F%2Fmega.nz%2Ffile%2FYwFxRCoS%230NShbFwSujwRZ_EfgfiUfooM2-32FFcvMT9Mk8YRj0Y&sa=D)
- Files for evaluate the regression model: [Link](https://www.google.com/url?q=https%3A%2F%2Fmega.nz%2Ffile%2FpoMXES6D%23L-HOrf59YOHKQAtTTUnfecXP4t9slRpo6MCRGnX9SO8&sa=D)
- Regression model: [Link](https://www.google.com/url?q=https%3A%2F%2Fmega.nz%2Ffile%2Fg8FjhSoL%23mZDdAaRdk84W-c8tLxvHiIwfrEEy54bOVYwRuSQRUvo&sa=D)
- Full results for each game: [Link](https://www.google.com/url?q=https%3A%2F%2Fmega.nz%2Ffile%2FFxVn0CjD%23VFdun2a66X17oeYpmU9hjs1C5arvA_ekCkFhDQUBSHQ&sa=D)


## Aknowledgements:
The authors thankfully acknowledge computer resources, technical advice and support provided by Laboratorio Nacional de Supercómputo del Sureste de México (LNS), a member of CONACYT national laboratories with the projects No. 201901047C and 202002030c. We also want to acknowledge to the Laboratorio Nacional de Supercómputo del Bajio with the project No. 2020.1.  Jesús García-Ramírez acknowledges CONACYT for the scholarship that supports his PhD studies associated to CVU number 701191. 
