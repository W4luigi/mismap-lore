## Niech $\mathscr{F}\subseteq 2^X$ będzie [[Ciało zbiorów|ciałem zbiorów]].
## Ciało zbiorów $\mathscr{F}$ nazywamy **$\sigma$-ciałem** wtedy i tylko wtedy, gdy jest **przeliczalnie addytywne**, czyli $\forall A_i \in \mathscr{F}$: $$\bigcup_{j=1}^{\infty}A_j\in\mathscr{F}$$
## **Przykłady**:
### (1) $\mathscr{F}=\mathcal{P}(A)$ jest $\sigma$-ciałem.
### (2) Niech $X\subseteq{A}$. Wówczas $\mathscr{F} = \{\emptyset,A,X\backslash{A}, X\}$  jest $\sigma$-ciałem.
### (3) $\mathscr{F} \subseteq\mathcal{P}(\mathbb{N}), \mathscr{F}=\{A\subseteq\mathbb{N}:|A|<\aleph_0 \vee|\mathbb{N}\backslash A|<\aleph_0\}$. Wówczas $\mathcal{F}$ jest ciałem zbiorów, ale nie jest $\sigma$-ciałem: $A_k=\{2,4,...,2k\}\in\mathcal{F}$, ale  $\bigcup_{k=1}^{\infty}A_k=\{2,4,6,...\}$ i $\mathbb{N}\backslash\bigcup_{k=1}^{\infty}A_k=\{1,3,5,...\}$ nie są skończone, zatem $\bigcup_{k=1}^{\infty}A_k\notin\mathscr{F}$
## **Stwierdzenie**: niech $\{\mathscr{F}_i\}_{i\in{}I}$ będzie rodziną ciał ($\sigma$-ciał).  Wówczas $\bigcap_{i\in I}\mathcal{F}_i$ też jest ciałem ($\sigma$-ciałem).
## **Wniosek**: dla każdej rodziny $\mathcal{J}\subseteq\mathcal{P}(X)$ istnieje najmniejsze ciało ($\sigma$-ciało) zawierające $\mathcal{J}$. Nazywamy je **ciałem ($\sigma$-ciałem) generowanym przez $\mathcal{J}$**
