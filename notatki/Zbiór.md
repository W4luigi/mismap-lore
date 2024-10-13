# **Zbiór** $\{\}$ i **relacja należenia** $\in$ są pojęciami pierwotnymi w teorii zbiorów. Klasycznym zestawem aksjomatów teorii zbiorów są [[Aksjomaty ZFC|aksjomaty ZFC]].

## **Wstęp**
### (1) **Relacja równości**: $\forall_{A,B}:(A=B\iff{\forall_{x}:(x\in{A}\iff{x\in{B}})})$
### (2) **Schemat definiowania przez wyróżnienie:** *by uniknąć paradoksów, np. $A = \{x:W(x)\}$ może nie zawsze tworzyć zbiór: własność $W(x):=$"nie jest swoim własnym elementem" jest wyrażalna w języku [[Teoria pierwszego rzędu|teorii pierwszego rzędu]], ale prowadzi do sprzeczności: $B$ jednocześnie *jest* i *nie jest* swoim własnym elementem. Zatem, by uniknąć sprzeczności, poprawny **schemat definiowania przez wyróżnienie** ma postać: $A=\{x\in{B}:W(x)\}$.
### (3) **Istnienie pary uporządkowanej**: *$(a,b)$ jest parą uporządkowaną z **poprzednikiem** $a$ i **następnikiem** $b$. Wyróżniona konstrukcja: $(a,b)=\{a,\{a,b\}\}$. Z pary konstruuje się **trójkę uporządkowaną**$(a,b,c)=(a,(b,c))$, **czwórkę uporządkowaną** $(a,b,c,d)=(a,(b,c,d))$, i tak dalej.*
## **Operacje na zbiorach**:
### (i) **Suma zbiorów**: $A\cup{}B = \{x:x\in{}A\vee{}x\in{}B\}$
### (ii) **Iloczyn, przecięcie, część wspólna zbiorów**: $A\cap{}B = \{x:x\in{}A\wedge{}x\in{}B\}$
### (iii) **Zbiór potęgowy**: $\mathcal{P}(A) = \{x: x\subseteq A\}$
### (iv) **Różnica zbiorów**: $x \in A \backslash B \iff x \in A \wedge x \notin B$
### (v) **Różnica symetryczna**: $A \ominus B = (A \backslash B) \cup (B \backslash A) = (A \cup B) \backslash (A \cap B)$
### (vi) **Suma rodziny zbiorów**: $\bigcup\mathcal{A} = \{x:\exists_{A\in\mathcal{A}}:x\in{}A\}$
### (vii) **Przecięcie rodziny zbiorów**:  $\bigcup\mathcal{A} = \{x:\forall_{A\in\mathcal{A}}:x\in{}A\}$
### (viii) **Iloczyn kartezjański zbiorów**: $A\times{}B = \{(a,b):a\in{}A\wedge{}b\in{}B\}$, $A\times{}B\times{}C=\{(a,b,c):a\in{}A\wedge{}b\in{}B\wedge{}c\in{}C\}$,$A\times{}B\times{}C{}\times{}D=\{(a,b,c,d):a\in{}A\wedge{}b\in{}B\wedge{}c\in{}C\wedge{}d\in{}D\}$,

## **Prawa rachunku  zbiorów**:
### *Łączności*: $A \cap (B \cap C) = (A \cap B) \cap C$ oraz $A \cup (B \cup C)$
### *Rozdzielności*:  $A \cap (B \cup C) = (A \cap B) \cap (A \cap C)$  oraz $A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$
### *Idempotentności*: $A \cup A = A$ oraz $A\cap A=A$
### *Pochłaniania*:  jeśli $A\subseteq B$ to $A \cup B = B$ oraz $A \cap B=A$
## **Operacje na zbiorach**:
### Zbiór potęgowy: $\mathcal{P}(A) = \{x: x\subseteq A\}$
### Różnica zbiorów: $x \in A \backslash B \iff x \in A \wedge x \notin B$
### Różnica symetryczna: $A \ominus B = (A \backslash B) \cup (B \backslash A) = (A \cup B) \backslash (A \cap B)$
