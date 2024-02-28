@qui Ciao ragazzi,
Esercizio di oggi: DB First
nome repo: db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.

colonne | Tipo | Attributi
--- | --- | --- 
id | BIGINT | PRIMARY_KEY, AUTO_INCREMENT,
marca | VARCHAR | NOTNULL
VIN | CHAR(17) | NOTNULL, UNIQUE
modello | VARCHAR | NOTNULL
anno_fabbricazione | YEAR | NOTNULL
kilometri_percorsi | INT | NOTNULL
prezzo | BIGINT | NOTNULL
condizioni | CHAR(1) | NOTNULL
tipo_alimentazione | CHAR(1) | NULL/NOTNULL
colore | VARCHAR | NULL
trasmissione(manuale/automatico) | BOOL/CHAR(1) | NOTNULL, DEFAULT(0)
numero_posti | TINYINT | NOTNULL, DEFAULT(5)
tipologia(suv, van, utilitaria ecc.) | CHAR(1) | NULL
