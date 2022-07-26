# Dimensions and notations
---

# Regularization

$$minJ(w,b)$$
$$J(w,b)=\frac{1}{m}\sigma_{i=1}^mLoss(\hat{y}^{(i)},y^{(i)})+\frac{\lambda}{2m}||w||_ {2}^{2}+\frac{\lamda}{2m}b^2$$
$L_{2} reg:  $||w||_ 2^2=\sigma_{j=1}^{n_x}w_{j}^{2}=w^T\cdot w$
$L_{1} reg:  $\frac{\lamda}{2m}\sigma_{i=1}^{n_x}=\frac{\lamda}{2m}||w||_ {1}$

$$J(w^{[1]},b^{[1]},...w^{[L]},b^{[L]}=\frac{1}{m}\sum_{i=1}^{m}Loss(\hat{y}^{(i)},y^{(i)}+\frac{\lamda}{2m}\sigma_{l=1}^{L}||w^{[l]}||^{2}$$
Frobenius norm
$$||w^{[l]}||_ F^2=\sigma_{i=1}^{n^{[l-1]}}\sigma_{j=1}^{n^{[l]}}(w_{ij}^{[l]})^2$$
$$$$
