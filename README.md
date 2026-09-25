# Calculate months for 130 days
days = 130
months_approx = days / 30
print(f"{months_approx:.2f}")

# Math-Notes
An academic Python repository implementing Gradient Descent optimization from scratch, demonstrating the power of Calculus and Derivatives in AI
# 📉 Calculus in AI: Gradient Descent Optimization Solver

Welcome to my computational mathematics repository! This project showcases the direct application of **Multivariable Calculus** and **Optimization Theory** in Modern Machine Learning by implementing the **Gradient Descent** algorithm from scratch.

## 📐 The Mathematical Foundation

Gradient Descent is an optimization algorithm used to minimize a function by iteratively moving in the direction of steepest descent, defined by the negative of the gradient.

### 1. The Objective Function
We consider a standard quadratic convex cost function:
$$ f(x) = x^2 + 4x + 4 $$

### 2. The Calculus Element (The Derivative)
To find the minimum, the algorithm computes the exact rate of change (derivative) at any given point to determine the slope:
$$ f'(x) = \frac{d}{dx}(x^2 + 4x + 4) = 2x + 4 $$

### 3. The Optimization Update Rule
Using the derivative, the algorithm updates the position iteratively using a scaling parameter called the **Learning Rate** ($\alpha$):
$$ x_{next} = x_{current} - \alpha \cdot f'(x_{current}) $$

When $f'(x) = 0$, the algorithm reaches the global minimum (critical point), where the tangent line is completely horizontal.

---

## 💻 Technical Stack & Implementation
* **Language:** Python 3
* **Libraries Used:** 
  * `NumPy` for efficient numerical vector arrays.
  * `Matplotlib` for generating dynamic geometric plots.
* **Features:** Generates a visual convergence trajectory map saved automatically as `optimization_plot.png`.

## 🚀 Execution & Setup
1. Clone this repository.
2. Install the mathematical libraries:
   ```bash
   pip install numpy matplotlib
   ```
3. Run the solver script:
   ```bash
   python main.py
   ```

---
✨ *Engineered with precision by Ahlam Al-Mutairi — Mathematics Undergraduate student exploring Deep Learning Foundations.*
