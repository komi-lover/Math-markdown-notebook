#### General form:
 $\{a_n\}=\{a+d(n-1)\}$ is the general formula for an arithmetic sequence, where $a$ is the first term and $d$ is common difference. ![[{2n}.jpg]]
 Picture above is a geometric shape of the sequence.
 In any arithmetic sequence we have $a_1=a$ and $a_{n+1}-a_{n}=d$. Proving these is directly possible using substitution $a_n=a+d(n-1)$. 
#### Why linear?
   Rearranging the formula $a+d(n-1)=$$a+dn-d$  and substituting $b=a-d$, we have $\{a_n\}=dn+b$ which is similar to linear equations $ax+b=y$, resulting that arithmetic sequence points lay on a line.
 ![[Example of linear sequence.jpg]]
Picture above shows that all points lay on the same line.
#### general rules
Assuming $a_n=a+d(n-1)$, $n,m∈\mathbb{N}$ and $m>n$
1. $a_{m}-a_n=(m-n)d$ 
2. $S_n=\sum_{i=1}^{n} a_i=a_1+a_2+\cdots+a_n=\frac{n}{2}(a_1+a_n)$
3. $S_{n,m}=\sum_{i=n}^{m} a_i=a_{n}+a_{n+1}+\cdots+a_{m}=$
   $=(a_1+a_2+\cdots+a_{m})-(a_1+a_2+\cdots+a_{n-1})$
   $=\frac{m}{2}(a_1+a_m)-\frac{n-1}{2}(a_1+a_{n-1})$ 
4. If $a_{m}=a_n+b$ then $b=(m-n)d$
5. If $r=\frac{p+q}{2}$ then $a_r=\frac{a_p+a_q}{2}$
#### Problems And Examples:
 Below are some cases with examples of solving
 1. ##### Example 1:
     if $a_3=9$ and $a_5=15$, find $a_{15}$. Using formulas above we get $d=\frac{a_5-a_3}{5-3}=\frac{6}{2}=3 \rightarrow 9=a+3(3-1)$ $\rightarrow a=3 \rightarrow a_{15}=3+3(15-1)=45$
 2. ##### Example 2: 
    Given $a_n=5-2(n-1)$ find $A_{n,m}=\sum_{i=n}^{m} 2a_i$
    To find it we use the formula $S_{n,m}=\frac{m}{2}(a_1+a_m)-\frac{n-1}{2}(a_1+a_{n-1})$
    $A_{n,m}=2S_{n,m}=m(12-2m)-(n-1)(14-2n)$
    $=12-2m^2+2n^2-16n+14$
    $=2n^2-2m^2-16n+26$
 3. ##### Example 3:
    If $5x+7,3x-1,2x+3$ are the consecutive terms of an arithmetic sequence, what's $x$?
     Using the rule $a_{n+1}-a_n=d$ we get:
     $(2x+3)-(3x-1)=(3x-1)-(5x+7)=d$
     $\rightarrow -x+4=-2x-8\rightarrow x=-12$
     Also we could use the fact $a_r=\frac{a_p+a_q}{2}$ if $r=\frac{p+q}{2}$
