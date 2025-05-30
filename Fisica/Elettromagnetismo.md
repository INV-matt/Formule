# Campo Elettrostatico

La carica di un elettrone è $e = 1.6*10^{-19} C$. Ogni carica è un multiplo di $e$

## Forza di Coulomb

$$F=k \frac{q_{1}q_{2}}{r^2}$$

dove 

$$k=8,99*10^9 \frac{Nm^2}{C^2}=\frac{1}{4 \pi \varepsilon_{0}}$ e $\varepsilon_{0} = 8,85 * 10^{-12} \frac{C^2}{Nm^2}$$

## Flusso

$$\Phi(\vec{E})=\vec{E} \cdot \vec{A}=EA\cos \varphi$$


### Teorema di Gauss

Il flusso attraverso una superficie gaussiana è:

$$\Phi(\vec{E})=\frac{Q}{\varepsilon_{0}}$$

## Campo elettrostatico
In generale:

$$\vec{E}=\frac{\vec{F}}{q_{0}}$$

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
&\frac{1}{C}=\sum \frac{1}{C_{i}}
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
In un campo elettrico, vale 

$$\mathcal{E}=\Gamma_{\gamma}(\vec{E})$$

Un campo elettrico indotto non è conservativo: 

$$\Gamma_{\gamma}(\vec{E}) \neq 0$$

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

## Circuiti AC
Un alternatore genera un'energia elettrica che varia nel tempo trasformando energia meccanica.

$$\begin{align}
\mathcal E(t)&=\omega AB \sin(\omega t)=\mathcal E_{0}\sin(\omega t) \\
i(t)&=\frac{\omega AB}{R}\sin(\omega t)=i_{0}\sin(\omega t) \\
P(t)&=i_{0}\mathcal E_{0}\sin^2(\omega t) \\
\bar{P}&=\frac{1}{2}i_{0}\mathcal E_{0}
\end{align}$$

## Trasformatore
$$\frac{\mathcal E_s}{\mathcal E_p}=\frac{N_{s}}{N_{p}}=\frac{I_{p}}{I_{s}}$$



# Leggi di Maxwell
I campi elettrici e magnetici sono regolati da quattro equazioni fondamentali:

$$\begin{align}
\Phi_{S}(\vec{E})&=\frac{Q}{\varepsilon_{0}} \\
\Phi_{S}(\vec{B})&=0 \\
\Gamma_{\gamma}(\vec{E})&=-\frac{d\Phi_{S}(\vec{B})}{dt} \\
\Gamma_{\gamma}(\vec{B})&=\mu_{0}\sum i_{k}+\varepsilon_{0}\mu_{0}\frac{d\Phi_{S}(\vec{E})}{dt} 
\end{align}$$

# Onde Elettromagnetiche
Le oscillazioni dei campi elettrici e magnetici si propagano nello spazio sotto forma di onda elettromagnetica. 
Questa si propaga nel vuoto con una velocità 

$$v=\frac{1}{\sqrt{ \varepsilon_{0}\mu_{0} }}=c$$

e nei materiali con velocità 

$$v_{r}=\frac{c}{\sqrt{\varepsilon_{r}\mu _{r}}}$$

Inoltre vale:

$$E=vB$$
dove $v$ è la velocità di propagazione dell'onda. In particolare, nel vuoto questo rapporto diventa:

$$\begin{align}
E=&cB \\
B^2=&\mu_{0}\varepsilon_{0}E^2
\end{align}$$

Inoltre:

$$v=\frac{\lambda}{T}=\lambda f$$

Nel passaggio da un materiale all'altro, $f$ rimane invariata, dunque $v/\lambda$ rimane invariato. Se un'onda rallenta quando entra in un materiale, la sua lunghezza d'onda diminuisce.

## Densità di energia trasportata dalle onde EM
In generale:

$$\begin{align}
\delta _{E}&=\frac{1}{2}\varepsilon_{0}E^2 \\
\delta _{B}&=\frac{1}{2\mu_{0}}B^2 \\
\end{align}$$

Poiché $\varepsilon_{0}E^2=B^2/\mu_{0}$

$$\delta(t)=\frac{1}{2}\varepsilon_{0}E(t)^2+\frac{1}{2\mu_{0}}B(t)^2=\varepsilon_{0}E(t)^2=\frac{1}{\mu_{0}}B(t)^2$$

Se l'onda è armonica:

$$\begin{align}
\delta(t)&=\varepsilon_{0}E_{0}^2\sin^2(\omega t)=\frac{1}{\mu_{0}}B_{0}^2\sin^2(\omega t) \\
\bar{\delta}&=\frac{1}{2}\varepsilon_{0}E_{0}^2=\frac{1}{2\mu_{0}}B_{0}^2 \\
\bar{\delta}&=\varepsilon_{0}E_{EF}^2=\frac{1}{\mu_{0}}B_{EF}^2
\end{align}$$


## Intensità dell'onda EM
$$I=\frac{W}{A\Delta t}$$
dove $W$ è l'energia che arriva in un tempo $\Delta t$ su una superficie $A$ posta perpendicolarmente ai raggi.

$$W=Ac\Delta t \bar{\delta}$$

Da cui

$$\bar{I}=c\bar{\delta}$$

Se la sorgente è una sorgente puntiforme isotropa:

$$I=\frac{P_{tot}}{4\pi r^2}$$

Da cui:

$$\begin{align}
\frac{\bar{P}}{4\pi r^2}&=\frac{1}{2}c \varepsilon_{0}E_{0}^2 \\
E_{0}&=\sqrt{ \frac{\bar{P}}{2\pi\varepsilon_{0} c} }\cdot \frac{1}{r} \\
B_{0}&=\sqrt{ \frac{\mu_{0}\bar{P}}{2\pi c} }\cdot \frac{1}{r}
\end{align}$$

## Quantità di moto e pressione dell'onda EM

$$\begin{align}
\Delta q&=\frac{\Delta W}{c} \text{ se l'onda è totalmente assorbita}\\
\Delta q&=2 \frac{\Delta W}{c} \text{ se l'onda è totalmente riflessa}
\end{align}$$

Dove $\Delta W$ è la quantità di energia assorbita.

Per il teorema dell'impulso:

$$p=\frac{F}{A}=\frac{\Delta q}{A\Delta t}=k\frac{\Delta W}{cA\Delta t}=k\bar{\delta},\ 1\leq k\leq 2$$

In particolare, la pressione di un'onda totalmente assorbita è $p=\bar{\delta}$ e di una totalmente riflessa $p=2\bar{\delta}$
