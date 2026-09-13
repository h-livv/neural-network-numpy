# Neural Network from Scratch

### A feed-forward neural network implemented entirely from scratch using only NumPy.

> **Status: Archived / Early Experiment.**
> This was an early study of neural-network fundamentals and is preserved as
> part of my progression toward implementing larger models from first principles.

The project was an early attempt to understand neural networks by implementing
the underlying mathematics and training procedure directly rather than relying
on a machine-learning framework.

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

---