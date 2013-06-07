matlab
======

>> zast(3,24,12)
ans =
   2.181818181818182
>> r

```c
function [C]=cel(f)
C=(f-32)*5/9;
 ```

>> ftemp=cel(5)
ftemp =-15
   
>> x
x =
  Columns 1 through 10
     1     2     3     4     5     6     7     8     9    10
  Columns 11 through 14
    11    12    13    14
>> 1/x
??? Error using ==> mldivide
Matrix dimensions must agree.
 
>> 1./x
ans =
  Columns 1 through 3
   1.000000000000000   0.500000000000000   0.333333333333333
  Columns 4 through 6
   0.250000000000000   0.200000000000000   0.166666666666667
  Columns 7 through 9
   0.142857142857143   0.125000000000000   0.111111111111111
  Columns 10 through 12
   0.100000000000000   0.090909090909091   0.083333333333333
  Columns 13 through 14
   0.076923076923077   0.071428571428571
```c
function [C]=cel(f)
C=(f-32)*5/9;
```
>> ftemp=15:34;
>> ctemp=cel(ftemp)
ctemp =
  Columns 1 through 3
  -9.444444444444445  -8.888888888888889  -8.333333333333334
  Columns 4 through 6
  -7.777777777777778  -7.222222222222222  -6.666666666666667
  Columns 7 through 9
  -6.111111111111111  -5.555555555555555  -5.000000000000000
  Columns 10 through 12
  -4.444444444444445  -3.888888888888889  -3.333333333333334
  Columns 13 through 15
  -2.777777777777778  -2.222222222222222  -1.666666666666667
  Columns 16 through 18
  -1.111111111111111  -0.555555555555556                   0
  Columns 19 through 20
   0.555555555555556   1.111111111111111
>> ls

.         arka.m    cw1.m     obj.m     stat.mat  zast.m    
..        cel.m     cw2.m     stat.m    wsp.m     
```c
function [x,y]=bieg(r,phi)
x=r*cos(phi);
y=r*sin(phi);
```
 
>> bieg(3.4,pi/3)
ans =
   1.700000000000000
>> [x,y]=bieg(3.4,pi/3)
x =
   1.700000000000000
y =
   2.944486372867091
>> 3^1.3
ans =
   4.171167510947728
>> tan(pi)
ans =
   -1.224646799147353e-016 
>> ezplot('y=sqrt(x)')
>> x=-5:0.1:5;
>> y=sqrt(x);
>> plot(x,y)
Warning: Imaginary parts of complex X and/or Y arguments ignored 
>> plot(x,y,'g')
Warning: Imaginary parts of complex X and/or Y arguments ignored 
>> plot(x,y,'g+')
Warning: Imaginary parts of complex X and/or Y arguments ignored

>> y=tan(x)
>> plot(x,y)
