# 1. Przypadek [[Funkcja rzeczywista jednej zmiennej|funkcji rzeczywistej jednej zmiennej]]
## Niech $A\subseteq\mathbb{R}, f:A\to\mathbb{R}$, $p\in A$
## Funkcja $f$ jest **ciągła w punkcie** $p$ wtedy i tylko wtedy, gdy
### (i) Punkt $p$ nie jest [[Punkt skupienia|punktem skupienia]] $A$.
### (ii) Punkt $p$ jest [[Punkt skupienia|punktem skupienia]] $A$ i $f$ ma skończoną [[Granica funkcji rzeczywistej jednej zmiennej|granicę]] w punkcie $p$ równą $f(p)$.

# 2. Przypadek [[Funkcja rzeczywista wielu zmiennych|funkcji rzeczywistej wielu zmiennych]]
## Niech $A\subseteq\mathbb{R}^n, f:A\to\mathbb{R}^m, p\in A$
## Funkcja $f$ jest **ciągła w punkcie** $p$ wtedy i tylko wtedy, gdy:
### (Cauchy) $\forall{\epsilon>0}:\exists{\delta>0}:\forall{x\in A}:||x-p||<\delta \implies ||f(x)-a||<\epsilon$
### (Heine) Dla każdego [[Ciąg|ciągu]] $(x_n)_{n\in\mathbb{N}}\subseteq A$ [[Zbieżność|zbieżnego]] do $p$, $\lim_{n\to\infty}f(x_n)=f(p)$.
# Funkcja $f$ jest **ciągła** na $A$, gdy jest ciągła w każdym punkcie $A$.