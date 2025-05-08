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

## Teoremi
### Teorema limite da destra e da sinistra
Se esiste il limite, allora esistono il limite destro e sinistro e sono uguali al limite stesso.

Se esistono il limite da destra e da sinistra e sono uguali, allora esiste il limite stesso.

### Teorema della permanenza del segno
$$\lim_{ x \to a }f(x) \neq 0 \implies \exists I(a)\ |\ \text{sgn}(f(x)) = \text{sgn}(l)\ \forall x \in I(a)$$


$$f(x) > 0\ \forall x \in I(a)\ \land \lim_{ x \to a }f(x) = l \implies l \ge 0 $$

### Teorema del confronto (dei carabinieri)
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
$\exists I(a)\ |\ \text{sgn}(f(x))=\text{sgn}(f(a))\ \forall x \in I(a)$ se $f(a)\neq 0$

### Teorema di Weierstrass
Se $f: [a,b] \to \mathbb R$ è continua, allora ha massimo e minimo assoluti su $[a, b]$

### Teorema degli zeri
Se $f:(p, q)\to \mathbb R$ è continua e tale che $f(a)*f(b)<0$ con $a, b \in (p, q)$, allora $\exists c \in (a,b) | f(c) =0$


# Derivate
Sia $f:D\to \mathbb R$ e $x_{0}, x_{0}+h\in D$.
Il **rapporto incrementale** di $f$ tra $x0$ e $x_{0}+h$ è

$$\frac{\Delta f}{\Delta x}(x_{0})=\frac{f(x_{0}+h)-f(x_{0})}{h}$$

È definita derivata di $f$ in $x_{0}$

$$f'(x_{0}) = \lim_{ h \to 0 }\frac{f(x+h)-f(x)}{h} $$

La funzione $f'$ che associa $x \to f'(x)\ \forall x \in D$ è chiamata **funzione derivata**

Se $f$ è invertibile, vale $(f^{-1})'(y)=\frac{1}{f'(x)}$

## Derivabilità
Sia $f: D \to \mathbb R$ e $x_{0} \in D$. Definiamo derivata destra di $f$ in $x_{0}$:

$$f_{+}'(x_{0})=\lim_{ h \to 0^+ }  \frac{f(x_{0}+h)-f(x_{0})}{h} $$
Analogamente si definisce la derivata sinistra.

Se esiste $f'(x_{0})=l$, allora esistono $f_{+}'(x_{0})=f_{-}'(x_{0})=l$, e viceversa.

### Teorema del limite della derivata
Sia $f: (a, b) \to \mathbb R$ e $x_{0} \in (a, b)$.
$$\exists \lim_{ x \to x_{0}^+} f'(x) = l \implies \exists f_{+}'(x_{0})=l$$
Analogamente vale per la derivata sinistra.

## Punti di non derivabilità
- punti di discontinuità
- punti di continuità
	- pt angoloso: $f_{-}'(x_{0})\neq f_{+}'(x_{0})$ e almeno uno finito
	- pt. di flesso a tg vert.: $f_{-}'(x_{0}) = f_{+}'(x_{0}) = \pm \infty$ 
	- pt. di cuspide: $f_{-}'(x_{0}) = -f'{+}'(x_{0}) = \pm \infty$ 
	- pt. generico di non derivabilità: $f_{-}'(x_{0}) \lor f_{+}'(x_{0})$ non esiste 
	- pt. di tg verticale al bordo: $f_{\pm}'(x_{0})= \pm \infty$ al bordo

## Differenziale
Sia $f$ derivabile in $x_{0}$ e $dx$ un incremento di $x$
Il differenziale di $f$ in $x_{0}$ (di incremento $dx$) è $df(x_{0})=f'(x_{0})dx$

## Teoremi sulle funzioni derivabili
Se $f$ è derivabile in $x_{0}$ e $f'(x_{0})=0$, allora $x_{0}$ è **punto stazionario** per $f$.

