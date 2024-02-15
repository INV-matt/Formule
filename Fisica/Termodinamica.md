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

Graficamente, il lavoro tra gli stati A e B è pari a:

$$
\begin{align}
W_{_A}^{^B}&=\int_A^B p(V) \, dV \\
&=\int_A^B \frac{nRT}{V} \, dV \\
&=nRT \int _A^B \frac{1}{V}\, dx \\
&=nRT\ln \frac{V_B}{V_A}  
\end{align}
$$

# Secondo principio
- **E. di Kelvin**: è impossibile realizzare una trasformazione in cui l'unico risultato sia quello di convertire in lavoro tutto il calore assorbito da un'unica sorgente
- **E. di Clausius**: è impossibile realizzare una trasformazione in cui l'unico risultato sia il passaggio di calore da un corpo con una data temperatura a un corpo con una temperatura maggiore

## Teorema di Carnot e macchina di Carnot
Una trasformazione è reversibile se il sistema e il suo ambiente possono essere riportati nell'identico stato in cui si trovavano inizialmente, effettuando la trasformazione a ritroso.

**T. di Carnot**: nessuna macchina termica irreversibile che opera tra due serbatoi a temperatura costante può avere un rendimento maggiore di una macchina reversibile che opera tra le stesse temperature.

Si può dimostrare che in una macchina di Carnot: 
$$
\eta_{Carnot} = 1 - \frac{| Q_{f} |}{Q_{c}} = 1 - \frac{| T_{f} |}{T_{c}}
$$

# Entropia
È un modo per quantificare la degenerazione della qualità dell'energia in un processo. Infatti un'energia termica ad alta temperatura è più "pregiata" della stessa a bassa temperatura in quanto permette rendimenti più elevati.
La variazione dell'entropia è il rapporto tra il calore scambiato dal sistema e la temperatura assoluta a cui viene scambiato.

$$
\Delta S=\left( \frac{Q}{T} \right)_{R}
$$
Il pedice $R$ indica che la trasformazione deve essere reversibile.
Si può dimostrare che $\Delta S = 0$ in una trasformazione reversibile e $\Delta S > 0$ in una trasformazione irreversibile.
