## Niech $\mathbb{A}=\:(A, a_1, a_2, ..., a_m,  f_1,  f_2, ..., f_n)$ będzie [[Algebra (algebra ogólna)|algebrą]].
## Niech $\equiv$ będzie [[Relacje równoważności|relacją równoważności]] w zbiorze $A$.
## Powiemy, że $k$-argumentowe działanie f w zbiorze $A$ jest **zgodne z relacją $\equiv$** jeśli  dla dowolnych elementów $x_1,x_2,...,x_k, y_1,y_2,...,y_k \in A$ zachodzi $(x_1 \equiv y_1 \wedge ... \wedge x_k \equiv y_k) \implies f(x_1,x_2,...,x_k) \equiv f(y_1,y_2,...,y_k)$
## Relację równoważności $\equiv$ nazywamy **kongurencją w algebrze** lub **kongurencją algebry** jeśli wszystkie działania $f_1, f_2, ..., f_k$ są zgodne z relacją $\equiv$

## **Przykłady**:
### (1) Niech $n \in \mathbb{N}_+$ i $\equiv_n$ będzie relacją równoważności w zbiorze $\mathbb{Z}$: $l \equiv_n m \iff$liczby $l$ oraz $m$ mają taką samą resztę z dzielenia przez $n$. Wówczas $\equiv_n$ (relacja przystawania modulo) jest kongurencją w grupie $(\mathbb{Z},0,+)$ i w pierścieniu $(\mathbb{Z},0,1,+,\cdot)$
### (2) Niech $\equiv$ będzie relacją w zbiorze $\mathcal{P}(\mathbb{N})$: $X \equiv Y \iff X \dot-Y<|\mathbb{N}|$. Wówczas $\equiv$ jest relacją równoważności oraz kongurencji w [[Pierścień zbiorów|pierścieniu zbiorów]] $(\mathcal{P}(\mathbb{N}),\emptyset,X, \dot -, \cap)$. 
### (3) Niech relacja równoważności $\equiv$ będzie kongurencją w grupie $\mathbb{G} = (G,e, \circ)$. Niech $H=[e]$ będzie [[Klasa równoważności|klasą abstrakcji]] elementu neutralnego $e$ grupy $\mathbb{G}$. Wówczas $H$ ma własności:
#### (a) $e \in H$
#### (b) Jeśli $a \in H$ i  $b \in H$ to  $a \circ b \in H$
#### (c) Jeśli $a \in H$ to  $a^{-1} \in H$
#### (d) Jeśli  $b \in H$ i  $a \in H$ to  $b  \circ a \circ b^{-1} \in H$
### Podzbiór $H \subseteq G$ spełniający (a-c) nazywamy **podgrupą grupy $G$**, czyli grupą której elementem neutralnym jest $e$, działaniem  jest $\circ|_{H \times H}$. 
### Podgrupa spełniająca również (d) jest nazywana **dzielnikiem normalnym grupy $G$** lub **podgrupą  normalną grupy $G$** 
### Dla dowolnego $b \in G$  przyjmijmy oznaczenia $bH := \{b \circ a: a\in G\}$ oraz $Hb := \{a \circ b: a\in G\}$  
### Teraz (d) można przeformułować w (e): 
#### (e) dla każdego $b \in G$, $bH = Hb$
### Zbiory postaci $bH$ nazywane są **warstwami podgrupy $H$ w grupie $G$**.
### Okazuje się, że zbiór ilorazowy $G/\equiv$ jest rodziną wszystkich warstw podgrupy $H$:
#### (f) $G/\equiv = \{bH:b\in G\}$
###  Warstwy podgrupy $H$ to warstwy odwzorowania $b \mapsto [b]$ ze zbioru $G$ na zbiór $G/\equiv$.
### Każda kongurencja wyznacza wzajemnie jednoznacznie jej dzielnik normalny.