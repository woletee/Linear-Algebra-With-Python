<font color='purple' size=2.5><i>Updated on Aug 2024</i></font>
![Presentation1](https://user-images.githubusercontent.com/59842360/159695863-678be5bc-d146-4340-9592-003ad93241e1.jpg)
# Lectures of Linear Algebra

These lecture notes are intended for introductory linear algebra courses, suitable for university students, programmers, data analysts, algorithmic traders and etc. 

The lectures notes are loosely based on several textbooks

1. <b><i>Linear Algebra and Its Applications</i></b> by Gilbert Strang 
2. <b><i>Linear Algebra and Its Applications</i></b> by David Lay 
3. <b><i>Introduction to Linear Algebra With Applications</i></b> by DeFranza & Gagliardi
4. <b><i>Linear Algebra With Applications</i></b> by Gareth Willia
5. forked from 
![cover-min](https://user-images.githubusercontent.com/59842360/83939172-64df6c00-a7e3-11ea-80b1-058af696d5a3.png)

However, the crux of the course is not about proving theorems, but to demonstrate the practices and visualization of the concepts. Thus we will not engage in precise deduction or notation, rather we aim to clarify the elusive concepts and thanks to Python/MATLAB, the task is much easier now.

## Prerequisites
Though the lectures are for beginners, it is beneficial that attendants had certain amount of exposure to linear algebra and calculus.

And also the attendee are expected to have basic knowledge (3 days training would be enough) of 
- [x] Python
- [x] NumPy
- [x] Matplotlib
- [x] SymPy

All the codes are written in an <b>intuitive manner</b> rather than efficient or professional coding style, therefore the codes are exceedingly straightforward, I presume barely anyone would have difficulty in understanding the codes.

The notes were written in JupyterLab, the interative plot requires ```ipympl```. To install, type in ```conda install -c conda-forge ipympl``` if you have JupyterLab 3.x. Check <a href='https://github.com/matplotlib/ipympl'><code>ipympl</code>page</a> for more details.

## Environment Setup
I use poetry to management environment, if you happen to use VS code like me, please follow the steps below:
1. In Windows powershell and install poetry ``` (Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python -p```
2. Navigate to ```cd $env:APPDATA\Python\Scripts```, check if poetry being installed.
3. Open a notepad ```notepad $profile``` and set alias for poetry ```Set-Alias poetry "C:\Users\user\AppData\Roaming\Python\Scripts\poetry.exe"``` in notepad, I prefered this way, because sometimes setting env path not working in windows.
4. Reload profile by ```. $profile```.
5. If you are on your personal computer ```Set-ExecutionPolicy RemoteSigned -Scope CurrentUser``` to unstrict your execution policy and choose Y.
6. Resume the default restricted policy for security ```Set-ExecutionPolicy Restricted -Scope CurrentUser```.
7. Now check ```poetry --version```, if you see the version printed, good to go.
8. You choose to use ```poetry update```, or just manage version at your own convenience.

## What to Expect from Notes
These notes will equip you with most needed and basic knowledge for other subjects, such as Data Science, Econometrics, Mathematical Statistics, Financial Engineering, Control Theory and etc., which heavily rely on linear algebra. Please go through the tutorial patiently, you will certainly have a better grasp of the fundamental concepts of linear algebera. Then further step is to study the special matrices and their application with your domain knowledge.  

## Contents

[Chapter 1 - Linear Equation System](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%201%20-%20Linear%20Equation%20System.ipynb)<br>
[Chapter 2 - Basic Matrix Algebra](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%202%20-%20Basic%20Matrix%20Algebra.ipynb)<br>
[Chapter 3 - Determinant](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%203%20-%20Determinant.ipynb)<br>
[Chapter 4 - LU Factorization](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%204%20-%20LU%20Factorization.ipynb)<br>
[Chapter 5 - Vector Addition, Subtraction and Scalar Multiplication](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%205%20-%20Vector%20Addition%2C%20Subtraction%20and%20Scalar%20Multiplication.ipynb)<br>
[Chapter 6 - Linear Combination](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%206%20-%20Linear%20Combination.ipynb)<br>
[Chapter 7 - Linear Independence](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%207%20-%20Linear%20Independence.ipynb)<br>
[Chapter 8 - Vector Space and Subspace](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%208%20-%20Vector%20Space%20and%20Subspace.ipynb)<br>
[Chapter 9 - Basis and Dimension](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%209%20-%20Basis%20and%20Dimension.ipynb)<br>
[Chapter 10 -Null Space vs Col Space, Row Space and Rank](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%2010%20-Null%20Space%20vs%20Col%20Space%2C%20Row%20Space%20and%20Rank.ipynb)<br>
[Chapter 11 - Linear Transformation](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%2011%20-%20Linear%20Transformation.ipynb)<br>
[Chapter 12 - Eigenvalues and Eigenvectors](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%2012%20-%20Eigenvalues%20and%20Eigenvectors.ipynb)<br>
[Chapter 13b - Principal Component Analysis](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%2013b%20-%20Principal%20Component%20Analysis.ipynb)<br>
[Chapter 13a - Diagonalization](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%2013a%20-%20Diagonalization.ipynb)<br>
[Chapter 14 - Applications to Dynamic System](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%2014%20-%20Applications%20to%20Dynamic%20System.ipynb)<br>
[Chapter 15 - Innear Product and Orthogonality](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%2015%20-%20Innear%20Product%20and%20Orthogonality.ipynb)<br>
[Chapter 16 - Gram-Schmidt Process and QR Decomposition](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%2016%20-%20Gram-Schmidt%20Process%20and%20QR%20Decomposition.ipynb)<br>
[Chapter 17 - Symmetric Matrices , Quadratic Form and Cholesky Decomposition](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%2017%20-%20Symmetric%20Matrices%20%2C%20Quadratic%20Form%20and%20Cholesky%20Decomposition.ipynb)<br>
[Chapter 18 - The Singular Value Decomposition](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%2018%20-%20The%20Singular%20Value%20Decomposition.ipynb)<br>
[Chapter 19 - Multivariate Normal Distribution](https://nbviewer.org/github/weijie-chen/Linear-Algebra-With-Python/blob/master/notebooks/Chapter%2019%20-%20Multivariate%20Normal%20Distribution.ipynb)<br>

## Screen Shots Examples
![截图01](https://user-images.githubusercontent.com/59842360/122352881-6b043e80-cf47-11eb-9ca4-8f52c93c0efa.jpg)
![截图03](https://user-images.githubusercontent.com/59842360/122352926-78212d80-cf47-11eb-9bb4-c33e03b7f085.jpg)
![截图00](https://user-images.githubusercontent.com/59842360/122352940-7b1c1e00-cf47-11eb-9f80-e26454d4baaf.jpg)
![截图00](https://user-images.githubusercontent.com/59842360/126001287-9f8de290-3940-4000-b5db-7b12d8b70005.jpg)
![截图01](https://user-images.githubusercontent.com/59842360/126001290-d342db9f-76eb-41ce-98b2-208075bd4640.jpg)
![截图02](https://user-images.githubusercontent.com/59842360/126001291-5cee0e1b-d02b-4912-9d27-65eaaff13178.jpg)
![截图03](https://user-images.githubusercontent.com/59842360/126001463-0b262316-0032-482e-bb0f-1ccbbd3a2835.jpg)
