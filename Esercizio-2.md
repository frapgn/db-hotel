# DB-HOTEL - Esercizio 2
##Group by
- Conta gli ospiti raggruppandoli per anno di nascita
```
SELECT YEAR(date_of_birth), COUNT(date_of_birth) FROM `ospiti` 
GROUP BY YEAR(date_of_birth)
```

- Somma i prezzi dei pagamenti raggruppandoli per status
```
SELECT `status`, SUM(`price`) FROM `pagamenti`
GROUP BY `status` 
```

- Conta quante volte è stata prenotata ogni stanza
```

```

- Fai una analisi per vedere se ci sono ore in cui le prenotazioni sono più frequenti
```

```

- Quante prenotazioni ha fatto l’ospite che ha fatto più prenotazioni?
```

```

##Join
- Come si chiamano gli ospiti che hanno fatto più di due prenotazioni?
```

```

- Stampare tutti gli ospiti per ogni prenotazione
```

```

- Stampare Nome, Cognome, Prezzo e Pagante per tutte le prenotazioni fatte a Maggio 2018
```

```

- Fai la somma di tutti i prezzi delle prenotazioni per le stanze del primo piano
```

```

- Prendi i dati di fatturazione per la prenotazione con id=7
```

```

- Le stanze sono state tutte prenotate almeno una volta? (Visualizzare le stanze non ancora prenotate)
```

```
