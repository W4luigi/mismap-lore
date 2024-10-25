# 1.  Pochodna [[Funkcja rzeczywista jednej zmiennej|funkcji rzeczywistej jednej zmiennej]]
## Niech $A\subseteq\mathbb{R}$, $f:A\to\mathbb{R}$, $a\in A$ będzie [[Punkt skupienia|punktem skupienia]] zbioru $A$. 
## Powiemy, że $f$ jest  **różniczkowalna** w $a$ wtedy i tylko wtedy, gdy istnieje skończona granica [[Iloraz różnicowy|ilorazu różnicowego]] $f$, czyli **pochodna funkcji w punkcie**: $$\lim_{h\to0}\frac{f(a+h)-f(a)}{h}=\lim_{x\to a}\frac{f(x)-f(a)}{x-a}:=f'(a)$$

## By odróżnić granice nieskończone od ich braku, można mówić o **pochodnych nieskończonych** w danym punkcie. Interpretacja geometryczna takiego faktu jest taka, że styczna do wykresu funkcji jest pionowa.
## [[Twierdzenia o pochodnej jednej zmiennej]]
# 2.  Pochodna cząstkowa [[Funkcja rzeczywista wielu zmiennych|funkcji rzeczywistej wielu zmiennych]]
## Niech $A\subseteq\mathbb{R}^n$ będzie [[Zbiór otwarty|zbiorem otwartym]], $f:A\to\mathbb{R}^m$, $a=(a_1,\dots,a_n)\in A$, $e_i$ to $i$-ty wektor bazy standardowej, tj. $e_i=(\underbrace{0,\dots,0}_{i-1},1,\underbrace{0,\dots,0}_{n-i})$
## Powiemy, że funkcja $f$ ma **pochodną cząstkową** w punkcie $a$ względem zmiennej $x_i$ wtedy i tylko wtedy, gdy [[Funkcja rzeczywista jednej zmiennej|funkcja rzeczywista jednej zmiennej]] $F_i(t)=f(a_1,\dots,a_{i-1},t,a_{i+1},\dots,a_n)$ ma pochodną w punkcie $a_i$, gdzie dobieramy $\delta>0$ tak, by odcinek $(a-\delta e_i,a+\delta e_i)\in A$. Przyjmujemy $$\frac{\partial f}{\partial x_i}(a)=F'_i(a_i)=\lim_{h\to0}\frac{f(a+he_i)-f(a)}{h}$$

# 3.  Pochodna kierunkowa funkcji rzeczywistej wielu zmiennych
## Niech $A\subseteq\mathbb{R}^n$ będzie [[Zbiór otwarty|zbiorem otwartym]], $f:A\to\mathbb{R}^m$, $a=(a_1,\dots,a_n)\in A$
## Powiemy, że funkcja $f$ ma **pochodną cząstkową** w punkcie $a$ względem wektora $v\in\mathbb{R}^n\backslash\{0\}$ wtedy i tylko wtedy, gdy  [[Funkcja rzeczywista jednej zmiennej|funkcja rzeczywista jednej zmiennej]] $F_v:(-\delta,\delta)\to\mathbb{R}^m$ (gdzie dobieramy $\delta>0$ tak, by odcinek $(a-\delta v,a+\delta v)\in A$), $F_v(t)=f(a+tv)$ ma pochodną w zerze. Przyjmujemy $$\frac{\partial f}{\partial v}(a)=(F_v)'(a)=\lim_{h\to0}\frac{f(a+hv)-f(a)}{h}$$ **Obserwacja**: pochodna kierunkowa względem $e_i$ to pochodna cząstkowa względem $i$-tej zmiennej.
# 4.  Różniczkowalność funkcji rzeczywistej wielu zmiennych.
## Niech $A\subseteq\mathbb{R}^n$ będzie [[Zbiór otwarty|zbiorem otwartym]], $f:A\to\mathbb{R}^m$, $a=(a_1,\dots,a_n)\in A$
## Mówimy, że funkcja $f$ jest różniczkowalna w punkcie $a$ wtedy i tylko wtedy, gdy istnieje przekształcenie liniowe $A:\mathbb{R}^n\to\mathbb{R}^m$, że $$\lim_{||h||\to0}\frac{||f(a+h)-f(a)-Ah||}{||h||}=0$$ W takim wypadku, $A$ nazywamy **różniczką**,**pochodną** lub **różniczką zupełną** w punkcie $a$ i oznaczamy $Df(a)$ lub $f'(a)$