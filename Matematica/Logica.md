# Operatori logici

| Nome               | Abbr. | Simbolo    |
| ------------------ | ----- | :----------: |
| Negazione          | NOT   | $\lnot$    |
| Disgiunzione incl. | OR    | $\lor$     |
| Congiunzione       | AND   | $\land$    |
| Disgiunzione escl. | XOR   | $\oplus$   |
| Condizionale       | IF    | $\implies$ |
| Bicondizionale     | IFF   | $\iff$     |
| Conclusione        | -     | $\vdash$   |

Simboli poco usati:

| Nome      | Simbolo      |
| --------- | :------------: |
| NOR       | $\downarrow$ |
| NAND      | $\uparrow$   |
| XNOR      | $\odot$      |
| Therefore | $\therefore$ |
| Because   | $\because$   |


# Tavole di verità

| $p$ | $\lnot p$ |
| --- | :---------: |
| 0   | 1|
| 1   | 0         | 

| $p$ | $q$ | $p \lor q$ |
| --- | --- | :----------: |
| 0   | 0   | 0          |
| 0   | 1   | 1          |
| 1   | 0   | 1          |
| 1   | 1   | 1           |

| $p$ | $q$ | $p \land q$ |
| --- | --- | :----------: |
| 0   | 0   | 0          |
| 0   | 1   | 0          |
| 1   | 0   | 0          |
| 1   | 1   | 1           |

| $p$ | $q$ | $p \oplus q$ |
| --- | --- | :----------: |
| 0   | 0   | 0          |
| 0   | 1   | 1          |
| 1   | 0   | 1          |
| 1   | 1   | 0           |

| $p$ | $q$ | $p \implies q$ |
| --- | --- | :--------------: |
| 0   | 0   | 1              | 
| 0   | 1   | 1              |
| 1   | 0   | 0              |
| 1   | 1   | 1              |

| $p$ | $q$ | $p \iff q$ |
| --- | --- | :----------: |
| 0   | 0   | 1          |
| 0   | 1   | 0         |
| 1   | 0   | 0          |
| 1   | 1   | 1           |


# Regole
## Regole di De Morgan
- $\lnot (p \land q) \iff \lnot p \lor \lnot q$.
- $\lnot (p \lor q) \iff \lnot p \land \lnot q$.

## Modus tollens
$p \implies q \iff \lnot q \implies \lnot p$.

## Doppia negazione
$\lnot(\lnot p) \iff p$.

## Assurdo
$p \implies (q \land \lnot q) \vdash \lnot p$.
$\lnot p \implies (q \land \lnot q) \vdash p$ (prova indiretta).

## Eliminazione della disgiunzione (dilemma costruttivo)
$p \implies r, q \implies r \vdash (p \lor q) \implies r$

## Introduzione della disgiunzione
$p$ è vera $\vdash p \lor q$ è vera.

## Eliminazione della congiunzione
$p\land q$ è vera, ma $p \vdash q$.

$p\land q$ è vera, ma $q \vdash p$.

# Introduzione della congiunzione
$p$ è vera, $q$ è vera $\vdash p \land q$ è vera.