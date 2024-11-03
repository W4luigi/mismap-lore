# Aksjomaty Zermelo - Fraenkel - choice:
## (1) **Aksjomat ekstensjonalności**
### $\forall_{A} \:\forall_{B}\: (\forall_{x} \:(x \in A \iff x \in B) \implies A=B)$
## (2) **Aksjomat zbioru pustego**
### $\exists_{X} \:\forall_{y} \: \neg(y \in X)$
## (3) **Aksjomat wyróżnienia**
### $\forall_{p_1}... \forall_{p_n} \forall_{B}  \exists_A \forall_x$ $(x \in A \iff (x \in B \wedge W(x,B,p_1,...,p_n)))$
## (4) **Aksjomat pary**
### $\forall_A \forall_B \exists_C \forall_x \:(x \in C \iff (x = A \vee x= B))$
## (5) **Aksjomat sumy**
###  $\forall_\mathcal{A} \: \exists_U \: \forall_x(x \in U \iff \exists_A \: (x \in A \wedge A \in \mathcal{A}))$
## (6) **Aksjomat zbioru potęgowego**
###  $\forall_X \exists_P \: \forall_Z \:(Z \in P \iff \forall_x \:(x \in Z \implies  x \in X))$
## (7) **Aksjomat nieskończoności**
###  $\exists_X  (\exists_Y \:(Y \in X \wedge \forall_y \neg(y \in Y))$ $\wedge \forall_y(y \in X \implies \exists_z (z \in X \wedge \forall_x$ $(x \in z \iff (x \in y \vee x = y)))))$
## (8) **Aksjomat wyboru**
###  $\forall_\mathcal{A} ((\forall_A (A \in \mathcal{A} \implies A \neq \emptyset)$  $\wedge \forall_A \forall_B  (( \forall{A \in \mathcal{A}} \wedge B \in  \mathcal{A} \wedge A \neq B) \implies$ $\neg(\exists_x (x \in A \wedge x \in B)))$ $\implies \exists_S \forall_A (A \in \mathcal{A} \implies \exists!_y (y \in S \wedge y \in A)))$
## (9) **Aksjomaty zastępowania**
###  $\forall_{p_1} ... \forall_{p_n} \forall_X (\forall_x \exists!_{y} \Phi(x,y,X,p_1,...,p_n)$ $\implies \exists_Y \forall_y (y\in Y \iff \exists_x (x \in X \wedge \Phi(x,y,X,p_1,...,p_n))))$
## (10) **Aksjomat regularności (ufundowania)**
###  $\forall_X \:(X \neq \emptyset \implies (\exists_y \: (y \in X \wedge \neg(\exists_z \:(z \in X \wedge z \in y))))$