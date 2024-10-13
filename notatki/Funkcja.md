## **Funkcja** to dowolny zbiór zawierający wyłącznie pary uporządkowane, do którego nie należą żadne dwie pary zawierające ten sam poprzednik i różne następniki. $f$ jest funkcją gdy: $\forall z \in f\:\exists y\: \exists x: z=(x,y)$ oraz $\forall x\: \forall y_1\: \forall y_2 \:(((x,y_1) \in f \wedge (x,y_2)) \in f \implies y_1=y_2)$
## $f$ nie jest funkcją jeśli zawiera przynajmniej 1 element który nie jest parą oraz jeśli zawiera dwie różne pary o tym samym poprzedniku, zatem istnieje **funkcja pusta**: $\emptyset$.
## **Dziedzina** to zbiór $D_f = \{x:\exists y\:(x,y) \in f\}$
## Jeśli $A$ jest podzbiorem $D_f$ to **obrazem zbioru $A$** jest zbiór $f(A)=\{y:\exists{a\in A}(a,y)\in f\}$ 
## Jeśli $B$ jest podzbiorem $f(D_f)$  to **przeciwobrazem** jest zbiór $f^{-1}(B)=\{x\in D_f\:\exists_{b\in B}:(x,b)\in f\}$ 
## **Zbiór wartości** to zbiór $f(D_f)=\{y:\exists x:(x,y) \in f\}$
## **Przeciwdziedzina** to dowolny nadzbiór zbioru wartości: $R_f \supseteq f(D_f)$
## Zatem funkcja jest podzbiorem [[Iloczyn kartezjański|iloczynu kartezjańskiego]] ([[Relacja|relacją]]) dziedziny i przeciwdziedziny $f\subseteq D_f\times R_f$. Przy definiowaniu funkcji używamy oznaczenia $f:D_f\to R_f$, by podkreślić istotę dziedziny i przeciwdziedziny.
## Dla dowolnych funkcji $f$ i $g$: $f=g \iff (D_f=D_g \wedge \forall x\: f(x)=g(x))$
