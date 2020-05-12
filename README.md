# db-hote

* Seleziona tutti gli ospiti che sono stati identificati con la carta di identità
```
SELECT `name`, `lastname`, `document_type`
FROM `ospiti`
WHERE `document_type` = 'CI';
```
* Seleziona tutti gli ospiti che sono nati dopo il 1988
* Seleziona tutti gli ospiti che hanno più di 20 anni (al momento dell’esecuzione della query)
* Seleziona tutti gli ospiti il cui nome inizia con la D
* Calcola il totale degli ordini accepted
* Qual è il prezzo massimo pagato?
* Seleziona gli ospiti riconosciuti con patente e nati nel 1975
* Quanti posti letto ha l’hotel in totale?