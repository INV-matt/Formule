- $\mathbb N$ numeri naturali
- $\mathbb Z$ numeri interi
- $\mathbb Q$ numeri razionali
- $\mathbb R$ numeri reali

# Insiemi reali
È definito **maggiorante** di $A \subset \mathbb R$ un qualsiasi $M \in \mathbb R\ |\ \forall a \in A,\ a \le M$.

Analogamente, il **minorante** di A è $m \in \mathbb R\ |\ \forall a \in A,\ a \ge M$.

$A$ è **limitato superiormente** se ammette maggiorante, **limitato inferiormente** se ammette minorante.

$M$ è **massimo** di $A$ se appartiene ad $A$ ed è un suo maggiorante.
$m$ è **minimo** di $A$ se appartiene ad $A$ ed è un suo minorante.

Dato un insieme $A$ limitato superiormente, l'**estremo superiore** di $A$ è il minore dei suoi maggioranti.
Dato un insieme $A$ limitato inferiormente, l'**estremo inferiore** di $A$ è il maggiore dei suoi minoranti.
L'estremo inferiore e superiore di $\emptyset$ sono rispettivamente $+\infty$ e $-\infty$.

## Teorema di Dedekind

$$A \subset \mathbb R \implies \exists\ \text{Sup}\ A,\ \text{Inf}\ A$$

## Intervalli
Dati $a, b \in \mathbb R$

$$\begin{align}
& (a, b) = \{x \in \mathbb R\ |\ a<x<b\} \\
& [a, b] = \{x \in \mathbb R\ |\ a \le x \le b\} \\
& ( -\infty, +\infty ) = \mathbb R
\end{align}$$


Dato $A = (a, b)$, l'ampiezza di $A$ è $b-a$ e il raggio $(b-a)/2$.

## Intorni
Dato $a \in \mathbb R$, un intervallo $I$ di $a$ è un qualsiasi intervallo aperto contenente a.
L'intersezione di due intorni di un numero è ancora un intorno del numero stesso.

$x \in \mathbb R$ è **punto di accumulazione** per $A \subset \mathbb R$ se $\forall I(x)\ \exists a \in A\ |\ a \in I(x) \land a\neq x$.
L'insieme di tutti i punti di accumulazione per un insieme è il derivato di quell'insieme.

## Teorema di Bolzano-Weierstrass
Ogni insieme infinito e limitato ammette almeno un punto di accumulazione.