# Esercizi di DSP - 01

##### 1. Scrivi un programma che utilizzi i quattro operatori matematici in parallelo

```
import("stdfaust.lib");
process = +, -, *, /;
```

##### 2. Scrivi un programma che utilizzi i quattro operatori matematici in serie

```
import("stdfaust.lib");
process = +: -(1): *(1): /(1);
```

##### 3. Scrivi un programma che esegua due operazioni in sequenza e producano un segnale in uscita identico a quello in entrata

```
import("stdfaust.lib");
process = _+(0) : *(1);
```

##### 4. Scrivi un programma che abbia 4 segnali un entrata, ne dimezzi l'ampiezza e li porti in uscita su quattro canali separati

```
import("stdfaust.lib");
process = _ *(0.5), _ *(0.5), _ *(0.5), _ *(0.5);
```

##### 5. Scrivi un programma che abbia 4 entrate ed una sola uscita, somma delle 4 entrate.

```
import("stdfaust.lib");
process =
```
