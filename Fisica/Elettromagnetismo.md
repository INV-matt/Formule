# Campo Elettrostatico

La carica di un elettrone è $e = 1.6*10^{-19} C$. Ogni carica è un multiplo di $e$

## Forza di Coulomb
$$F=k \frac{q_{1}q_{2}}{r^2}$$

dove $k=8,99*10^9 \frac{Nm^2}{C^2}=\frac{1}{4 \pi \varepsilon_{0}}$ e $\varepsilon_{0} = 8,85 * 10^{-12} \frac{C^2}{Nm^2}$ 

## Flusso
$$\Phi(\vec{E})=\vec{E} \cdot \vec{A}=EA\cos \varphi$$
### Teorema di Gauss
Il flusso attraverso una superficie gaussiana è:
$$\Phi(\vec{E})=\frac{Q}{\varepsilon_{0}}$$

## Campo elettrostatico
In generale: $\vec{E}=\frac{\vec{F}}{q_{0}}$
Campo generato da una particella

$$E=\frac{1}{4\pi \varepsilon_{0}}\frac{Q}{r^2}$$

Campo in un condensatore
$$E = \frac{Q}{\varepsilon_{0}A}=\frac{\sigma}{\varepsilon_{0}}$$

Campo generato da una distribuzione piana infinita uniforme
$$E= \frac{\sigma}{2\varepsilon_{0}}$$

Campo generato da un file elettrico infinito uniforme
$$E = \frac{\lambda}{2\pi\varepsilon_{0}} \frac{1}{r}$$

Campo all'interno di una sfera piena uniforme di raggio $R$
$$E=\frac{q}{4\pi\varepsilon_{0}R^3} r$$

Campo all'esterno di un conduttore (Teorema di Coulomb)
$$E = \frac{\sigma}{\varepsilon_{0}}$$

## Energia potenziale e potenziale
Energia potenziale tra due cariche

$$U=\frac{1}{4\pi\varepsilon_{0}} \frac{q_{1}q_{2}}{r}$$

Energia potenziale in un condensatore

$$U=\mp qEd$$


Potenziale Elettrico

$$\begin{align}
V &= \frac{U}{q} \\
\Delta V&=\frac{\Delta U}{q}=-\frac{W}{q}
\end{align}$$


Potenziale in un campo radiale
$$V=\frac{1}{4\pi\varepsilon_{0}} \frac{Q}{r}$$

Potenziale in un condensatore
$$V=-\frac{E}{d}$$

## Circuitazione
$$\Gamma_{\gamma}(\vec{E})=\sum\Delta s_{i}E_{i}\cos\varphi_{i}$$

La circuitazione lungo un cammino chiuso è nulla.


## Condensatori
Campo interno: $E = \frac{\sigma}{\varepsilon_{0}}$
Capacità: $q = C \Delta V$, dove $C = \frac{A\varepsilon_{0}}{d}$
Energia del condensatore: $W=\frac{1}{2} q\Delta V$

### Condensatore equivalente
Se i condensatori sono in parallelo:
$$\begin{align}
&\begin{cases}
\Delta V=\Delta V_{1}=\Delta V_{2} =\dots=\Delta V_{n} \\
q= q_{1}+q_{2}+\dots+q_{n}
\end{cases} \\ \\
&C = \sum C_{i}
\end{align}$$

Se i condensatori sono in serie:
$$\begin{align}
&\begin{cases}
\Delta V=\Delta V_{1}+\Delta V_{2}+\dots+\Delta V_{n} \\
q=q_{1}=q_{2}=\dots=q_{n}
\end{cases} \\  \\
\frac{1}{C}=\sum \frac{1}{C_{i}}
\end{align}$$


L'energia del condensatore equivalente è la somma delle energie.


## Circuiti DC
L'intensità di corrente è $i = \frac{\Delta q}{\Delta t}$. Nei circuiti DC, $i$ è costante.

In un circuito, un generatore ha forza elettromotrice $\mathcal{E}=\frac{W}{q}=V$

Prima legge di Ohm:    $V=iR$
Seconda legge di Ohm: $R = \rho\frac{l}{A}$

Potenza assorbita da un circuito: $W=i\Delta V$

