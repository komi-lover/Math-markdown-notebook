The general form of a Quadratic sequence is usually expressed as $a_n=an^2+bn+c$.
To obtain information about it, it's best to have an example sequence, to simplify finding patterns.

Starting with something simple like $a=1,b=2,c=1\rightarrow a_n=n²+2n+1$
Now the sequence is $\{a_n\}=4,9,16,25,\cdots$ 
Notice that if we introduce the sub-sequence $\{b_n\}=\{a_{n+1}-a_n\}$ we get $b_{n+1}-b_n=2$ meaning ${b_n}$ is linear. Let's try to find $b_n$ using $a_n$.$b_n=a_{n+1}-a_n=(n+1)^2+2(n+1)+1-(n²+2n+1)$$=n^2+2n+1+2n+2+1-n^2-2n-1$$=2n+3$
We could also use $\{b_n\}=5,7,9,\cdots$ which would give us the same result. 

More generally we find out for each $a_n=an^2+bn+c$ the sub sequence $b_n=a_{n+1}-a_n$ is linear. 
Notice $b_n=2an+b+1=2a(n-1)+b+1-2a$ meaning the common difference of $b_n$ is $2a$ resulting that $a_n=(\frac{b_{m+1}-b_m}{2})n^2+bn+c$ for any $m∈\mathbb{N}$. So to find $a_n$ we usually need at least three terms, assuming three terms are $a_p=x,a_q=y,a_r=z$ we either should solve the system below $$\begin{gathered}  1.\space ap^2+bp+c=x \\ 2.\space aq^2+bq+c=y \\ 3.\space ar²+br+c=z \end{gathered}$$ for $a,b$ and $c$ or find the value of $\frac{(b_{m+1}-b_m)}{2}=t$ and solve the system below $$\begin{gathered} tp^2+bp+c=x \\ tq^2+bq+c=y \end{gathered}$$ for $b$ and $c$.(notice we picked first and second equations, but after finding leading coefficient $a$ we could have used any pairs.)