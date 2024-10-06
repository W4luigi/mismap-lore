## (1) Aksjomat ekstensjonalności
### $\forall A \:\forall B\: (\forall x \:(x \in A \iff x \in B) \implies A=B)$
## (2) Aksjomat zbioru pustego
### $\exists X \:\forall y \: \neg(y \in X)$
## (3) Aksjomat wyróżnienia
### $\forall p_1\; ... \forall p_n \: \forall B \: \exists A \:\forall x \:(x \in A \iff (x \in B \wedge W(x,B,p_1,...,p_n)))$
## (4) Aksjomat pary
### $\forall  A \:\forall B \:\exists C \:\forall x \:(x \in C \iff (x = A \vee x= B))$
## (5) Aksjomat sumy
###  $\forall \mathcal{A} \: \exists U \: \forall x\:(x \in U \iff \exists A \: (x \in A \wedge A \in \mathcal{A}))$
## (6) Aksjomat zbioru potęgowego
###  $\forall X\: \exists P \: \forall Z \:(Z \in P \iff \forall x \:(x \in Z \implies  x \in X))$
## (7) Aksjomat nieskończoności
###  $\exists X \: (\exists Y \:(Y \in X \wedge \forall y \neg(y \in Y))$ $\wedge \forall y \:(y \in X \implies \exists z \:(z \in X \wedge \forall x \: (x \in z \iff (x \in y \vee x = y)))))$
## (8) Aksjomat wyboru
###  $\forall \mathcal{A} ((\forall A (A \in \mathcal{A} \implies A \neq \emptyset)$  $\wedge \forall A \forall  B  (( \forall A \in \mathcal{A} \wedge B \in  \mathcal{A} \wedge A \neq B) \implies \neg(\exists x (x \in A \wedge x \in B)))$ $\implies \exists S \forall A (A \in \mathcal{A} \implies \exists!y (y \in S \wedge y \in A)))$
## (9) Aksjomaty zastępowania
###  $\forall p_1 ... \forall p_n \forall X (\forall x \exists!{y} \:  \Phi(x,y,X,p_1,...,p_n)$ $\implies \exists Y \forall y  (y  \in Y \iff \exists x (x \in X \wedge \Phi(x,y,X,p_1,...,p_n))))$
## (10) Aksjomat regularności (ufundowania)
###  $\forall X \:(X \neq \emptyset \implies (\exists y \: (y \in X \wedge \neg(\exists z \:(z \in X \wedge z \in y))))$