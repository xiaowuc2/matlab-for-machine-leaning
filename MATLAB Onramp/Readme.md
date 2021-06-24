<p align="center">
  <a href="https://www.youtube.com/channel/UCX7oe66V8zyFpAJyMfPL9VA">
    <img src="https://github.com/xiaowuc2/xiaowuc2/blob/master/source/Matlab_Logo.png" alt="MATLAB" width="200" height="200">
  </a>
  <h3 align="center">MATLAB for Machine Learning #Onramp.m</h3>
  <p align="center">
    Variable • Files • Vector & Matrices • Array • Function • Plotting
      <br />
    <br>
  </p>
</p>


[![GitHub](https://img.shields.io/static/v1.svg?label=Collaborators&message=1&color=success&logo=github&style=social)](https://github.com/qxresearch/Simple-Harmonic-Motion/graphs/contributors)
[![YouTube](https://img.shields.io/static/v1.svg?label=YouTube&message=@qxresearch&color=grey&logo=youtube&style=flat&logoColor=white&colorA=critical)](https://www.youtube.com/channel/UCX7oe66V8zyFpAJyMfPL9VA)
[![GitHub followers](https://img.shields.io/github/followers/xiaowuc2?style=social)]("https://github.com/xiaowuc2")
  [![Twitter Follow](https://img.shields.io/twitter/follow/qxresearchx?label=%40qxresearchx&style=social)](https://twitter.com/qxresearchx)
    <img alt="AUR last modified" src="https://img.shields.io/aur/last-modified/google-chrome">
    [![MATLAB](https://github.com/mathworks/Database-Explorer-for-IIASA/workflows/MATLAB/badge.svg)](https://github.com/mathworks/Database-Explorer-for-IIASA/actions?query=workflow%3AMATLAB)
 

### 🗺️ What's in the Repository?


This repository is essence of Matlab for getting started with Machine Learning. For each course there is: 
1. A `md` which is the note 
2. A `.m` file which is source code

Just go throuh the readme.md files everything will be clear in one shot. From source code file you can copy the whole thing and paste it on [Octave Online](https://octave-online.net) to test. If you ruminate about the code, there are significant difference from Python.

#### Table of Contents:

1. [2.1 Entering Command 💡](https://github.com/xiaowuc2/matlab-for-machine-leaning/tree/main/MATLAB%20Onramp#21-entering-command-)
2. [2.2 Naming Variables](https://github.com/xiaowuc2/matlab-for-machine-leaning/tree/main/MATLAB%20Onramp#22-naming-variables-)
3. [2.3 Saving and Loading Variables](https://github.com/xiaowuc2/matlab-for-machine-leaning/tree/main/MATLAB%20Onramp#23-saving-and-loading-variables-)
4. [2.4 Using Built-in Functions and Constants](https://github.com/xiaowuc2/matlab-for-machine-leaning/tree/main/MATLAB%20Onramp#24-using-built-in-functions-and-constants-)
5. []()
6. []()

#### Practice here : 
#mathworks Course : [MATLAB Onramp](https://matlabacademy.mathworks.com/R2021a/portal.html?course=gettingstarted)

--------------

<br>
</br>

### 2.1 Entering Command 💡

\>> 3*5

ans =

    15

\>> m = 3*5

m =

    15

\>> m = m + 1

m =

    16

\>> y = m/2

y =

     8

\>> k = 8 - 2;

\>> m = 3*k

m =

    18

\>> y

y =

     8

--------------

### 2.2 Naming Variables 💡

\>> a = 8

a =

     8

\>> A = -2

A =

    -2

\>> avgAa = (a+A)/2

avgAa =

     3
--------------
### 2.3 Saving and Loading Variables 💡

\>> save datafile.mat

\>> clear

\>> load datafile.mat

\>> data

```
data =

    3.0000    0.5300    4.0753       NaN
   18.0000    1.7800    6.6678    2.1328
   19.0000    0.8600    1.5177    3.6852
   20.0000    1.6000    3.6375    8.5389
   21.0000    3.0000    4.7243   10.1570
   23.0000    6.1100    9.0698    2.8739
   38.0000    2.5400    5.3002    4.4508
```
   Task 5
\>> clr 

```
```

--------------

### 2.4 Using Built-in Functions and Constants 💡

\>> x = pi/2

x =

    1.5708

\>> y = sin(x)

y =

     1

\>> z = sqrt(-9)
```
z =

   0.0000 + 3.0000i
```  
--------------
### 4.1 Manually Entering Arrays

\>> x = 4 
```
x = 4 #one dimentional array. By default row vector
```

\>> x = [7 9] 
```
7  9 #two dimentional array 1x2
```

\>> x = [7 ; 9]
```
7
9

#column vector, 1x2
```

\>> x = [3  10  5]
```
3  10  5

#row vector 1x3
```

\>> x  = [5 6 7 ; 8 9 10]

```
5  6  7
8  9  10
```

\>> x = [ sqrt(10) pi^2]

```
3.1623  9.8696
```
--------------

### 4.2 Creating Evenly-Spaced Vectors

\>> x = [ 1 2 3]
```
1  2  3 #manually
```
\>> y = 5 : 8
```
5  6  7  8 #last point is inclusive unlike python
```

\>> x = 1 : 0.5 : 5 # start : step : end
```
1.0000  1.5000  2.0000  2.5000  3.0000  3.5000  4.0000  4.5000  5.0000
```
#### linspace function : linspace(first,last,number_of_elements). | Same difference between them

\>> x = linspace(0,1,5)
```
0    0.250    0.500    0.750    1.000
```
#### Transpose Operator : '
\>> x = 1:3;
\>> x = x'
```
1
2
3
```
\>> x = [1 2 3]'
```
1
2
3
```

\>> x = (1:2:5)' #1 to 5, step = 2
```
1
2
3
```

--------------

### 4.3 Array Creation Functions
#### rand(size, classname) function. Creates a size\*size  matrix with random values.
\>> x = rand(2)
```
0.8147    0.1270
0.9058    0.9134

2x2 #and the valuse will change everytime
```
\>> 

