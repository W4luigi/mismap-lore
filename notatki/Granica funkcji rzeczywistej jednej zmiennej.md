## Niech $A\subseteq\mathbb{R}$, $f:A\to\mathbb{R}$ będzie  [[Funkcja rzeczywista jednej zmiennej|funkcja rzeczywistą jednej zmiennej]], $p\in\overline{\mathbb{R}}$ jest [[Punkt skupienia|punktem skupienia]] zbioru $A$.
# 1.  **Definicja Heinego**:
## Powiemy, że funkcja $f$ ma **granicę w punkcie $p$ równą** $g$ wtedy i tylko wtedy, gdy dla każdego [[Ciąg|ciągu]] $(x_n)_{n\in\mathbb{N}}\subseteq A\backslash\{p\}$ [[Zbieżność|zbieżnego]] do $p$, granica $\lim_{n\to\infty}f(x_n)$ istnieje i jest równa $g$.
##  Powiemy, że $f$ ma w $p$ **granicę lewostronną (prawostronną)** $\lim_{x\to p^-}f(x)=g$ ($\lim_{x\to p^+}f(x)=g$), gdy ciąg $(x_n)_{n\in\mathbb{N}}\subseteq A\backslash\{p\}$ jest obłożony warunkiem $\forall{n\in\mathbb{N}}:x_n<p$ ($x_n>p$) i zachodzi $\lim_{n\to\infty}f(x_n)=g$
## **Stwierdzenie**: następujące są równoważne:
### (a) $f$ ma w $p$ granicę równą $g$.
### (b) $f$ ma w $p$ obie granice jednostronne i obie są równe $g$. 

# 2. **Definicja Cauchy'ego**:
## Powiemy, że funkcja $f$ ma **granicę w punkcie $p$ równą** $g$ wtedy i tylko wtedy, gdy:
### (i) Przypadek $g,p\in\mathbb{R}$: $\forall{\epsilon>0}:\exists{\delta>0}:(0<|x-p|<\delta \wedge x\in A) \implies |f(x)-a|<\epsilon$
### (ii) Przypadek $p\in\mathbb{R}$, $g=\pm\infty$ (*granica niewłaściwa w punkcie prostej*): $\forall{M>0}:\exists{\delta>0}:(0<|x-p|<\delta\wedge x\in A)\implies \pm f(x)>M$
### (iii) Przypadek $p=\pm\infty$, $g\in\mathbb{R}$  (*granica właściwa w nieskończoności*): $\forall{\epsilon>0}:\exists{T>0}:(\pm x>T\wedge x\in A)\implies |f(x)-a|<\epsilon$
### (iv) Przypadek $p=\pm\infty$, $g=\pm\infty$ (*granica niewłaściwa w nieskończoności*):  $\forall{M>0}:\exists{T>0}:(\pm x>T\wedge x\in A)\implies \pm f(x)>M$

## Obie definicje są równoważne. Implikacja definicji Cauchy'ego do definicji Heinego wymaga [[Aksjomaty ZFC|aksjomatu wyboru]].
