# [[Pochodna]], [[Różniczkowalność funkcji rzeczywistej wielu zmiennych]]
# **Twierdzenie:**
## Niech $U\subseteq \mathbb{R}^k$, $f:U\to\mathbb{R}^l$, $p\in U$
## Jeżeli $f$ jest różniczkowalna w punkcie $p$, to dla każdego niezerowego wektora $v\in\mathbb{R}^k$ zachodzi: 
### (i) $Df(p)\cdot v=\frac{\partial f}{\partial v}(p)$ *(patrz: [[Pochodna kierunkowa funkcji rzeczywistej wielu zmiennych|Pochodna kierunkowa]])*
### (ii) $Df(p)\cdot e_i=\frac{\partial f}{\partial x_i}(p)$ *(patrz: [[Pochodna cząstkowa funkcji rzeczywistej wielu zmiennych|Pochodna cząstkowa]])*
# **Twierdzenie:**
## Niech $U\subseteq\mathbb{R}^k$ będzie [[Zbiór otwarty|zbiorem otwartym]], $f=(f_1,\dots,f_k):U\to\mathbb{R}^l$, $p=(p_1,\dots,p_l)$. 
## Następujące są równoważne:
### (i) funkcja $f$ jest różniczkowalna w punkcie $p$
### (ii) każda z funkcji $f_i$ jest różniczkowalna w punkcie $p_i$

# **Uwaga: [[Macierz Jacobiego]]**
# **Twierdzenie:**
## Niech $U\subseteq\mathbb{R}^k$, $f:U\to\mathbb{R}^l$, $p\in\mathbb{R}^k,r>0$
## Jeśli wszystkie pochodne cząstkowe $\frac{\partial f}{\partial x_i}$ istnieją na całej [[Kula|kuli]] $B(p,r)$ i są ciągłe w $p$, to $f$ jest różniczkowalna w punkcie $p$. Zachodzi wtedy wzór $$Df(p)\cdot h=\sum^{k}_{i=1}{h_i\frac{\partial f}{\partial x_i}{p}}:h=(h_1,\dots,h_k)\in\mathbb{R}^k$$