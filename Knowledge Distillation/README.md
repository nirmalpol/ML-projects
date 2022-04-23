## Main Notebook Files
This project demonstrates the use and impact of Knowledge Distillation (KD) with the MNIST dataset using TensorFlow. Large resource intensive Neural Net model are difficult to run on IoT or end use devices like smartphones. KD takes these large models and has them train smaller "Student" models by transferring the hidden dark knowledge as outlined in Hinton et al (2015) paper. This transfer effectively helps to compress the large model's knowledge into a smaller model while attempting to maintain a high level of accuracy.

### Task1.ipynb
This notebook contains many sections that must be run from top to bottom to get the results of KD on the MNIST dataset.

## References to Open Source Libraries
- G. Hinton, O. Vinyals, and J. Dean, “Distilling the Knowledge in a Neural Network,”
ArXiv150302531 Cs Stat, Mar. 2015, Accessed: Apr. 03, 2022. [Online]. Available:
http://arxiv.org/abs/1503.02531
- M. Abadi et al., “TensorFlow: Large-Scale Machine Learning on Heterogeneous Distributed Systems,” ArXiv160304467 Cs, Mar. 2016, Accessed: Mar. 01, 2022. [Online]. Available: http://arxiv.org/abs/1603.04467
- M. T. Ribeiro, S. Singh, and C. Guestrin, “‘Why Should I Trust You?’: Explaining the Predictions of Any Classifier,” in Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, New York, NY, USA, Aug. 2016, pp. 1135–1144. doi: 10.1145/2939672.2939778.
