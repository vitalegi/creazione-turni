# README

## Configurazione

- Colonna E, modificare M1 / M2 / M3 con i nomi delle macro-aree, celle arancioni ![icon](https://placehold.it/15/ff8000/000000?text=+)
- Colonna F, modificare A1 / A2 / A3 / .. / C1 con i nomi delle aree, celle rosse ![icon](https://placehold.it/15/ff0000/000000?text=+)
- Foglio "Conf", rinominare colonne A e B come fatto sopra. I nomi devono essere uguali.
- Colonna G, modificare P1/ .. / P3 con i nomi delle risorse, celle celesti ![icon](https://placehold.it/15/00ffff/000000?text=+)
- Riga 3, imposta numero di auto disponibili per ogni turno, celle verdi ![icon](https://placehold.it/15/006600/000000?text=+)
- Colonne O:Q, "Attesi Max" (celle lilla ![icon](https://placehold.it/15/ff66ff/000000?text=+)): Per ogni risorsa è possibile indicare:
  - Tot: numero di turni da fare
  - #M: numero di mattine da fare
  - #P: numero di pomeriggi da fare
  
  Per una risorsa a 36h, indicare 5 / 5 / 5

  Per una risorsa che fa solo mattine, 5 / 5 / 0
  
  Per una risorsa che lavora solo 4 giorni, 4 / 4 / 4

## Utilizzo

- Cancellare i vari M / P dal calendario, eliminando le voci una per volta. NON selezionare parti della tabella e poi eliminare, ci sono campi nascosti che devono rimanere. celle verdi ![icon](https://placehold.it/15/66ff66/000000?text=+)
- Riempire il calendario con M/P. Se qualche vincolo non sarà rispettato, la cella corrispondente si colorerà di rosso.
- Una volta completato, nel foglio "Stampabile" trovi la versione per la stampa
