# loss-scope

Visualize changes in model weights over time, roughly describes the loss landscape.

Mostly to show if any weight pairs seem to oscillate back and forth while others change drastically. 

## Future Work

- Dimensionality reduce to not show many plots (pca, umap, tsne?)
- Save memory by plotting as we go and not saving entire weights
- Save memory by randomly sampling which weights to track?