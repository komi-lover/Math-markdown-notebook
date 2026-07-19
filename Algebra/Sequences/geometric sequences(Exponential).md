A Geometric sequence generally is expressed as $\{a_n\}=ar^{n-1}$ where $a$ is the first term and $r$ is the common ratio. Like arithmetic sequences we have $a_1=a$ and $a_{n}=ra_{n-1}\rightarrow \frac{a_n}{a_{n-1}}=r$ and more generally $\frac{a_m}{a_n}=r^{m-n}$. 
#### why exponential?
Set $x=n-1$ to get $a_n=ar^x$ which is similar to the exponential functions $f(x)=a(b)^x$. ![[Exponential sequence.jpg]] Picture above is an example of $\{1\cdot 2^{n-1}\}$ which lays on the curve $y=(0.5)\cdot 2^x$.
#### general formulas:
###### 1. $\frac{a_m}{a_n}=r^{m-n}$
$\frac{a_m}{a_n}=\frac{ar^{m-1}}{ar^{n-1}}=r^{m-n}$
###### 2. $S_n=a_1+a_2+\cdots+a_n=\frac{a(r^n-1)}{r-1}$ 
$rS_n=a_2+a_3+\cdots+a_{n+1}\rightarrow$
$rS_n-S_n=a_{n+1}-a_1=a(r^n-1)\rightarrow S_n=\frac{a(r^n-1)}{r-1}$ 
###### 3.$S_{m,n}=a_n+a_{n+1}+\cdots+a_m=\frac{a(r^m-r^{n-1})}{r-1}$
$S_{m,n}=\sum_{i=n}^{m} a_i=\sum_{i=1}^{m} a_i-\sum_{j=1}^{n-1} a_i=$
$\frac{a(r^m-1)}{r-1}-\frac{a(r^{n-1}-1)}{r-1}=\frac{a}{r-1}\cdot[(r^m-1)-(r^{n-1}-1)]$.
###### 4. $a_m=ta_n\rightarrow t=r^{m-n}$
###### 5. If $b=\frac{a+c}{2}$ then $(a_b)^2=a_a\cdot a_c$









