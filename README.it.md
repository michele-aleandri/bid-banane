# Puerto Banana – Regole (2–6 giocatori)

[Gioca](https://michele-aleandri.github.io/bid-banane/) · [English version](README.md)

## Obiettivo

Essere il primo giocatore a raggiungere 200 banane (punti stock). Se più giocatori raggiungono 200 o più nello stesso round, condividono la vittoria.

## Preparazione

- Ogni giocatore parte con 10 banane (stock).
- Posiziona i segnalini di tutti i giocatori sui rispettivi valori di stock.

## Round

Ogni round segue la stessa sequenza:

1. **Determinare la posta in palio**
   - Il numero di banane messe all'asta in questo round è pari allo stock più alto attualmente posseduto da un giocatore.

2. **Offerte segrete**
   - Tutti i giocatori offrono un numero intero non negativo (≥ 0).
   - Le offerte restano segrete finché tutti non sono pronti, poi vengono rivelate contemporaneamente.
   - I giocatori non pagano banane per fare un'offerta.

3. **Risoluzione dell'asta**
   Ci sono tre casi:

   **A. Parità per l'offerta più alta**
   - I giocatori in parità si dividono equamente la posta (arrotondando per difetto).
   - Non vengono pagati bonus.

   **B. Una sola offerta più alta**
   - Quel giocatore vince la posta e la aggiunge al proprio stock.
   - Poi deve pagare un bonus pari alla differenza tra la sua offerta e la seconda offerta più alta.
   - Se più giocatori sono in parità per il secondo posto, il bonus viene diviso equamente tra loro (arrotondando per difetto per ciascun giocatore).

   **C. Se il vincitore non può pagare il bonus**
   - La vincita non viene mantenuta.
   - Con 3–6 giocatori: il suo stock scende a 0.
   - Con 2 giocatori: il suo stock rimane invariato (non viene ridotto).
   - Quel giocatore viene escluso dall'asta e il successivo miglior offerente tenta di risolvere l'asta come nuovo vincitore.
   - Si continua finché qualcuno riesce a pagare o resta un solo giocatore.
   - Se ne resta uno solo, ottiene l'intera vincita e non paga alcun bonus.

## Fine della partita

- La partita termina alla fine di un round in cui almeno un giocatore ha 200 o più di stock.
- Vincono il giocatore (o i giocatori) con più banane.
- I pareggi sono vittorie condivise.

*Al termine della partita puoi scaricare un file con il resoconto di tutte le offerte e dei pagamenti.*
