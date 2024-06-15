# GAI_hw4
>   Guiding DIP Early Stopping with DDPM-inspired Supervision

You can run main.ipynb directly to reproduce the experiment.

This experiment involves using forward process output of DDPM model (noisy image sequence) as the training target for DIP model.
We use 10 different trainging stage to train DIP model, starting from the most corrupted image and gradually moving towards the clean target image.

We expect this approach will improve the DIP model reconstruction quality.Since the model can learn the hierarchical representation of target image.

The result is shown below.

