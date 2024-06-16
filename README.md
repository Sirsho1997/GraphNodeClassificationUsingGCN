## Graph Node Classification Using GCN

This repository contains information and documentation for working with the 'Computer' part of the AmazonCoBuy dataset. This dataset is part of the larger AmazonCoBuy collection and focuses on co-purchasing behavior among computer-related goods.

## Dataset Description
- Nodes: 13,752 (represent goods)
- Edges: 491,722 (indicate that two goods are frequently bought together)
- Node Features: 767 (bag-of-words encoded product reviews)
- Class Labels: 10 (product categories)
- Self-Loops: Self-loops are added to the graph regardless of whether they already exist


### Graph Neural Network

- Implemented the Graph Convolutional Network (GCN) model with 2 layers and trained it using the Adam optimizer with cross-entropy selected as the loss function.
- Achieved best validation accuracy of 87.3%.
- Python libraries used: DGL, PyTorch, Matplotlib, and Seaborn.

### Usage
This dataset and preprocessing information can be used for tasks such as node classification, link prediction, and other graph-based machine-learning tasks. Ensure that the necessary preprocessing steps, such as adding self-loops and defining train/validation/test masks, are completed before training models on this dataset.

