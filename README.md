# Torch to FPGA using NNgen

A `colab_nngen_lenet.ipynb` file contains steps needed to:
1. Setup environment and install NNgen in Google Colab service,
2. Load a neural network model saved in ONNX format and implemented using Torch. As we tested, models saved with Tensorflow do not work with NNgen,
3. Generate IP block for Vivado,
4. Quantize and save model weights.
