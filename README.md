# DB First

Esercizio di oggi: DB First

nome repo: db-first

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

# Tabella

Colonne | Tipo | Attributi
--- | --- | --- |
id | BIGINT | PRIMARY_KEY, AUTO_INCREMENT
Targa | VARCHAR(10) | NULL, UNIQUE
Numero Telaio | CHAR(17) | NOTNULL, UNIQUE
Marca | VARCHAR(20) | NOTNULL
Modello | VARCHAR(20) | NOTNULL
Allestimento | VARCHAR(20) | NULL
Chilometraggio | MEDIUMINT | NOTNULL
Anno Immatricolazione | DATE | NOTNULL
Tipo di Cambio | CHAR(3) | NOTNULL
Carburante | VARCHAR(9) | NOTNULL
Cilindrata | VARCHAR(4) | NOTNULL
Cilindri | TINYINT | NULL
Peso | MEDIUMINT | NULL
Porte | TINYINT | NOTNULL
Posti | TINYINT | NOTNULL
Colore Carrozzeria | VARCHAR | NULL
Prezzo | FLOAT(9,2) | NULL
Numero Proprietari | TINYINT | NOTNULL, DEFAULT(1)
Cerchi in Lega | TINYINT/BOOL | NULL
Sensori di parcheggio | TINYINT/BOOL | NULL
AirBag | TINYINT/BOOL | NULL
Revisione | DATE | NOTNULL
Potenza(CV) | TINYINT | NULL