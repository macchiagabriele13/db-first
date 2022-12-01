<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->

Table name: Cars

id: BIGINT | AI NOTNULL UNIQUE
model: VARCHAR(20) | NOTNULL
brand: VARCHAR(20) | NOTNULL
engine: VARCHAR(20) | NULL
color: VARCHAR(20) | NULL
price: DECIMAL (8,2) | NULL
year: YEAR | NOTNULL
description:TEXT | NULL
notes:TEXT | NULL