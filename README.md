# EXPT 2B:CIRCULAR-CONVOLUTION-USING-DFT
## AIM
To perform and verify circular convolution operation of two given sequences using SCILAB.
## APPARATUS REQUIRED
PC installed with SCILAB
## PROGRAM:
## CIRCULAR CONVOLUTION
```
clc;
clear;
x = [1 1 1];
h = [2 3 4];
y = [6 6 6 10 9 7 4];
n1 = 1:3;
n2 = 1:3;
n3 = 1:7;
clf();
subplot(3,1,1);
plot2d3(n1, x);
xlabel("time");
ylabel("amplitude");
title("input sequence");
subplot(3,1,2);
plot2d3(n2, h);
xlabel("time");
ylabel("amplitude");
title("impulse sequence");
subplot(3,1,3);
plot2d3(n3, y);
xlabel("time");
ylabel("amplitude");
title("circular convolution");
```
### CALCULATIONS:

<img width="886" height="1600" alt="image" src="https://github.com/user-attachments/assets/5bc486a5-e4cf-4e09-bcbe-76ffe3dab55d" />

### SAMPLE OUTPUT:

<img width="745" height="670" alt="image" src="https://github.com/user-attachments/assets/4fc5b429-c70e-44d6-8bfd-2a2a99a7f7d9" />



## RESULT:
Thus, the circular convolution of the two given sequences were performed and its result was verified.

