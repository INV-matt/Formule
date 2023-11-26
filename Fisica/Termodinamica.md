Stabilisce le trasformazioni di E termica in E meccanica e viceversa.
È sempre possibile trasformare una quantità di E meccanica in E termica, ma non il contrario.

Un sistema termodinamico S.T. è il dispositivo che risente dei parametri di stato. 
Se viene riscaldato, $Q \gt 0$, se è raffreddato, $Q \lt 0$.
Se compie un lavoro, $W \gt 0$, se lo subisce, $W \lt 0$.

Un S.T. è:
- __aperto__ se è possibile il passaggio di materia e energia
- __chiuso__ se è possibile solo il passaggio energia
- __isolato__ se è inibito il passaggio di materia e energia

# Principio Zero
Se due S.T. sono individualmente in equilibrio termico con un terzo S.T., allora sono in equilibrio termico tra di loro.

# Primo principio
$$
\Delta U = Q - W
$$

$U$ è funzione di stato: dipende unicamente dallo stato del sistema e non da come è stato raggiunto quello stato.
$Q$ e $W$ non sono funzioni di stato.

## Trasformazioni quasi statiche
È una trasformazione che avviene così lentamente che il gas passa da stati di equilibrio successivi, in cui pressione e temperatura sono uniformi in tutte le parti del sistema.
Il lavoro è sempre interpretabile come l'area del grafico $p(V)$:

$$
W=\int p(V) \, dV  
$$
### T. Isobare
$$
\begin{align}
W&=p \Delta V  \\
\Delta U&=Q - p\Delta V
\end{align}
$$

### T. Isocore
$$
\begin{align}
W&=p \Delta V  \\
\Delta V&=0\ (\because \text{Isocora}) \\
\therefore W&=0 \\
\Delta U&=Q
\end{align}
$$

### T. Adiabatiche
$$
\begin{align}
Q&=0 \\
\therefore\Delta U&=-W
\end{align}
$$

### T. Isoterme
In un gas ideale:
$$
\Delta U=\frac{3}{2}nR\Delta T
$$
ma $\Delta T = 0$, dunque $Q=W$

$$
\begin{align}
W^{^B}_{_A}&=\int_{A}^B p(V) \, dV \\
&=\int_{A}^B \frac{nRT}{V} \, dV \\
&=nRT \int _{A}^B \frac{1}{V}\, dx \\
&=nRT\ln \frac{V_{B}}{V_{A}}  
\end{align}
$$