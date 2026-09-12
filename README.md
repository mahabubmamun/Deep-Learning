## 📘 Notebooks

### 1. L2 Regularization — Mitigating Overfitting

**Notebook:** `regularization-l2-mitigating-overfitting.ipynb`

This notebook explores **L2 Regularization** as a technique for reducing overfitting in neural networks. A noisy `make_moons` dataset is used to compare a neural network **with and without L2 regularization**.

#### Topics Covered

* **Overfitting in Neural Networks**

  * Understanding how a model can learn noise and become overly complex.
  * Identifying overfitting using training and validation loss.

* **L2 Regularization**

  * Understanding the concept of L2 regularization.
  * Adding an L2 penalty to the model's loss function.
  * Understanding how L2 discourages large weight values.

* **Neural Network Regularization with Keras**

  * Using `kernel_regularizer` in Keras.
  * Applying `tensorflow.keras.regularizers.l2()` to Dense layers.

* **Comparing Regularized vs. Non-Regularized Models**

  * Training two neural networks with the same architecture.
  * Comparing their decision boundaries.
  * Comparing training and validation loss.

* **Decision Boundary Visualization**

  * Visualizing how neural networks learn nonlinear classification boundaries.
  * Observing the effect of regularization on model complexity.

* **Weight Analysis**

  * Extracting neural network weights using `model.get_weights()`.
  * Comparing weight distributions between regularized and non-regularized models.
  * Using box plots and distributions to analyze weight magnitude.

#### 🧰 Libraries Used

`Python` · `NumPy` · `Pandas` · `Matplotlib` · `Seaborn` · `Scikit-learn` · `TensorFlow/Keras` · `MLxtend`
