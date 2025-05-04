# Statistica
## Valore atteso
$$E = \sum x_ip_i$$
## Varianza e deviazione standard
$\bar x$ è la media, $\sigma$ è la deviazione standard
$$VAR = \sum (x_i - \bar x)^2$$
$$\sigma=\sqrt{VAR}$$


# Probabilità

$$
P(N) = \frac{\text{casi favorevoli}}{\text{casi totali}}
$$


$$
P(\bar{A}) = 1 - P(A)
$$

## [Teorema di Bayes](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Bayes_theorem_assassin.svg/800px-Bayes_theorem_assassin.svg.png)
La probabilità che accada A dato B, con A e B dipendenti, è:

$$P(A|B)=\frac{P(B|A)P(B)}{P(A)}$$

dove $P(B|A$) è la probabilità che accada B dato A.


# Combinatoria
## Disposizioni
Disposizioni di $n$ elementi in gruppi ordinati di $k$ elementi senza ripetizioni

$$D_{n,k} = \frac{n!}{(n-k)!}$$

Disposizioni di $n$ elementi distinti in gruppi ordinati di $k$ elementi:
$$D'_{n,k}=n^k$$

## Permutazioni
Permutazioni di $n$ elementi senza ripetizioni:
$$P_{n}=n!$$

Permutazioni circolari di $n$ elementi senza ripetizioni:
$$P'_{n}=(n-1)!$$

Permutazioni con ripetizioni:
$$P = \frac{n!}{\prod k_{i}!}$$


## Combinazioni
Combinazioni senza ripetizioni:
$$C_{n,k}=\frac{D_{n,k}}{P_{k}}=\frac{n!}{(n-k)!k!}={n \choose k}$$

Combinazioni con ripetizioni:
$$C_{n,k}'=\frac{(n+k-1)!}{k!(n-1)!}$$