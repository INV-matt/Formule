# Limiti
- Sia $f:(p, a) \cup(a,q) \to \mathbb R$, diciamo

$$\lim_{ x \to a } f(x) = l \in R$$

se 

$$\forall\varepsilon>0\ \exists I(a)\ |\ |f(x)-l| < \varepsilon\ \forall x \in I(a)$$


- Sia $f:(p, a) \cup(a,q) \to \mathbb R$, diciamo

$$\lim_{ x \to a } f(x) = +\infty$$

se 

$$\forall M>0\ \exists I(a)\ |\ f(x) > M\ \forall x \in I(a)$$



- Sia $f:(p, +\infty) \to \mathbb R$, diciamo

$$\lim_{ x \to +\infty } f(x) = +l \in R$$

se 

$$\forall\varepsilon>0\ \exists I(+\infty)\ |\ |f(x)-l| < \varepsilon\ \forall x \in I(+\infty)$$



- Sia $f:(p, +\infty) \to \mathbb R$, diciamo

$$\lim_{ x \to +\infty } f(x) = +\infty$$

se 

$$\forall M>0\ \exists I(+\infty)\ |\ f(x) > M\ \forall x \in I(+\infty)$$


Se l'intorno è destro (o sinistro), il limite è detto destro( o sinistro)

## Teorema limite da destra e da sinistra
Se esiste il limite, allora esistono il limite destro e sinistro e sono uguali al limite stesso.

Se esistono il limite da destra e da sinistra e sono uguali, allora esiste il limite stesso.

## Teorema della permanenza del segno
$$\lim_{ x \to a }f(x) \neq 0 \implies \exists I(a)\ |\ sgn(f(x)) = sgn(l)\ \forall x \in I(a)$$


$$f(x) > 0\ \forall x \in I(a)\ \land \lim_{ x \to a }f(x) = l \implies l \ge 0 $$

## Teorema del confronto (dei carabinieri)
Siano $f(x), g(x), h(x): D \to \mathbb R\ |\ g(x) \le f(x) \le h(x)\ \forall x \in I(a)$ e che $\lim_{ x \to a }g(x) = \lim_{ x \to a }h(x) = l$.

Allora esiste $\lim_{ x \to a } f(x) = l$


## Funzioni continue
Una funzione $f: D \to \mathbb R$ è detta **continua** in $a$ pt. di accumulazione per $D$, se 

$$\lim_{ x \to a }f(x) = f(a) $$

Un funzione è continua se

$$\lim_{ x \to a } f(x) = f(a)\ \forall a \in D $$

### Punti di discontinuità
Siano $L_{+}=\lim_{ x \to a^+ }f(x)$ e $L_{-}=\lim_{ x \to a^- }f(x)$.
- $L_{+}\neq L_{-} \in \mathbb R$: discontinuità di 1° specie o tipo salto
- $L_{+}\lor L_{-} = \infty$: discontinuità di tipo salto
- $\nexists\ L_{+}\lor \nexists L_{-}$: discontinuità di 2° specie
- $L_{+}= L_{-} \neq f(a)$: discontinuità di 3° specie o eliminabile

### Teorema della permanenza del segno
Sia $f: D\to \mathbb R$. Se $f$ è continua in $a \in D$, allora 
$\exists I(a)\ |\ sgn(f(x))=sgn(f(a))\ \forall x \in I(a)$ se $f(a)\neq 0$

### Teorema di Weierstrass
Se $f: [a,b] \to \mathbb R$ è continua, allora ha massimo e minimo assoluti su $[a, b]$

### Teorema degli zeri
Se $f:(p, q)\to \mathbb R$ è continua e tale che $f(a)*f(b)<0$ con $a, b \in (p, q)$, allora $\exists c \in (a,b) | f(c) =0$


# Derivate

# Integrali

# Equazioni differenziali