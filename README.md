# db-hotel

* Seleziona tutti gli ospiti che sono stati identificati con la carta di identità
```
SELECT `name`, `lastname`, `document_type`
FROM `ospiti`
WHERE `document_type` = 'CI';
```
* Seleziona tutti gli ospiti che sono nati dopo il 1988
```
SELECT `name`, `lastname`, `date_of_birth`
FROM `ospiti`
WHERE `date_of_birth` > '1988-12-31';
```
* Seleziona tutti gli ospiti che hanno più di 20 anni (al momento dell’esecuzione della query)
```
SELECT `name`, `lastname`, `date_of_birth`
FROM `ospiti`
WHERE `date_of_birth` < '2000-05-12';
```
* Seleziona tutti gli ospiti il cui nome inizia con la D
```
SELECT `name`, `lastname`
FROM `ospiti`
WHERE `name` LIKE 'd%';
```
* Calcola il totale degli ordini accepted
```
SELECT `status`, COUNT(price) AS 'mumero_prenotazioni', SUM(price) AS 'incasso_totale'
FROM `pagamenti`
WHERE `status` = 'accepted';
```
* Qual è il prezzo massimo pagato?
* Seleziona gli ospiti riconosciuti con patente e nati nel 1975
* Quanti posti letto ha l’hotel in totale?