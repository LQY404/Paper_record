- Distributed Iterative Gating Networks for Semantic Segmentation
  - presents a light-weight mechanism for adaptive control of computation similar to recurrent convolutional neural networks by integrating feedback signals with a feed forward architecture.
  - In contrast to other RNN formulations, DIGNet generates feedback signals in a cascaded manner that implicitly carries information from all the layers above.

- Differentiable Scene Graphs
  - Reasoning systems based on SGs are typically trained in a two-step procedure: first, a model is trained to predict SGs from images, and next a separate model is trained to reason based on the predicted SGs. However, it would seem preferable to train such systems in an end-to-end manner.
  - propose Differentiable Scene Graphs (DSGs), an image representation that is amenable to differentiable end-to-end optimization, and requires supervision only from the downstream tasks.
  - DSGs provide a dense representation for all regions and pairs of regions, and do not spend modelling capacity on regions of the image that do not contain objects or relations of interest.

- Leveraging Pretrained Image Classifiers for Language-Based Segmentation
  - semantic segmentation models cannot easily generalize to new object classes unseen during train time.
  - propose a novel segmentation model that injects visual priors into semantic segmentation architectures, allowing them to segment out new target labels without retraining.

- Improved Embeddings with Easy Positive Triplet Mining
  - propose an alternative, loosened embedding strategy that requires the embedding function only map each training image to the most similar examples from the same class, an approach we call “Easy Positive” mining.
  - experiments and visualizations that highlight that this Easy Positive mining leads to embeddings that are more flexible and generalize better to new unseen data.
  - exceeds state of the art approaches on image retrieval datasets.

