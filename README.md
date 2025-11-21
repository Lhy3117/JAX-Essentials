# ⚡️ JAX Essentials: A Quick Start Guide


This repository is my personal collection of essential patterns and examples for learning **JAX**—the library that is revolutionizing high-performance numerical computing and machine learning.

If you are coming from NumPy, JAX feels familiar but brings superpowers like **autograd** and **XLA compilation**. I built this guide to bridge that gap and serve as a quick reference for your projects (like computational economics models!).

## 🌟 What's Inside?

I've broken down the core concepts into digestible sections within the notebook (`JAX_essentials.ipynb`):

1.  **NumPy on Steroids**: How `jax.numpy` mimics `numpy` but runs on accelerators (GPU/TPU).
2.  **Random Numbers**: Understanding JAX's unique key-based random number generation (PRNG)—critical for reproducibility.
3.  **The Magic of `jit`**: Using `@jax.jit` to compile your functions and make them fly. 🚀
4.  **Functional Programming**: Why "pure functions" matter in JAX.
5.  **Automatic Differentiation (`grad`)**: Calculating derivatives without the headache—essential for optimization.
6.  **Vectorization (`vmap`)**: Replacing slow loops with parallelized batch operations automatically.
7.  **Implementation**: A practical example of **Monte Carlo Option Pricing**, showing how to put it all together.

## 🚀 Why JAX?

*   **Speed**: It compiles your Python code to optimized machine code via XLA.
*   **Simplicity**: It looks just like NumPy.
*   **Power**: It powers modern research, from deep learning to economic modeling.

## 🛠️ Usage

1.  **Clone the repo**:
    ```bash
    git clone https://github.com/HaoyuanLi/JAX_essentials.git
    ```

2.  **Install JAX**:
    ```bash
    pip install jax jaxlib
    ```

3.  **Run the notebook**:
    ```bash
    jupyter notebook JAX_essentials.ipynb
    ```

## 🔗 Related Projects

*   **[McCall Job Search Model](https://github.com/HaoyuanLi/mccall-job-search-model)**: See JAX in action in a full economic model.


---

*Happy JAX-ing!* ⚡️


