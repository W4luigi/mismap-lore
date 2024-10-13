
## Rodzinę $\mathcal{F}\subseteq\mathcal{P}(X)$ nazywamy **$\sigma$-ciałem**, jeśli $\mathcal{F}$ jest [[Ciało zbiorów|ciałem podzbiorów]] $X$ oraz dodatkowo jest **przeliczalnie addytywna**, czyli $$\forall_{A_1,A_2,...\in\mathcal{F}}:\bigcup_{j=1}^{\infty}A_j\in\mathcal{F}$$
## **Przykłady**:
### (1) $\mathcal{F}=\mathcal{P}(A)$ jest $\sigma$.
### (2) Niech $X\subseteq{A}$. Wówczas $\mathcal{F} = \{\emptyset,A,X\backslash{A}, X\}$  jest $\sigma$.
### (3) $\mathcal{F} \subseteq\mathcal{P}(\mathbb{N}), \mathcal{F}=\{A\subseteq\mathbb{N}:|A|<\aleph_0 \vee|\mathbb{N}\backslash A|<\aleph_0\}$. Wówczas $\mathcal{F}$ jest ciałem zbiorów, ale nie jest $\sigma$-ciałem: $A_k=\{2,4,...,2k\}\in\mathcal{F}$, ale  $\bigcup_{k=1}^{\infty}A_k=\{2,4,6,...\}$ i $\mathbb{N}\backslash\bigcup_{k=1}^{\infty}A_k=\{1,3,5,...\}$ nie są skończone, zatem $\bigcup_{k=1}^{\infty}A_k\notin\mathcal{F}$
## **Stwierdzenie**: niech $\{\mathcal{F}_i\}_{i\in{}I}$ będzie rodziną ciał ($\sigma$-ciał).  Wówczas $\bigcap_{i\in I}\mathcal{F}_i$ też jest ciałem ($\sigma$-ciałem).
## **Wniosek**: dla każdej rodziny $\mathcal{J}\subseteq\mathcal{P}(X)$ istnieje najmniejsze ciało ($\sigma$-ciało) zawierające $\mathcal{J}$. Nazywamy je **ciałem ($\sigma$-ciałem) generowanym przez $\mathcal{J}$**
