[![forthebadge](https://forthebadge.com/images/badges/gluten-free.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/you-didnt-ask-for-this.svg)](https://forthebadge.com) 

# Indice
- [Matematica](#Matematica)
	- [Algebra](#Algebra)
	- [Geometria Analitica](#Geometria-Analitica)
	- [Funzioni](#Funzioni)
	- [Probabilità](#Probabilità)
- [Fisica](#Fisica)
	- [Statica](#Statica)
	- [Ottica Geometrica](#Ottica-Geometrica)
	- [Calore e temperatura](#Calore-e-Temperatura)
	- [Cinematica](#Cinematica)
	- [Dinamica](#Dinamica)
	- [Relatività Galileiana](#Relatività-galileiana)
	- [Forze Apparenti](#Forze-apparenti)
	- [Impulso e Quantità di moto](#Impulso-e-quantità-di-moto)
	- [Dinamica Rotazionale](#Dinamica-rotazionale)
	- [Prodotti](#Prodotti)


# Matematica
## Algebra

#### $\Delta :$
$$x_{1;2} = \frac{-b \pm \sqrt{b^2-4ac}}{2a}$$
#### $\frac{\Delta}{4} :$

$$b=2k \ \Rightarrow \ x_{1;2} = \frac{-k \pm \sqrt{k^2-ac}}{a}$$

## Geometria Analitica
### Retta
$$y=mx+q$$$$ax+by+c=0$$
#### Retta passante per due punti $A(x_A;y_A)$ e $B(x_B;y_B)$
$$y-y_A=\frac{y_A - y_B}{x_A-x_B}(x-x_A)$$
#### Asse del segmento
$$(x-x_A)^2+(y-y_A)^2=(x-x_B)^2+(y-y_B)^2$$
$$2(x_B-x_A)+2(y_B-y_A)+x_A^2+y_A^2-x_B^2-y_B^2=0$$
#### Bisettrice
$$\frac{ax+by+c}{\sqrt{(a^2+b^2)}} = \pm \frac{a'x+b'y+c'}{\sqrt{(a' ^2+b' ^2)}}$$
#### Fascio Proprio e Improprio
$$(a + a'k)x + (b+b'k)y + c+k=0$$
$(a + a'k)x \neq (b+b'k) \Rightarrow$  Fascio Proprio

$(a + a'k)x = (b+b'k) \Rightarrow$  Fascio Improprio

### Parabola
#### Parabola  $\gamma: y=ax^2+bx+c$

##### Vertice
$$V\equiv \bigg(-\frac{b}{2a};\frac{4ac-b^2}{4a} \bigg)$$
##### Fuoco
$$F\equiv \bigg(-\frac{b}{2a};\frac{1+ 4ac-b^2}{4a} \bigg)$$
##### Direttrice
$$d: y=\frac{4ac-b^2-1}{4a}$$

#### Parabola  $\gamma: x=ay^2+by+c$

##### Vertice
$$V\equiv \bigg(\frac{4ac-b^2}{4a};-\frac{b}{2a} \bigg)$$
##### Fuoco
$$F\equiv \bigg(\frac{1+ 4ac-b^2}{4a};-\frac{b}{2a}\bigg)$$
##### Direttrice
$$d: x=\frac{4ac-b^2-1}{4a}$$

#### Formula di Sdoppiamento
$$\frac{y+y_0}{2}=ax_0x+b\frac{x_0+x}{2}+c$$
#### Area del Segmento Parabolico
L'area è uguale a $\frac{2}{3}$ dell'area  del rettangolo circoscritto. 
Se la parabola é della forma $\gamma: y=ax^2+bx+c$ :
$$\mathcal{A}=\frac{1}{6}|a||x_A-x_B|^3$$
Se la parabola è della forma $\gamma: x=ay^2+by+c$ :
$$\mathcal{A} = \frac{1}{6}|a||y_A-y_B|^3$$
### Circonferenza
$$\omega: x^2+y^2+ax+by+c=0$$
##### Centro e raggio
$$C \equiv \bigg(-\frac{1}{2}a; -\frac{1}{2}b\bigg)$$
$$r=\sqrt{x{_C}^2+y{_C}^2-c}$$
#### Formula di sdoppiamento
$$x_0x+y_0y+a\frac{x_0+x}{2}+b\frac{y_0+y}{2}+c=0$$

### Ellisse
Ellisse con centro in $O(0;0)$ 
$$\omega:\frac{x^2}{a^2}+\frac{y^2}{b^2}=1$$
Ellisse con centro in $O'(p;q)$
$$\begin{align}
&\omega:\frac{(x-p)^2}{a^2}+\frac{(y-q)^2}{b^2}=1\\
&\text{oppure}\\
&\omega:a'x^2+b'y^2+c'x+d'y+e'=0 \ \text{ (non sempre rappresenta un'ellisse) }
\end{align}$$
#### Formula di sdoppiamento
$$\frac{x_0x}{a^2}+\frac{y_0y}{b^2}=1$$


## Funzioni

Una relazione $f: A \to B$ è una funzione se a ogni elemento di $A$ associa uno e un solo elemento di $B$

Una funzione $f: A \to B$ è **iniettiva** se ogni elemento di $B$ è immagine al più di un elemento di $A$ $$x_1 \neq x_2 \Rightarrow f(x_1) \neq f(x_2)$$
Una funzione $f: A \to B$ è **suriettiva** se ogni elemento di $B$ è immagine di almeno un elemento di $A$

Una funzione $f: A \to B$ è **biunivoca** se è contemporaneamente iniettiva e biettiva $$f: A \leftrightarrow B$$
Una funzione $f: A \to B$ è **crescente** in un intervallo $I \subseteq \mathbb{D}$ se $$\forall x_1,x_2 \in I, x_1 < x_2 \Rightarrow f(x_1)<f(x_2)$$
Una funzione $f: A \to B$ è **decrescente** in un intervallo $I \subseteq \mathbb{D}$ se $$\forall x_1,x_2 \in I, x_1 < x_2 \Rightarrow f(x_1)>f(x_2)$$
Dato $D\subseteq R \ |\ x\in D \Rightarrow -x \in D$, se $f(-x)=f(x),\ \forall x \in D$ allora $f(x)$ è **pari**, altrimenti se se $f(-x)=-f(x),\ \forall x \in D$ allora $f(x)$ è **dispari**

Comporre due funzioni $f:A\to B$ e $g:B\to C$ significa considerare una terza funzione che associa a ogni elemento di $A$ un elemento di $C$.
Questa funzione è detta **funzione composta** $g \circ f$:
$$(g \circ f)(x) = g(f(x))$$
In generale $g\circ f \neq f \circ g$
Se si compongono le due funzioni $f:A\to B$ e $f^{-1}: B\to A$, si ottiene la funzione identità:
$$(f^{-1} \circ f)(x) = x$$

## Probabilità
### Valore atteso
$$E = \sum x_ip_i$$
### Varianza e deviazione standard
$\bar x$ è la media, $\sigma$ è la deviazione standard
$$VAR = \sum (x_i -\bar x)^2$$$$\sigma=\sqrt{VAR}$$

# Fisica
## Statica
Un corpo è in equilibrio se:
$$\begin{cases}
\sum \vec F = 0 \\
\sum \vec M = 0
\end{cases}$$

### Idrostatica
#### Pressione
$$p = \frac {F_{\perp}}{S}$$
#### Legge di Stevino
$$p=dgh$$
Da questa formula si ricava che la pressione atmosferica $p_0=1,013 * 10^5 Pa$

#### Principio di Archimede
$$F_A=pS=dg(h_2-h_1)S=d_{fluido}gV$$
Da ciò si ricava che:
$$\begin{cases}
F_A \lt P+F_{\perp} \iff il\ corpo\ affonda \\
F_A \gt P+F_{\perp} \iff il\ corpo\ galleggia\\
\end{cases}
$$

## Ottica Geometrica
$$\theta_i \cong \theta_r$$
### Specchi sferici
$$f=\frac{1}{2}r$$
### Rifrazione - Legge di Snell
$$n\sin\theta_0=n\sin\theta_1$$
### Leggi delle lenti sottili
$$\frac{1}{p}+\frac{1}{q}=\frac{1}{f}$$
Dove $p$ è la distanza dell'oggetto dal centro, $q$ la distanza dell'immagine dall'oggetto e $f$ la distanza focale
$$G = -\frac{q}{p}$$

## Calore e Temperatura
**Temperatura**: quanto le molecole di un corpo sono agitate
**Calore**: energia, ovvero capacità di un corpo di fare qualcosa

### Dilatazione termica 
$$l_f=l_0(1+\lambda\Delta T)$$
$$V_f=V_0(1+\beta\Delta T)$$

### Calore
$$Q=mc_s\Delta T$$
dove $c_s$ è il calore specifico. Il calore è misurato in Joule, $1cal = 4,186 J$ 

### Passaggi di stato
$$Q = m L$$
dove $L$ è il calore latente.

### Equilibrio termico
$$\begin{align}
|Q_{ceduto}|&=|Q_{assorbito}| \\
m_1 c_{s_1} (T_{eq}- T_1)&+m_2 c_{s_2} (T_{eq}- T_2) = 0
\end{align}$$

## Cinematica
#### MRU
$$\begin{align}
\begin{cases}
s_1&=s_0 + v\Delta t\\
v &= COSTANTE\\
a &= 0\ m/s^2
\end{cases}
\end{align}$$
#### MRUA
$$\begin{align}
\begin{cases}
s_1&=s_0 + v_0\Delta t + \frac{1}{2}a\Delta t^2\\
v_f &= v_0 + a\Delta t \\ 
a &= COSTANTE
\end{cases}
\end{align}$$
#### MPRB con lancio orizzontale
$$\begin{align} &s(\Delta t)
\begin{cases}
s_x = v\Delta t\\
s_y = y_0 - \frac{1}{2}g\Delta t^2
\end{cases}\\\\
&v(\Delta t)
\begin{cases}
v_x = v_0 \\
v_y =  - g\Delta t
\end{cases}\\\\
&\gamma: y=-\frac{g}{2{v_0}^2}x^2+y_0\\\\
&\Delta t_{volo}=\sqrt{\frac{2y_0}{g}}\\\\
&G = v_x\Delta t_{volo}
\end{align}$$
#### MPRB con lancio obliquo
$$
\begin{align} &v_0
\begin{cases}
v_{0_x} = v_0 \cos \theta \\
v_{0_y} = v_0 \sin \theta
\end{cases}\\\\
&s(\Delta t)
\begin{cases}
s_x = v_{0_x}\Delta t\\
s_y = v_{0_y}\Delta t - \frac{1}{2}g\Delta t^2
\end{cases}\\\\
&v(\Delta t)
\begin{cases}
v_x = v_{0_x} \\
v_y = v_{0_y}- g\Delta t
\end{cases}\\\\
&\gamma: y=-\frac{g}{2{v_{0_x}}^2}x^2+\frac{v_{0_y}}{v_{0_x}}x\\\\
&\Delta t_{volo}=\frac{2v_{0_y}}{g}\\\\
&G = v_x\Delta t_{volo} = \frac{2{v_0}^2}{g}\sin \theta \cos \theta
\end{align}
$$
#### MCU
$$v_{tang.}=\frac{\Delta l}{\Delta t}=\frac{2\pi r}{T}$$
$$\omega = \frac{\Delta \theta ^{^{RAD}}}{\Delta t}=\frac{2\pi}{T}$$
$$\therefore\ v_{tang.} = \omega r$$
$$a_{tang.}= COSTANTE$$
$$a_{radiale} = \frac{{v_{tang.}}^2}{r} = \omega^2r$$
$$f=T^{-1}$$
La frequenza $f$ può anche essere chiamata $\nu$ 

## Dinamica
$$\sum \vec{F}=m \vec{a}$$
#### Lavoro con $\vec{F}$ costante
$$W=\vec{F}\cdot\Delta\vec{ s}$$
#### Lavoro con $\vec{F}$ variabile
Corrisponde all'area sotto il grafico $\Delta s$; $F$

#### Energia cinetica
$$K = \frac{1}{2}mv^2$$
$$ W =\Delta K$$
#### Energia Potenziale
$$W_c = -\Delta U$$
dove $W_c$ é il lavoro di una forza conservativa, ovvero una forza il cui lavoro é  indipendente dal percorso che il corpo compie.
In particolare, per un corpo di massa $m$ ad altezza $h$ si ha che:
$$U_P=mgh$$
#### Principio di conservazione dell'energia meccanica
$$
\begin{align}
&\begin{cases}
W_{tot}=W_{cons} + W_{non\ cons} = \Delta K\\ 
W_{cons}=-\Delta U
\end{cases} \\
&\therefore W_{non\ cons}=\Delta K+\Delta U \\ \\
&W_{non\ cons} = 0 \iff \Delta K + \Delta U =0
\end{align}
$$
#### Potenza
$$
\begin {align}
\bar P = \frac{W}{\Delta t} \\ 
\bar P = \vec F \cdot \bar{\vec v} 
\end{align}
$$

## Relatività galileiana
$$
s(\Delta t) \begin{cases}
x_{B_x}=&x_{A_x}-v_x\Delta t \\
y_{B_y}=&y_{A_y}-v_y\Delta t \\
z_{B_z}=&z_{A_z}-v_z\Delta t
\end{cases} $$

$$
v(\Delta t) \begin{cases} 
u_{B_x}=&u_{A_x}-v_x\\
u_{B_y}=&u_{A_y}-v_y\\
u_{B_z}=&u_{A_z}-v_z
\end{cases} $$

Ogni sistema di riferimento che si muove a velocità costante rispetto a un sistema inerziale è un sistema inerziale.
## Forze apparenti
#### Peso apparente
$$F_N=mg+ma$$
#### Forza centripeta e centrifuga
Sono l'effetto di un'accelerazione centripeta: la prima è relativa ad un osservatore esterno al sistema non inerziale, la seconda ad un osservatore interno.
Hanno entrambe modulo $F_c=m\omega^2 r$, direzione parallela ad $r$ e verso opposto tra loro: la forza centripeta verso l'interno, quella centrifuga verso l'esterno

#### Forza di Coriolis
$$\vec F_{Cor}= 2m\vec{v}\times \vec{\omega}$$

## Impulso e quantità di moto
#### Impulso
$$\vec{I} = \vec{F}\Delta t$$
#### Quantità di moto
$$\vec{q} = m\vec{v}$$
#### Teorema dell'impulso
$$\vec{I}=\Delta \vec{q}$$
#### Urti
Se l'urto è **elastico** $$K_f = K_i \ \ \ \ \ et \ \ \ \ q_f=q_i$$
Se l'urto è **anelastico** $$K_f \neq K_i \ \ \ \ \ et \ \ \ \ q_f=q_i$$


## Dinamica Rotazionale
$$\begin{align}
\alpha=\frac{\Delta\omega}{\Delta t} \\
a_T=r\alpha
\end{align}$$
#### Momento
$$\vec M = \vec r \times \vec F$$

#### Momento di inerzia
$$\begin{align}
I_a=\sum mr^2\\
\sum M_a = I_a\alpha
\end{align}$$

#### Momento angolare
$$\vec L=I\vec\omega$$
se la risultante delle forze esterne è nulla: $L_f=L_i$ 


## Prodotti
#### Prodotto scalare
$$\vec{a}\cdot\vec{b} = |\vec{a}||\vec{b}|\cos(\theta) $$
#### Prodotto vettoriale
$$\vec{a}\times\vec{b} = \vec{c} $$
$$|\vec{c}| = |\vec{a}||\vec{b}|\sin(\theta) $$
$\vec{c}$ ha direzione uguale a quella della normale del piano su cui giacciono $\vec{a}$ e $\vec{b}$ e verso determinabile con [questo schema](https://i.kym-cdn.com/entries/icons/original/000/032/116/cover1.jpg) 
