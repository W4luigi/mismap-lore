## **Intuicja**: 
### (i) Chcemy mierzyć podzbiory $\mathbb{R}^n$, długość podzbiorów $\mathbb{R}$, powierzchnię $\mathbb{R}^2$, objętość $\mathbb{R}^3$, itd. 
### (ii) Chcemy, by np. pole figury w $\mathbb{R}^2$ nie zależało od tego, jak jest położona:
#### Jeśli $\varphi:$$\mathbb{R}^n\to\mathbb{R}^n$ jest [[Izometria|izometrią]], to $pole(A)=pole(\varphi(A))$.
### (iii) Jeśli zbiory $A_1,A_2,\dots,A_n$ są parami rozłączne, to $pole(A_1\cup{}A_2\cup\dots\cup{}A_n) = pole(A_1)+pole(A_2)+\dots+pole(A_n)$
### (iv) $pole$ może przyjmować wartości dodatnie, nieskończone, lub $0$.
####  Zatem $pole$ jest [[Monotoniczność|funkcją monotoniczną]].
### (v) Dzięki temu możemy obliczać pola trójkątów prostokątnych i szacować nimi pola dowolnych trójkątów (składanych z dwóch prostokątnych), a dalej, dowolnych wielokątów (rozbijanych na trójkąty). Potrzebujemy w takim razie przeliczalnej addytywności jeśli $\{A_i\}_{i=1}^{\infty}$ jest rodziną zbiorów rozłącznych, to $pole(\bigcup_{i=1}^{\infty}Ai)=\sum_{i=1}^{\infty}pole(A_i)$.

## Niech w takim razie $\mu:\mathcal{P}(\mathbb{R}^n)\to[0,+\infty]$, spełniającej niezmienniczość ze względu na przesunięcia (ii), przeliczalną addytywność (iii), która zgadza się z pojęciem długości, pola, objętości, itd.
## Okazuje się, że taka funkcja **nie istnieje**.
## **Kontrprzykład**: *[[!!Zbiór Vitaliego]]*