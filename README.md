# Mean-Variance-
## AIM:
To write a program for mean, variance and cross correlation in SCILAB and verify the output.

## EQUIPMENTS NEEDED:
•	Computer with i3 Processor<BR>
•	SCI LAB

## Algorithm
1.	Define	the	Function:	Specify the	function	you	want	to	simulate.	For	example, f(x)=sin⁡(x)f(x) = \sin(x)f(x)=sin(x) or any other function.
2.	Generate Sample Points: Decide on the range and the number of sample points. Generate these sample points within the desired range.
3.	Evaluate the Function: Compute the function values at each of these sample points.
4.	Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the mean and variance of the computed function values.
5.	Display Results: Output the computed mean variance and Cross Correlation

## PROCEDURE
•	Refer Algorithms and write code for the experiment.<BR>
•	Open SCILAB in System<BR>
•	Type your code in New Editor<BR>
•	Save the file<BR>
•	Execute the code<BR>
•	If any Error, correct it in code and execute again<BR>
•	Verify the generated results<BR>

## PROGRAM
```
function X=f(x)
   z=2*(1-x)^2;
   X=x*z;
endfunction 
a=0;
b=1;
EX=intg(a,b,f); 
disp("Mean : ",EX)

function X=g(x)
   z=2*(1-x)^2;
   X=(x^2)*z;
endfunction 
a=0;
b=1;
EX2=intg(a,b,g);
var=EX2-(EX^2);
disp("Variance : ",var);

```

## OUTPUT
<img width="860" height="380" alt="AC-5" src="https://github.com/user-attachments/assets/828cc662-22d1-46d8-acdb-513eb943c1fe" />


## RESULT
Thus the mean and variance are executed in Scilab and output is verified



