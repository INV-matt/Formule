# Valori noti
| function | $0$ | $\frac \pi 6$ | $\frac \pi 4$ | $\frac \pi 3$ | $\frac \pi 2$ |
|--- | ---|---|---|---| --- |
| $\sin$ | $0$ | $\frac 1 2$ | $\frac {\sqrt 2} 2$ | $\frac {\sqrt 3} 2$| $1$| 
| $\cos$ | $1$ | $\frac {\sqrt 3} 2$ | $\frac {\sqrt 2} 2$ | $\frac 1 2$ | $0$| 
| $\tan$ | $0$ | $\frac {\sqrt 3} 3$ | $1$ | $\frac {\sqrt 3} 2$| $\pm \infty$| 

# Archi e angoli associati
## Angoli supplementari
$$
\begin{align}
\sin(\pi - \alpha) &= \sin(\alpha) \\
\cos(\pi - \alpha) &= -\cos(\alpha) \\
\tan(\pi - \alpha) &= -\tan(\alpha) \\ \\
\csc(\pi - \alpha) &= \csc(\alpha) \\
\sec(\pi - \alpha) &= -\sec(\alpha) \\
\cot(\pi - \alpha) &= -\cot(\alpha) \\
\end{align}
$$
## Angoli che differiscono di $\pi$
$$
\begin{align}
\sin(\pi + \alpha) &= -\sin(\alpha) \\
\cos(\pi + \alpha) &= -\cos(\alpha) \\
\tan(\pi + \alpha) &= \tan(\alpha) \\ \\
\csc(\pi + \alpha) &= -\csc(\alpha) \\
\sec(\pi + \alpha) &= -\sec(\alpha) \\
\cot(\pi + \alpha) &= \cot(\alpha) \\
\end{align}
$$
## Angoli esplementari
$$
\begin{align}
\sin(2\pi - \alpha) &= -\sin(\alpha) \\
\cos(2\pi - \alpha) &= \cos(\alpha) \\
\tan(2\pi - \alpha) &= -\tan(\alpha) \\ \\
\csc(2\pi - \alpha) &= -\csc(\alpha) \\
\sec(2\pi - \alpha) &= \sec(\alpha) \\
\cot(2\pi - \alpha) &= -\cot(\alpha) \\
\end{align}
$$

## Teorema di Pitagora
$$\sin^2\alpha + \cos^2\alpha = 1$$

# Formule di addizione
$$\begin{align}
\sin(\alpha+\beta)&=\sin\alpha\cos\beta+\sin\beta\cos\alpha \\
\cos(\alpha+\beta)&=\cos\alpha\cos\beta-\sin\alpha\sin\beta \\
\tan(\alpha+\beta)&=\frac{\tan\alpha+\tan\beta}{1-\tan\alpha\tan\beta}
\end{align}$$
# Formule di sottrazione
$$\begin{align}
\sin(\alpha-\beta)&=\sin\alpha\cos\beta-\sin\beta\cos\alpha \\ 
\cos(\alpha-\beta)&=\cos\alpha\cos\beta+\sin\alpha\sin\beta \\
\tan(\alpha-\beta)&=\frac{\tan\alpha-\tan\beta}{1+\tan\alpha\tan\beta}
\end{align}$$
# Formule di duplicazione
$$\begin{align}
\sin2\alpha&=2\sin\alpha\cos\alpha \\ \\
\cos2\alpha&=\cos^2\alpha-\sin^2\alpha \\ 
&=2\cos^2\alpha-1 \\  
&=1-2\sin^2\alpha \\ \\
\tan2\alpha&=\frac{2\tan\alpha}{1-\tan^2\alpha}
\end{align}$$
# Formule di bisezione
$$\begin{align}
\sin\frac\alpha2&=\pm\sqrt{\frac{1-\cos\alpha}2} \\ \\
\cos\frac\alpha2&=\pm\sqrt{\frac{1+\cos\alpha}2} \\ \\
\tan\frac\alpha2&=\pm\sqrt{\frac{1-\cos\alpha}{1+\cos\alpha}} \\
&=\pm\frac{\sin\alpha}{1+\cos\alpha} \\ 
&=\pm\frac{1-\cos\alpha}{\sin\alpha} \\
\text{con}\ \alpha&\neq(2k+1)\pi,\ k\in\mathbb{Z}
\end{align}$$

# Formule parametriche
$$
\begin{align}
\sin \alpha&=\frac{2t}{1+t^2} \\
\cos \alpha&=\frac{1-t^2}{1+t^2}  \\
\end{align}
$$

Con $t=\tan\frac{\alpha}{2}$ e $\alpha\neq \pi+2k\pi$ .

# Formule di prostaferesi

$$ 
\begin{align}
\sin \alpha + \sin \beta &= 2 \sin\frac{\alpha+\beta}{2}\cos\frac{\alpha-\beta}{2} \\
\sin \alpha - \sin \beta &= 2 \sin\frac{\alpha+\beta}{2}\cos\frac{\alpha-\beta}{2} \\
\cos \alpha + \cos \beta &= 2 \cos\frac{\alpha+\beta}{2}\cos\frac{\alpha-\beta}{2} \\
\cos \alpha - \cos \beta &= -2 \sin\frac{\alpha+\beta}{2}\sin\frac{\alpha-\beta}{2} \\
\end{align} 
$$

# Formule di Werner
Bruh ricavatele da prostaferesi

# Risoluzione di equazioni lineari in seno e coseno
## Metodo algebrico
Risoluzione attraverso le [formule parametriche](#Formule%20parametriche)

## Metodo geometrico
Riscriviamo l'equazione $a\sin x+b\cos x+c=0$ come:

$$
\begin{cases}
a\sin x+b\cos x+c=0 \\
\cos^2x + \sin^2 x = 0 \\
\end{cases}
$$

Poniamo $X := \cos x$ e $Y:=\sin x$: 

$$
\begin{cases}
aY+bX+c=0 \\
X^2+Y^2=1
\end{cases}
$$

Questo sistema rappresenta l'intersezione tra una circonferenza e una retta.
## Metodo dell'angolo aggiunto
$$
\begin{align}
a\sin x+b\cos x&=r\sin (x+\alpha) \\
\text{con: } \\
r = \sqrt{ a^2+b^2 },&\ \tan\alpha=\frac{a}{b}
\end{align}
$$





