# Signals-and-Systems-Lab-1
Lab 1 of Signals and Systems

1. Write a MATLAB program that will add all the numbers corresponding to the even
indices of an array. For instance, if the array x was x=[1, 3, 5, 10], then it should
return 13 (= 3 + 10). Use that program to nd the sum of all even integers from 1 to
1000. Write your program so that it is exible. That is, you should be able to invoke
your program from the command window as follows:
>> y=addeven(x)
where x is the input vector, and y is the sum of all the numbers corresponding to the
even indices of x.

2. Can you explain what the following program does:
L=length(x);
for i=1:L
  if x(i) < 0
    x(i)=-1;
  end
end
Can you rewrite this program without using for loops?
