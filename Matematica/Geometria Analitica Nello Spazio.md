# Punto
Un punto è determinato da 3 coordinate
$$
P = (x, y, z)
$$
## Distanza tra due punti
$$
d(A, B) = \sqrt{ (x_{A}-x_{B})^2+(y_{A}-y_{B})^2+(z_{A}-z_{B})^2 }
$$

## Punto Medio
$$M
\begin{cases}
x_{M}=\frac{x_{A}+x_{B}}{2} \\
 y_{M}=\frac{y_{A}+y_{B}}{2}  \\
z_{M}=\frac{z_{A}+z_{B}}{2} 
\end{cases}
$$

## Baricentro 
$$
G\begin{cases}
x_{G}=\frac{1}{3}(x_{A}+x_{B}+x_{C}) \\
y_{G}=\frac{1}{3}(y_{A}+y_{B}+y_{C}) \\
z_{G}=\frac{1}{3}(z_{A}+z_{B}+z_{C})
\end{cases}
$$

# Vettori
Un punto $P$ può essere individuato da un vettore $\vec{v}$ con coda in $O$ e punta in $P$

## Operazioni
$$
\begin{align}
\vec{u}+\vec{v} &= (u_{x}+v_{x}, u_{y}+v_{y}, u_{z}+v_{z}) \\
k\vec{v} &= (kv_{x}, kv_{y}, kv_{z}) \\
\vec{u}\cdot\vec{v} &= u_{x}v_{x} + u_{y}v_{y} + u_{z}v_{z} \\
\vec{u}\times\vec{v} &= \det \begin{vmatrix}
\vec{i} & \vec{j} & \vec{k} \\
u_{x} & u_{y} & u_{z} \\
v_{x} & v_{y} & v_{z}
\end{vmatrix}
\end{align}
$$

## Vettori paralleli e perpendicolari
$$
\begin{align}
\vec{u} \parallel \vec{v} &\iff \vec{u}=k\vec{v} \\
\vec{u}\perp \vec{v}&\iff \vec{u}\cdot \vec{v}=0
\end{align}
$$

# Retta
Presi un punto $P_{0}$ e un vettore direzione $(l,m,n)$, un generico punto $P \in r \iff \overrightarrow{P_{0}P} \parallel \vec{v}$ : 


$$\begin{align}
&\begin{cases}
x-x_{0}=kl \\
y-y_{0}=km \\
z-z_{0}=kn
\end{cases} \\ \\
\frac{x-x_{0}}{l} &= \frac{y-y_{0}}{m} =\frac{z-z_{0}}{n} =k
\end{align}$$

In particolare:
- $l=0 \iff r\parallel Oyz$
- $m=0 \iff r\parallel Oxz$
- $n=0 \iff r\parallel Oxy$
- $m=0, n=0 \iff r \parallel \text{asse }x$
- $n=0, l=0 \iff r \parallel \text{asse }y$
- $l=0, m=0 \iff r \parallel \text{asse }z$

## Retta passante per due punti
Dati due punti $A$ e $B$, la retta passante per essi è 

$$
r : \frac{x-x_{A}}{x_{B}-x_{A}} = \frac{y-y_{A}}{y_{B}-y_{A}}= \frac{z-z_{A}}{z_{B}-z_{A}}
$$

# Piano
Dati un punto $P(x_{0},y_{0},z_{0})$ e la normale $\vec{n}(a,b,c)$, il piano $\alpha$ è il luogo dei punti $P(x,y,z) | \overrightarrow{PP_{0}} \perp \vec{n}$ : 

$$
\begin{align}
\alpha: ax+by+cz+d=0 \\
d = -(ax_{0}+by_{0}+cz_{0})
\end{align}
$$


Due piani sono paralleli se le loro normali sono parallele, perpendicolari se le loro normali sono perpendicolari

## Distanza punto piano
Dati $\alpha:ax+by+cz+d=0$ e $A(x_{A},y_{A},z_{A})$,

$$
d(A, \alpha) = \frac{|ax_{A}+by_{A}+cz_{A}+d|}{\sqrt{ a^2+b^2+c^2 }}
$$


## Retta da due piani
Una retta è individuata dall'intersezione di due piani

$$
r\begin{cases}
ax+by+cz+d=0 \\
a'x+b'y+c'z+d'=0
\end{cases}
$$


## Posizione reciproca di due rette
Due rette sono:
- parallele se i loro vettori direzione sono paralleli
- perpendicolari se i loro vettori direzione sono perpendicolari
- sghembe se appartengono a piani diversi e non hanno punti in comune
- incidenti se hanno un punto in comune



# Sfera
Una superficie sferica $\omega$ di centro $C(x_{0},y_{0},z_{0})$ e raggio $r$ ha equazione: 

$$
(x-x_{0})^2+(y-y_{0})^2+(z-z_{0})^2=r^2
$$


L'equazione $x^2+y^2+z^2+ax+by+cz+d=0$ rappresenta una superficie sferica di centro $C\left( -\frac{a}{2},-\frac{b}{2},-\frac{c}{2} \right)$ e raggio $r=\frac{1}{2}\sqrt{a^2+b^2+c^2-4d}$