### Teorema di Fermat
Se $f(a,  b) \to \mathbb R$ è
1. derivabile su $(a,b)$
2. $x_{0} \in (a,b)$ è pt. di max/min relativo

allora $x_{0}$ è pt stazionario, ovvero $f'(x_{0}) = 0$

### Teorema di Rolle
Sia $f: [a, b] \to \mathbb R$ tale che:
1. $f$ continua su $[a, b]$
2. $f$ derivabile su $(a, b)$
3. $f(a) = f(b)$

allora $\exists c \in (a, b)\ |\ f'(c)=0$

### Teorema di Lagrange
Sia $f: [a, b] \to \mathbb R$ tale che:
1. $f$ continua su $[a, b]$
2. $f$ derivabile su $(a, b)$

allora $\exists c \in (a, b)\ |\ f'(c)= \frac{f(b)-f(a)}{b-a}$

### Teorema di Cauchy
Siano $f, g: [a, b] \to \mathbb R$ tali che:
1. $f, g$ continue su $[a, b]$
2. $f,g$ derivabili su $(a, b)$
3. $g(x)\neq0\ \forall x \in (a, b)$

allora $\exists c \in (a, b)\ |\ \frac{f'(c)}{g'(c)}= \frac{f(b)-f(a)}{g(b)-g(a)}$

### Teorema di Cauchy
Siano $f, g: (a, b) \to \mathbb R$ tali che:
1. $f,g$ derivabili su $(a, b)$
2. $g(x)\neq0\ \forall x \in (a, b)$
3. $\lim_{ x \to x_{0} } \frac{f(x)}{g(x)}=\frac{0}{0}$
4. $\exists \lim_{ x \to x_{0} } \frac{f'(x)}{g'(x)}=l$

allora $\exists \lim_{ x \to x_{0} } \frac{f(x)}{g(x)=l}$

### Teorema della funzione costante
Una funzione la cui derivata è 0 su un intervallo è costante su quell'intervallo.

Da ciò deriva che, se due funzioni hanno stessa derivata, allora differiscono per una costante.


### Teorema della funzione crescente/decrescente
Sia $f:(a,b)\to\mathbb R$ tale che $f$ derivabile su $(a, b)$ e $f'(x)>0\ \forall x\in (a, b)$. Allora $f$ è crescente su $(a, b)$.

Sia $f:(a,b)\to\mathbb R$ tale che $f$ derivabile su $(a, b)$ e crescente. Allora $f'(x)\ge0\ \forall x\in (a, b)$

### Teorema dei punti di massimo/minimo
Sia $f: (a,b) \to \mathbb R$ tale che
1. $f$ continua
2. $f$ crescente su $(a, x_{0})$
3. $f$ decrescente su $(x_{0}, b)$

Allora $x_{0}$ è punto di massimo relativo.

## Concavità e punti di flesso
Una funzione è localmente **convessa** se $\exists I(x_{0})\ |\ f(x) > f(x_{0}) + f'(x_{0})(x-x_{0})\ \forall x\in I(x_{0}) - \{x_{0}\}$

Analogamente, è **concava** se vale l'inverso.

$x_{0}$ è **punto di flesso ascendente** se $f$ passa da concava a convessa. 

Viceversa, $x_0$ è **punto di flesso discendente**.

Se $f$ è derivabile in $x_0$ punto di flesso, allora si distingue il punto di flesso tra:
- punto di flesso a tangenza obliqua
- punto di flesso a tangenza orizzontale
- punto di flesso a tangenza verticale

### Teorema della convessità/concavità
Sia $f: (a, b) \to \mathbb R$ tale che
1. $f$ derivabile due volte
2. $f''(x)>0\ \forall x\in (a, b)$

Allora $f$ è convessa.

Sia $f: (a, b) \to \mathbb R$ tale che
1. $f$ derivabile due volte
2. $f$ convessa

Allora $f''(x)\ge0\ \forall x\in (a, b)$.

