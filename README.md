# Portata Tubo Scarico — Formula di Manning

Calcolatore idraulico per tubi a sezione circolare piena. Pagina HTML singola, zero dipendenze, nessun build step.

## Utilizzo

Apri `index.html` nel browser. Nessun server necessario.  
O usa il link qui: https://marchiosim.github.io/portata-acqua-tubo/

## Parametri

- **Diametro interno** — da 50 a 800 mm
- **Pendenza** — da 0.1% a 25%
- **Materiale** — PVC liscio, grès, calcestruzzo, muratura, plastica corrugata (SN4/SN8), terreno

## Formula

```
Q = (1/n) · A · R^(2/3) · S^(1/2)
```

Moto uniforme secondo Manning (1891). Valida per sezione circolare a piena sezione, regime stazionario.

## Avvisi automatici

- Velocità < 0.6 m/s → rischio depositi
- Velocità > 4 m/s → rischio erosione

## Limiti

Non tiene conto di perdite localizzate (curve, giunti, imbocco), moto vario o sezione parzialmente piena.