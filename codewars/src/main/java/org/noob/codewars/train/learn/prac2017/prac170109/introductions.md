Leonardo Fibonacci

A farmer raises rabbits. Each rabbit gives birth to one
rabbit when it turns 2 months old, and then to one
rabbit each month. Rabbits never die, and we ignore
hares. How many rabbits will the farmer have in the
n-th month, if he starts with one newborn rabbit?

Fibonacci numbers are generated by setting F0=0, F1=1, and then using the formula

`Fn = Fn-1 + Fn-2`

Your task is to efficiently calculate the nth element in the Fibonacci sequence and then count the occurrence of each digit in the number returning a list of integer pairs sorted in descending order.

10 ≤ N ≤ 100000

>f(10)=55 returns
>
>a = [(2, 5)]
>
>two occurances of the digit 5
>
> f(10)=55 
>      ^^
>      ||
>
>f(10000) returns 
>
>a = [(254, 3),
>     (228, 2),
>     (217, 6),
>     (217, 0),
>     (202, 5),
>     (199, 1),
>     (198, 7),
>     (197, 8),
>     (194, 4),
>     (184, 9)]