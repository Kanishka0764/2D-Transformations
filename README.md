# 2D-Transformations
Implementation of 2D geometric transformations (Translation, Rotation, Scaling, Shearing, Affine, Similarity, and Projective) in Python with mathematical explanations and visualization.
# 2D Geometric Transformations

This project demonstrates *2D geometric transformations* in Python, including:

- *Translation*
- *Scaling*
- *Rotation*
- *Shear*
- *Similarity Transformation*
- *Affine Transformation*
- *Projective Transformation*

The transformations are implemented using *NumPy* and *Matplotlib* for visualization, making it easy to understand how each transformation modifies a given shape.

---

## 🔹 Mathematical Background
**Translation Matrix**

![Translation](https://latex.codecogs.com/svg.latex?\bg_white\begin{bmatrix}x'\\y'\\1\end{bmatrix}=\begin{bmatrix}1&0&t_x\\0&1&t_y\\0&0&1\end{bmatrix}\begin{bmatrix}x\\y\\1\end{bmatrix})

**Scaling Transformation**

![Scaling](https://latex.codecogs.com/svg.latex?\bg_white\begin{bmatrix}x'\\y'\\1\end{bmatrix}=\begin{bmatrix}s_x&0&0\\0&s_y&0\\0&0&1\end{bmatrix}\begin{bmatrix}x\\y\\1\end{bmatrix})

**Rotation Transformation**

![Rotation](https://latex.codecogs.com/svg.latex?\bg_white\begin{bmatrix}x'\\y'\\1\end{bmatrix}=\begin{bmatrix}\cos\theta&\sin\theta&0\\-\sin\theta&\cos\theta&0\\0&0&1\end{bmatrix}\begin{bmatrix}x\\y\\1\end{bmatrix})

**Shear Transformation**

![Shear](https://latex.codecogs.com/svg.latex?\bg_white\begin{bmatrix}x'\\y'\\1\end{bmatrix}=\begin{bmatrix}1&k_x&0\\k_y&1&0\\0&0&1\end{bmatrix}\begin{bmatrix}x\\y\\1\end{bmatrix})

**Similarity Transformation**

![Similarity](https://latex.codecogs.com/svg.latex?\bg_white\begin{bmatrix}x'\\y'\\1\end{bmatrix}=\begin{bmatrix}s\cos\theta&s\sin\theta&t_x\\-s\sin\theta&s\cos\theta&t_y\\0&0&1\end{bmatrix}\begin{bmatrix}x\\y\\1\end{bmatrix})

**Affine Transformation**

![Affine](https://latex.codecogs.com/svg.latex?\bg_white\begin{bmatrix}x'\\y'\\1\end{bmatrix}=\begin{bmatrix}a_{11}&a_{12}&t_x\\a_{21}&a_{22}&t_y\\0&0&1\end{bmatrix}\begin{bmatrix}x\\y\\1\end{bmatrix})

**Projective Transformation**

![Projective](https://latex.codecogs.com/svg.latex?\bg_white\begin{bmatrix}x'\\y'\\w\end{bmatrix}=\begin{bmatrix}h_{11}&h_{12}&h_{13}\\h_{21}&h_{22}&h_{23}\\h_{31}&h_{32}&h_{33}\end{bmatrix}\begin{bmatrix}x\\y\\1\end{bmatrix})

**Normalization:**  
![Normalization](https://latex.codecogs.com/svg.latex?\bg_white x'=\frac{x'}{w},\quad y'=\frac{y'}{w})



**Final coordinates after normalization:**

![Normalization](https://latex.codecogs.com/svg.latex?x%27=\frac{x%27}{w},\quad%20y%27=\frac{y%27}{w})


---

## 📂 Project Structure

2D-Geometric-Transformations/
│
├── IPA_Pythoncode.ipynb # Jupyter Notebook with implementations
├── README.md # Project documentation
└── requirements.txt # Dependencies


---


---

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/2D-Geometric-Transformations.git
cd 2D-Geometric-Transformations
```

**2. Install dependencies:**

pip install -r requirements.txt

**3. Run with Jupyter Notebook**

jupyter notebook IPA_Pythoncode.ipynb


**Requirements** :

numpy

matplotlib

jupyter
