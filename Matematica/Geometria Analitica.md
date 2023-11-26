# Retta
![retta](assets/graphs/retta.svg)
$$y=mx+q$$
$$ax+by+c=0$$
## Retta passante per due punti $A(x_A;y_A)$ e $B(x_B;y_B)$
$$y-y_A=\frac{y_A - y_B}{x_A-x_B}(x-x_A)$$
## Asse del segmento
$$(x-x_A)^2+(y-y_A)^2=(x-x_B)^2+(y-y_B)^2$$
$$2(x_B-x_A)+2(y_B-y_A)+x_A^2+y_A^2-x_B^2-y_B^2=0$$
## Bisettrice
$$\frac{ax+by+c}{\sqrt{(a^2+b^2)}} = \pm \frac{a'x+b'y+c'}{\sqrt{(a' ^2+b' ^2)}}$$
## Fascio Proprio e Improprio
$$(a + a'k)x + (b+b'k)y + c+k=0$$
$(a + a'k) \neq (b+b'k) \Rightarrow$  Fascio Proprio

$(a + a'k) = (b+b'k) \Rightarrow$  Fascio Improprio

# Parabola
## Parabola  $\gamma: y=ax^2+bx+c$

##### Vertice
$$V\equiv \bigg(-\frac{b}{2a};\frac{4ac-b^2}{4a} \bigg)$$
##### Fuoco
$$F\equiv \bigg(-\frac{b}{2a};\frac{1+ 4ac-b^2}{4a} \bigg)$$
##### Direttrice
$$d: y=\frac{4ac-b^2-1}{4a}$$

## Parabola  $\gamma: x=ay^2+by+c$

##### Vertice
$$V\equiv \bigg(\frac{4ac-b^2}{4a};-\frac{b}{2a} \bigg)$$
##### Fuoco
$$F\equiv \bigg(\frac{1+ 4ac-b^2}{4a};-\frac{b}{2a}\bigg)$$
##### Direttrice
$$d: x=\frac{4ac-b^2-1}{4a}$$

## Formula di Sdoppiamento
$$\frac{y+y_0}{2}=ax_0x+b\frac{x_0+x}{2}+c$$
## Area del Segmento Parabolico
L'area è uguale a $\frac{2}{3}$ dell'area  del rettangolo circoscritto. 
Se la parabola é della forma $\gamma: y=ax^2+bx+c$ :
$$\mathcal{A}=\frac{1}{6}|a||x_A-x_B|^3$$
Se la parabola è della forma $\gamma: x=ay^2+by+c$ :
$$\mathcal{A} = \frac{1}{6}|a||y_A-y_B|^3$$
# Circonferenza
$$\omega: x^2+y^2+ax+by+c=0$$
##### Centro e raggio
$$C \equiv \bigg(-\frac{1}{2}a; -\frac{1}{2}b\bigg)$$
$$r=\sqrt{x{_C}^2+y{_C}^2-c}$$
## Formula di sdoppiamento
$$x_0x+y_0y+a\frac{x_0+x}{2}+b\frac{y_0+y}{2}+c=0$$

# Ellisse
Ellisse con centro in $O(0;0)$ 
$$\omega:\frac{x^2}{a^2}+\frac{y^2}{b^2}=1$$
Ellisse con centro in $O'(p;q)$ 

$$\begin{align}
&\omega:\frac{(x-p)^2}{a^2}+\frac{(y-q)^2}{b^2}=1 \\
&\text{oppure} \\
&\omega:a'x^2+b'y^2+c'x+d'y+e'=0 
\end{align}
$$
## Formula di sdoppiamento
$$\frac{x_0x}{a^2}+\frac{y_0y}{b^2}=1$$

# Iperbole
## Iperbole con centro in $O(0;0)$ e asse trasverso: asse x

$$\begin{align}
\gamma:\frac{x^2}{a^2}-\frac{y^2}{b^2}=1 \\
F_{1;2}\equiv(\pm c; 0)
\end{align}$$

## Iperbole con centro in $O(0;0)$ e asse trasverso: asse y

$$\begin{align}
\gamma:\frac{x^2}{a^2}-\frac{y^2}{b^2}=-1 \\
F_{1;2}\equiv(0; \pm c)
\end{align}$$

##### Semiasse focale ed eccentricità

$$\begin{align}
c &= \sqrt{a^2+b^2} \\
e&=\frac c a
\end{align}$$

## Equazione di un'iperbole generica

$$ \gamma: ax^2+by^2+cx+dy+e=0 \text{, con } ab<0 $$

## Iperbole equilatera:
$$ \gamma: x^2-y^2=\pm a^2 $$

## Iperbole riferita agli asintoti

$$ \gamma: xy=k $$

Se $k>0$:

$$\begin{align}
A_1\equiv (-\sqrt k, -\sqrt k), A_2\equiv (\sqrt k, \sqrt k) \\ 
F_1\equiv (-\sqrt {2k}, -\sqrt {2k}), F_2\equiv (\sqrt {2k}, \sqrt {2k}) \\
\end{align}$$

Se $k<0$:

$$\begin{align}
A_1\equiv (-\sqrt {-k}, -\sqrt {-k}), A_2\equiv (\sqrt {-k}, \sqrt {-k}) \\
F_1\equiv (-\sqrt {-2k}, -\sqrt {-2k}), F_2\equiv (\sqrt {-2k}, \sqrt {-2k}) \\
\end{align}$$

## Funzione Omografica:
$$
\begin{align}
& \gamma:y=\frac{ax+b}{cx+d},\ c\neq0\ \land\ ad\neq bc \\
& \gamma: (x+\frac d c)(y -\frac a c )=1
\end{align}
$$