# Sortafast

A simple and quick sorting algorithm.

It all started almost six months ago when I went for an interview for internship at Intel.
The interviewer asked me to come up with a sorting algorithm.
I proposed this idea and he told me this is impossible.

Covid-19 pandemic hit and I was stuck at home.
So I made it possible.

First it compares each number to each number.
There's a count for every number and it starts with 0.
Say the first number is n1 and the number that will be compared with it is n2.
If n1 > n2, then n1's count will increase by 1.
Else nothing happens.
After comparing n1 with all the numbers (even n1 itself),
n1 will be placed into a new array at index of (count).
This process will be repeated and the new array will be filled up.

That's it. 
