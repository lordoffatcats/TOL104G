# Föll
Föll eru varpanir úr fromengi $X$ yfir í bakmengi $Y$. 

### Dæmi: Tákna má fall $f$ frá $\mathbb{R}$ í $\mathbb{R}$ sem: $f:\mathbb{R}\to \mathbb{R}$.

## Graf falls
Graf falls er mengi af öllum pörum $(x,y) | y=f(x)$.
![[Mynd2.png]]

## Einhalla föll (*monotonic*)
Einhalla föll eru vaxandi eða minnkandi.

Fall $f$ er vaxandi ef $f(x_{2})\geq f(x_{1})$ fyrir öll $x_2\geq x_1$.
Fall $f$ er minnkandi ef $f(x_{2})\leq f(x_{1})$ fyrir öll $x_2\geq x_1$.

Ef $f(x_{2})>f(x_{1})$ fyrir öll $x_{2} \geq x_{1}$, þá er $f$ stranglega vaxandi.
Ef $f(x_{2})<f(x_{1})$ fyrir öll $x_{2} \geq x_{1}$, þá er $f$ stranglega minnkandi.

## Samsetning falla
Ef $f$ og $g$ eru föll frá $A\to \mathbb{R}$, þá er $f+g$ líka fall frá $A\to \mathbb{R}$, skilgreint sem: $(f+g)(x)=f(x)+g(x)$. Á sama hátt má reikna $(f-g)$, $(f \cdot g)$ og $(f/g)$.

## Andhverf föll
Ef $f:X\to Y$ er eintækt/gagntækt fall, þá er $f^{-1}:Y\to X$, svo $f^{-1}(f(x))=x$ og $f(f^{-1}(x))=x$
![[Mynd1.png]]

# Runur
Runur eru föll $\mathbb{N}\to S$, oftast er $S=\mathbb{R}$ og við erum með runu af tölum.
Runur eru táknaðar með $a_{0},a_{1},a_{2},\dots,a_{n}$ þar sem $a_0=f(0)$, $a_{1}=f(1)$ o.s.f.v. Runur geta verið endanlegar t.d. $5,3,8,7,2,11$ eða óendanlegar t.d. $1,3,5,7,\dots,2n+1$. Oft eru gefnar formúlur fyrir $n$-ta stak í rununni t.d. $a_{n}=2n+2$.

## Mismunaruna (*arithmetic series*)
Mismunarunur eru á forminu $a, a+d, a+2d,\dots,a+md$, svo: $a_n=a_0+nd$

### Dæmi:
Látum $a = 2$, $d=3$, svo runan er: $2,5,8,11$.

## Kvótaruna (*geometric series*)
Kvótarunur eru á forminu $a, ar, ar^2, \dots, ar^n$, svo $a_n=a_0r^n$.

### Dæmi:
Látum $a=2$, $d=3$, svo runan er: $2,6,18,54$.

## Rakningarvensl
Rakningarvensl er runa þar sem $a_{n}$ er fall af $a_{0},a_{1},a_{2},\dots a_{n-1}$ með gefna liði $a_{0},a_{1},a_{2},\dots a_{n_{0}-1}$ þar sem $n_0\leq n$.

### Dæmi er Fibonacci runan:
$a_0=1$, $a_1=1$, $a_n=a_{n-2}+a_{n-1}$, svo runan er: $1,1,2,3,5,8,13,...$. 

### Gullinsnið
Gullinsniðið er skilgreint sem 
$$\lim_{ n \to \infty }\frac{a_{n}}{a_{n-1}} = \frac{1+\sqrt{ 5 }}{2}$$ fyrir Fibonnaci rununa