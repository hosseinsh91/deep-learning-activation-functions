# Deep Learning Activation Functions: Visualization and Analysis

## **📌 Project Overview**
This project implements and visualizes **activation functions** commonly used in **Artificial Neural Networks (ANNs)**. Activation functions determine how neurons in a neural network activate and pass information forward. The notebook provides **mathematical insights**, **Python implementations**, and **graphical representations** of each function and its derivative.

### **🚀 Key Features**
✅ Implementation of **ReLU, ELU, Tanh, and Sigmoid** activation functions  
✅ **Mathematical formulations** of activation functions and their derivatives  
✅ **Graphical representations** to analyze function behavior  
✅ **Gradient analysis** to understand optimization impact  

---

## **📌 Activation Functions Covered**
### **1️⃣ ReLU (Rectified Linear Unit)**
- Formula:  
  \[
  f(x) = \max(0, x)
  \]
- Pros: Efficient, prevents vanishing gradients  
- Cons: Can suffer from dying neurons (gradient becomes 0)  

### **2️⃣ ELU (Exponential Linear Unit)**
- Formula:  
  \[
  f(x) =
  \begin{cases} 
  x, & x > 0 \\
  \alpha (e^x - 1), & x \leq 0
  \end{cases}
  \]
- Pros: Reduces dying ReLU problem, smooth gradient  
- Cons: Slightly more computationally expensive  

### **3️⃣ Tanh (Hyperbolic Tangent)**
- Formula:  
  \[
  f(x) = \frac{e^x - e^{-x}}{e^x + e^{-x}}
  \]
- Pros: Outputs range from **-1 to 1**, better for normalized data  
- Cons: Can still suffer from vanishing gradients  

### **4️⃣ Sigmoid**
- Formula:  
  \[
  f(x) = \frac{1}{1 + e^{-x}}
  \]
- Pros: Useful for **binary classification**  
- Cons: **Vanishing gradient** issue for large/small values  

---

## **📌 Installation & Setup**
### **Prerequisites**
- Python 3.x
- Jupyter Notebook
- NumPy, Matplotlib

### **📌 Install Required Libraries**
```bash
pip install numpy matplotlib
