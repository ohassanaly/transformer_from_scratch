Implementing the Transformer from scratch as defined by https://arxiv.org/abs/1706.03762 

We use PyTorch and follow https://www.youtube.com/watch?v=ISNdQcPhsts  
For the output of ResidualConnection, We Normalize  (layer output + x) instead of Normalizing the layer output before adding x as in the video