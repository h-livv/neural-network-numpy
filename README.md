# Neural Network from Scratch

A neural network built **entirely from scratch using only NumPy**.

The purpose of this project was to understand how neural networks actually work by implementing the underlying mathematics and training procedure myself, rather than relying on a machine-learning framework.

The implementation covers:

- Activation functions
- Forward propagation
- Loss calculation
- Gradient descent
- Backpropagation
- Parameter updates
- Feature normalization
- Model evaluation

The network is trained on the Heart Disease dataset using only **NumPy** for the neural-network implementation. No PyTorch, TensorFlow, scikit-learn, or other ML framework is used.

## Why?

This was an early attempt to understand neural networks from first principles. At the time, I did not yet have a strong mathematical foundation for the underlying concepts, so implementing the network forced me to work through how gradient descent, derivatives, activation functions, and backpropagation actually produce learning.

## Files

- `Neural_Network.ipynb` — Step-by-step implementation and exploration
- `Neural_Network.py` — Standalone implementation
- `heart.csv` — Dataset

## Dependencies

```bash
pip install numpy pandas matplotlib
````

## Running

```bash
jupyter notebook Neural_Network.ipynb
```

or

```bash
python Neural_Network.py
```
