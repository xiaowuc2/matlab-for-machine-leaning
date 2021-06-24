<p align="center">
  <a href="https://www.youtube.com/channel/UCX7oe66V8zyFpAJyMfPL9VA">
    <img src="https://github.com/xiaowuc2/xiaowuc2/blob/master/source/Matlab_Logo.png" alt="MATLAB" width="200" height="200">
  </a>
  <h3 align="center">MATLAB for Machine Learning #Onramp.m</h3>
  <p align="center">
    Variable • Files • Vector & Matrices • Array • Function • Plotting
  </p>
</p>


[![GitHub](https://img.shields.io/static/v1.svg?label=Collaborators&message=1&color=success&logo=github&style=social)](https://github.com/qxresearch/Simple-Harmonic-Motion/graphs/contributors)
[![YouTube](https://img.shields.io/static/v1.svg?label=YouTube&message=@qxresearch&color=grey&logo=youtube&style=flat&logoColor=white&colorA=critical)](https://www.youtube.com/channel/UCX7oe66V8zyFpAJyMfPL9VA)
[![GitHub followers](https://img.shields.io/github/followers/xiaowuc2?style=social)]("https://github.com/xiaowuc2")
  [![Twitter Follow](https://img.shields.io/twitter/follow/qxresearchx?label=%40qxresearchx&style=social)](https://twitter.com/qxresearchx)
    <img alt="AUR last modified" src="https://img.shields.io/aur/last-modified/google-chrome">
    [![MATLAB](https://github.com/mathworks/Database-Explorer-for-IIASA/workflows/MATLAB/badge.svg)](https://github.com/mathworks/Database-Explorer-for-IIASA/actions?query=workflow%3AMATLAB)
 
<br>
</br>

###  How to use this Repository?


This repository contains the essence of Matlab. If you're interested in Machine Learning and Research then you should deffinetely go through the readme.md file once. This course will give you a clear insight about why we use MATLAB in the first place for Machine Learning.You can run the source codes(.m) on [Octave Online](https://octave-online.net). If you ruminate about the code, there is no significant difference between Python and Matlab, so just dive into it. <br></br>Important and coonfusing topics are matked with `⚠️`

#### 📖 Search Documentation function/operations : [MathWorks/help](https://in.mathworks.com/help/index.html)
#### 📖 Practice & Certification @mathworks : [MATLAB Onramp](https://matlabacademy.mathworks.com/R2021a/portal.html?course=gettingstarted)

--------------

### 🗺️ Table of Contents:

1. [2.1 Entering Command](https://github.com/xiaowuc2/matlab-for-machine-leaning/tree/main/MATLAB%20Onramp#21-entering-command-)
2. [2.2 Naming Variables](https://github.com/xiaowuc2/matlab-for-machine-leaning/tree/main/MATLAB%20Onramp#22-naming-variables-)
3. [2.3 Saving and Loading Variables](https://github.com/xiaowuc2/matlab-for-machine-leaning/tree/main/MATLAB%20Onramp#23-saving-and-loading-variables-)
4. [2.4 Using Built-in Functions and Constants](https://github.com/xiaowuc2/matlab-for-machine-leaning/tree/main/MATLAB%20Onramp#24-using-built-in-functions-and-constants-)
5. []()
6. []()

--------------
<p align="center">
  <h3 align="center">Function Cheat Sheet</h3>
  <p align="center">
    All Built-in Function and Operator Used in This Course
  </p>

|Function & Operator | Work | Example |
|---------|---------|---------|
|`pi` |	The number π|  x = pi/2 |
|`sin()` `cos()`| Trigonometric function| y = sin(x) |
|`NaN` |	Undefined numerical result (not a number)| X = NaN |
|`NaN()` |	Creates a matrix containing `NaN` | X = NaN(3) : will create a 3x3 matix containing `NaN` |
| `zeros()` | Creates a matrix containing `0` | zeros(3) : will create a 3x3 matrix with `0` |
| `ones()` | Creates a matrix containing `1` | ones(2) : will create a 2x2 matrix with `1` |
|	`max()` | Finds out the maximum value in an Array | max(Array1) : will return max value in `Array1` |
| `sqrt()` | Square root of a number | x = sqrt(2) |
| `[` `]` | Creates Matrix | x = [1 2 3] |
| `:` | from to | 1:5 : gives 1 2 3 4 5 |
| `linspace(first,last,number_of_elements)` | from first to last prints `n` with same difference | x = linespace(1,10,5) |
| `end` | `end` of a Matrix . helpts to find row column elements | data(end-1,end) |
| `round` | Roundes up float to integer | round(1.2354) |
| `*` | Matrix Matrix multiplication | A * B |
| `.*` | Element wise multiplication between matrix | A .* B |
| `size` | Array size | s = size(x) |
| `;` | ⚠️ Inside `[` `]` it creates column matrix \| We add this at the end of a line to avoid printing it's value in console | 1. a = [1 2 3 : 4 5 6] 2. y = [ 1 2 3 ]; |
| `randi(imax,size)` | randi(imax) returns a pseudorandom scalar integer between 1 and imax. | r = randi(10,5) : between 1 to 10, 5 elements \| r = randi(10,1,5) : between 1 to 10, 1x5 elements |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|`ans`	| Most recent answer|  |
|`eps`	| Accuracy of floating-point precision|  |
|`i,j`	| The imaginary unit √-1|  |
|`Inf` |	Infinity|  |

You can always refer to the Official Documentation of Matlab as a guide for searching the use of function/operation : [MathWorks/help](https://in.mathworks.com/help/index.html)

--------------
<p align="center">
  <h3 align="center">Commands</h3>
  <p align="center">
    Variable • Built-in Function(math) • Constant
  </p>
</p>

<br>
</br>

### 2.1 Entering Command

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

### 2.2 Naming Variables

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
### 2.3 Saving and Loading Variables

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

### 2.4 Using Built-in Functions and Constants

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
<p align="center">
  <h3 align="center">Vectors and Matrices</h3>
  <p align="center">
    Array • Evenly-Spaced Vectors • Array Creation Function(ones,zeros)
  </p>
</p>

### 4.1 Manually Entering Arrays

\>> x = 4 
```
x = 4 #one dimentional array. By default row vector
```

\>> x = [7 9] 
```
7  9 #two dimentional array 1x2
```

\>> x = [7 ; 9] ⚠️
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

\>> x  = [5 6 7 ; 8 9 10] ⚠️

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
#### Transpose Operator : `'`
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
3
5
```

--------------

### 4.3 Array Creation Functions

#### rand(size, classname) function. Creates a size\*size  matrix with random values if dimention is not mentioned.

\>> x = rand(2)
```
0.8147    0.1270
0.9058    0.9134

2x2 #and the valuse will change everytime
```
\>> x= rand(2,3)
```
0.6324    0.2785    0.9575
0.0975    0.5469    0.9649
```
#### ones function : gives a matrix where all elements are '1' : ones(2,3)
#### zeros function : gives a matix where all elements are '0' : zeros(4,2)

\>> x = ones(2,3)
```
1  1  1
1  1  1
```
\>> x = zerso(6,3)
```
0  0  0  
0  0  0
0  0  0 
0  0  0
0  0  0 
0  0  0
```
--------------
<p align="center">
  <h3 align="center">Indexing and Modifying Arrays</h3>
  <p align="center">
    Array • Extracting Elements @array
  </p>
</p>

### 5.1 Indexing into Arrays
Given `datafile`, let's see what's inside

\>> load datafile

\>> data
```
3.0000 0.5300 4.0753 NaN
18.0000 1.7800 6.6678 3.6852
19.0000 0.8600 1.5177 3.5389
20.0000 1.6000 3.6375 10.1570
21.0000 3.0000 4.7243 10.1570
23.0000 6.1100 9.0698 2.8739
38.0000 2.5400 5.3002 4.4508
```
\>> x = data(6,3)
```
x = 9.0698
```
#### `end` keyword : end of the array. eg. end - 1 , end - 2 

\>> x = data(end,3)
```
5.3002
```
\>> x = data(end-1,3)
```
x = 9.0698
```
--------------

### 5.2 Extracting Multiple Elements

Given `datafile`. Let's see what's in there

\>> load datafile

\>> data
```
3.0000 0.5300 4.0753 NaN
18.0000 1.7800 6.6678 3.6852
19.0000 0.8600 1.5177 3.5389
20.0000 1.6000 3.6375 10.1570
21.0000 3.0000 4.7243 10.1570
23.0000 6.1100 9.0698 2.8739
38.0000 2.5400 5.3002 4.4508
```
#### Colon Operator (:) : All, like python.

Task : print the second column of `data`

\>> density = data(:,2)
```
0.5300
1.7800
0.8600
1.6000
3.0000
6.1100
2.5400
```
Task : prtint the last two columns of `data`

\>> volumes = data(:,end-1:end)
```
4.0753       NaN
6.6678    2.1328
1.5177    3.6852
3.6375    8.5389
4.7243   10.1570
9.0698    2.8739
5.3002    4.4508
```
Task : place the 6th element of `density` in variable `p`

\>>  p = density(6)
```
p = 6.1100
```
Task : place 2nd throught 5th element of `density` in variable `p`

\>> p = density(2:5)
```
1.7800
0.8600
1.6000
3.0000
```
--------------
### 5.3 Changing Values in Arrays

Given `datafile`. Let's see what's in there

\>> load datafile

\>> data
```
3.0000 0.5300 4.0753 NaN
18.0000 1.7800 6.6678 3.6852
19.0000 0.8600 1.5177 3.5389
20.0000 1.6000 3.6375 10.1570
21.0000 3.0000 4.7243 10.1570
23.0000 6.1100 9.0698 2.8739
38.0000 2.5400 5.3002 4.4508
```
Task : create a vector `v2` containing the last column of `data`

\>> v2 = data(:,end)
```
 NaN
2.1328
3.6852
8.5389
10.1570
2.8739
4.4508
```
Task : Change the first element in `v2` from `NaN` to `0.5`

\>> v2(1) = 0.5

\>> v2
```
 0.5000
 2.1328
 3.6852
 8.5389
 10.1570
 2.8739
 4.4508
```

Task : Change the `NaN` in `data`

\>> data(1,end) = 0.5
```
 3.0000    0.5300    4.0753    0.5000
 8.0000    1.7800    6.6678    2.1328
19.0000    0.8600    1.5177    3.6852
20.0000    1.6000    3.6375    8.5389
21.0000    3.0000    4.7243   10.1570
23.0000    6.1100    9.0698    2.8739
38.0000    2.5400    5.3002    4.4508
```
--------------
<p align="center">
  <h3 align="center">Array Calculation</h3>
  <p align="center">
    Addition • Substraction • sqrt() 
</p>
</p>

### 6.1 Performing Array Operations on Vectors

Given `datafile`. Let's see what's in there

\>> load datafile
    
\>> density = data(:,2);

\>> v1 = data(:,3);

\>> v2 = data(:,4);    
    
\>> data
```
3.0000 0.5300 4.0753 NaN
18.0000 1.7800 6.6678 3.6852
19.0000 0.8600 1.5177 3.5389
20.0000 1.6000 3.6375 10.1570
21.0000 3.0000 4.7243 10.1570
23.0000 6.1100 9.0698 2.8739
38.0000 2.5400 5.3002 4.4508
```
Task : Add 1 to each element of `v1` and store the result in a variable named `r`

\>> r = v1 + 1
```
 5.0753
 7.6678
 2.5177
 4.6375
 5.7243
10.0698
 6.3002
```
Task : Create a vector `vs` that is the sum of the vectors `v1` and `v2`

\>> vs = v1 + v2
```
  NaN
 8.8006
 5.2029
12.1764
14.8813
11.9437
 9.7510
```
Task : Create a variable `va` that contains the value `vs` divided by 2 (the average volume)

\>> va = vs / 2
```
  NaN
 4.4003
 2.6014
 6.0882
 7.4406
 5.9718
 4.8755
```
#### max() function. It finds the max in the array
Task : Create a variable `vm` containing the maximum of the `va` vector

\>> vm = max(va)
```
vs = 7.4407
```
Task : Using the `round` function, create a variable named `vr` which contains the rounded average volumes, `va`

\>> vr = round(va)
```
 NaN
  4
  3
  6
  7
  6
  5
```
#### Matrix Multiplication is done by `*` Elementwise multiplication is done by `.*`

Task : Create a variable named `mass` containing the elementwise product of `density` and `va`

\>> mass = density .* va

```
       NaN
    7.8325
    2.2372
    9.7411
   22.3220
   36.4880
   12.3838
```
--------------
<p align="center">
  <h3 align="center">Calling Functions</h3>
  <p align="center">
    Multiple Outputs from Function Calls
  </p>
</p>

### 7.1 Obtaining Multiple Outputs from Function Calls

Given `datafile`. Let's see what's in there

\>> load datafile

\>> v1 = data(:,3);

\>> v2 = data(:,4);    
    
\>> data
```
3.0000 0.5300 4.0753 NaN
18.0000 1.7800 6.6678 3.6852
19.0000 0.8600 1.5177 3.5389
20.0000 1.6000 3.6375 10.1570
21.0000 3.0000 4.7243 10.1570
23.0000 6.1100 9.0698 2.8739
38.0000 2.5400 5.3002 4.4508
```

#### size() function returns size of Array

Task : Create a variable named `dsize` containing the size of the `data` variable

\>> dsize = size(data)
```
7  4
```
Task : Create the variables `dr` and `dc` which respectively contain the number of rows and columns of the variable `data`

\>> [dr,dc] = size(data) ⚠️
```
dr = 7
dc = 4
```

Task : Create the variables `vMax` and `ivMax` containing the maximum value of the `v2` vector and the corresponding index value respectively

\>> [vMax,ivMax] = max(v2)  ⚠️
```
vMax = 10.157
ivMax = 5
```
#### randi() function
randi(imax) returns a pseudorandom scalar integer between 1 and imax.

Task : Create a matrix `x` that Contains random integers in the range from 1 to 20 Has 5 rows Has 7 columns

\>> x = randi(20,5,7)
```
x =

   11    3   10    2   20   20    6
    2    6   18    3   14   14   11
   15    6   12   19   20   10   10
    1   13    3   17   11   12    3
   11    5    4    4   13   11   10
   
   #everytime the numbers will be random integers

```
--------------
<p align="center">
  <h3 align="center">Plotting Data</h3>
  <p align="center">
    Plotting Vectors • Annotating Plots
  </p>
</p>









--------------

### Interesting Facts & Projects @Matlab 

### Facts
```
1. Every Variable in Matlab is an Array(mutable)
2. Indexing starts from 1 unline Python(starts from 0)

```