### Teorema dei punti di flesso
Sia $f: (a, b) \to \mathbb R$ tale che
1. $f$ derivabile due volte
2. $x_0\in(a,b)$

Allora $f''(x_{0})=0$.




# Integrali
## Integrale indefinito
Sia $F(x)$ derivabile tale che $F'(x)=f(x)$: diciamo $F(x)$ **primitiva** di $f(x)$.

Se $f(x)$ è continua, allora ammette una primitiva.

Se $F(x)$ è primitiva di $f(x)$, allora qualsiasi funzione $G(x)=F(x)+C$ è primitiva di $f(x)$.

L'**integrale indefinito** di $f$ è l'insieme di tutte le primitive di $f$ ed è indicato con $\int f(x) \ dx$.
- $\int(f(x)+g(x))  \  dx=\int f(x) \  dx+\int g(x) \  dx$
- $\int kf(x) \  dx=k\int f(x) \  dx$

Date $F, f: \mathbb R \to \mathbb R\  |\  F'(x)=f(x)$ e $g$ derivabile, vale:

$$\int f(g(x)) \cdot g'(x) \  dx =F(g(x))+C$$

Date $f$ e $g$ derivabili, vale:

$$\int f'(x)\cdot g(x) \  dx = f(x) \cdot g(x) - \int f(x) \cdot g'(x) \  dx  $$

## Integrale definito
Si definiscono rispettivamente **somma integrale superiore** e **somma integrale inferiore**:
$$\begin{align}
S_{n}&=\sum_{i=1}^nmax_{i}f(x)\Delta x \\
s_{n}&=\sum_{i=1}^nmin_{i}f(x)\Delta x  \\
&\text{con} \ \  \Delta x=\frac{b-a}{n}
\end{align}$$

Se $f$ è continua, allora 
$$\lim_{ n \to +\infty }S_{n}=\lim_{ n \to +\infty }s_{n}=A$$
dove $A$ è l'area del trapezoide.
Se $f:[a,b]\to \mathbb R$, $f$ è integrabile in senso definito secondo Riemann e  $\lim_{ n \to +\infty }S_{n}=\lim_{ n \to +\infty }s_{n}=\int_{a}^b f(x)\  dx$

Se $f$ è continua, allora è integrabile in senso definito.

- $\int _{b}^a f(x)\  dx=-\int _{a}^b f(x)\  dx$
- $\int _{a}^af(x) \  dx=0$

### Proprietà
- $\int _{a}^b f(x)\  dx=\int _{a}^c f(x)\  dx + \int _{c}^b f(x)\  dx$
- $\int _{a}^b (f(x)+g(x))\  dx=\int _{a}^b f(x)\  dx+\int _{a}^b g(x)\  dx$
- $\int _{a}^b kf(x)\  dx=k\int _{a}^b f(x)\  dx$
- $f(x)\leq g(x) \implies\int _{a}^b f(x)\  dx \leq \int _{a}^b g(x)\  dx$
- $\left|\int _{a}^b f(x)\  dx\right|\leq\int _{a}^b \left|f(x)\right|\  dx$
- $\int _{a}^b k\  dx=k(b-a)$

### Teorema del valore medio integrale
Sia $f:[a,b]\to \mathbb{R}$ continua. Allora $\exists c \in [a, b] | f(c)(b-a)=\int _{a}^bf(x) \  dx$. 

$f(c)$ prende nome di valore medio integrale.

### Funzione integrale
Data $f:[a,b] \to \mathbb{R}$ continua, si definisce **funzione integrale** di $f$ su $[a, b]$
$$F(x)=\int _{a}^x f(t)\ dt $$

### Teorema fondamentale del calcolo integrale (Torricelli-Barrow)
Se $f$ è continua, allora $F$ è derivabile e vale:
$$F'(x)=f(x)$$

### Formula di Leibniz-Newtonnnnnn
$$\int _{a}^b f(x)\ dx=F(b)-F(a)=\Big[F(x)\Big]_{a}^b $$


# Equazioni differenziali