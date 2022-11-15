/*
  CEC22 Test Function Suite for Single Objective Bound Constrained Numerical Optimization 
 

*/

The test functions are as follows for different case
1) cec22_test_func(double *, double *,int,int,int);
Example:
cec22_test_func(x, f, dimension,population_size,func_num);

where test_func according to case.

main.cpp is an example function about how to use test_func.cpp


#include <WINDOWS.H>    
#include <stdio.h>
#include <math.h>
#include <malloc.h>
void test_func(double *, double *,int,int,int);
double *OShift,*M,*y,*z,*x_bound;
int ini_flag=0,n_flag,func_flag;
void main()
{
...
}

lshade algorithm has been used for example.

For Linux Users:
Please  change %xx in fscanf and fprintf and do use "WINDOWS.H". 
