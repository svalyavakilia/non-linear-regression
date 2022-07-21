# Non-linear regression for data modeling 📈

Provide data and try to model it with non-linear regression!

This program mounts to a Google Drive and, for a provided path on your disc, creates a non-linear model.

User should additionally provide the power of the model.
The higher the power is, the potentially more accurate the model is.
However, the time required to provide calculation grows, too.

The program has been written in Python in Google Colab environment.

Among the libraries are _Numpy_ and _Scikit-learn_.

---

The provided file should be in format:

$x_0$ $y_0$

$x_1$ $y_1$

$x_2$ $y_2$

...

$x_{n-2}$ $y_{n-2}$

$x_{n-1}$ $y_{n-1}$

$x_n$ $y_n$

---

![image](https://user-images.githubusercontent.com/70007684/180235125-ead40f0b-83a1-47e4-90d8-b2a53f5644a6.png)

Here, the power of the model is 4.

Yellow stars: training data

Green circles: testing data

Yellow curve: the actual model

Some more models:

![image](https://user-images.githubusercontent.com/70007684/180235709-d4de9622-9c07-4a97-bfd4-874c86e4c48c.png)

The power here is 2. The same data, but with the power 3:

![image](https://user-images.githubusercontent.com/70007684/180235861-36bcbc3d-3553-4c60-b2ec-08d79cf8c099.png)

Another model, power 3:

![image](https://user-images.githubusercontent.com/70007684/180237474-bd1049a3-fdb7-4722-9878-f951df084faa.png)

The same model, power 6:

![image](https://user-images.githubusercontent.com/70007684/180237658-c5d61235-cf35-4b85-a1e3-edbe7668cb4e.png)