### Resistore equivalente
Se i condensatori sono in parallelo:
$$\begin{align}
&\begin{cases}
\Delta V=\Delta V_{1}=\Delta V_{2} =\dots=\Delta V_{n} \\
i= i_{1}+i_{2}+\dots+i_{n}
\end{cases} \\ \\
& \frac{1}{R} = \frac{1}{\sum R_{i}}
\end{align}$$

Se i condensatori sono in serie:
$$\begin{align}
&\begin{cases}
\Delta V=\Delta V_{1}+\Delta V_{2}+\dots+\Delta V_{n} \\
i=i_{1}=i_{2}=\dots=i_{n}
\end{cases} \\  \\
&R=\sum R{i}
\end{align}$$

La potenza assorbita dal resistore equivalente è la somma delle potenze.

### Leggi di Kirchhoff
Prima legge: In un nodo, la somma delle correnti entranti è uguale alla somma delle correnti uscenti

Seconda legge: In una maglia, la somma delle differenze di potenziale è 0



# Campo Magnetico
## Forza di Lorentz Danetz
$$\vec{F}=q\vec{v}\times \vec{B}$$

Una particella in un campo magnetico perpendicolare si muove di moto circolare:
$$\begin{align}
r &= \frac{mv}{qB} \\
T &= \frac{2\pi m}{qB} \\
\omega &= \frac{qB}{m}
\end{align}$$

Forza magnetica su filo percorso da corrente:
$$F = ilB\sin\varphi$$

Momento torcente su una spira:
$$\begin{align}
\tau&=BiA\sin\varphi \\
\mu&=iA
\end{align}$$


### Campi magnetici generati da correnti
Costante di permeabilità del vuoto: $\mu_{0}=4\pi*10^{-7} \frac{Tm}{A}$

Filo infinito percorso da corrente (Legge di Biot-Savart): 
$$B=\frac{\mu_{0}}{2\pi} \frac{i}{r}$$

Spira percorsa da corrente:
$$B = \frac{\mu_{0}N}{2} \frac{i}{r}$$

Solenoide: 
$$B=\mu_{0} \frac{N}{L} i$$

## Flusso e circuitazione/integrale di linea
Il flusso di un campo magnetico attraverso una superficie gaussiana è nullo (Teorema di Gauss).
$$\Phi_{S}(\vec{B})=0$$

La circuitazione di un campo magnetico attraverso un circuito chiuso (Teorema di Ampere) vale:
$$\Gamma_{\gamma}(\vec{B})=\mu_{0} \sum i_{k}$$
dove $i_k$ sono le correnti concatenate a $\gamma$


# Induzione elettromagnetica
Si nota che la variazione del flusso di B genera una corrente elettrica indotta.
In un campo elettrico, vale $\mathcal{E}=\Gamma_{\gamma}(\vec{E})$
Un campo elettrico indotto non è conservativo: $\Gamma_{\gamma}(\vec{E}) \neq 0$

## Legge di Faraday-Neumann-Lenz
$$\begin{align}
\mathcal{E}&=- \frac{\Phi(B)}{\Delta t} \\  \\
\mathcal{E}&=- \frac{d\Phi(B)}{dt}
\end{align}$$

## Mutua induzione
$$\begin{align}
\Phi_{2}(B)=Mi_{1} \\
\mathcal E_{2} = -M \frac{\Delta i_{1}}{\Delta t_{2}}
\end{align}$$

## Autoinduzione
$$\begin{align}
\Phi(B) = Li \\
\mathcal E = -L \frac{\Delta i}{\Delta t}
 \end{align}$$

In un solenoide, $L=\mu_{0} \frac{N^2A}{l}$

## Circuiti RL
Costante di tempo induttiva: $\tau=\frac{L}{R}$

Corrente di chiusura: 
$$i(t)=\frac{V}{R}(1-e^{-t/\tau})$$

Corrente di apertura: 
$$i(t)= \frac{V}{R} e^{-t/\tau}$$
Energia immagazinata:
$$W_{L}=\frac{1}{2}Li^2$$

## Circuiti RC
Costante di tempo capacitiva: $\tau=RC$

Corrente di carica:
$$i(t)=\frac{V}{R} e^{-t/\tau}$$

Corrente di scarica:
$$i(t)=-\frac{V}{R}e^{-t/\tau}$$
