# Database Macchine_Usate

## Data types:
- strings: [varchar(number), char(number), text, longtext]
- numbers: [tinyint, smallint, mediumint, int, bigint]
- decimals: [float(i,d), double(i,d), decimal(i,d)]
- dates: [datetime, date, time, year, timestamp]

## Attributes:
- NULL / NOT NULL
- DEFAULT(value)
- PRIMARY_KEY
- AUTO_INCREMENT
- UNIQUE

## Entity name: Macchina

## Table name: Macchine

## Table columns:
- Auto            | BIGINT, PRIMARY_KEY, AUTO_INCREMENT, NOTNULL, UNIQUE, INDEX
- marca           | VARCHAR(15), NOTNULL, INDEX
- modello         | VARCHAR(30), NOTNULL, INDEX
- anno_di_rilascio| YEAR, INDEX
- kms             | MEDIUMINT, INDEX
- prezzo          | decimal(6,2)
- colore          | VARCHAR(20), NOTNULL,
- alimentazione   | VARCHAR(20), NOTNULL, INDEX
- allestimento    | VARCHAR(20), NOTNULL, INDEX
- descrizione     | TEXT, NULLABLE
- foto            | VARCHAR(200), NOTNULL
- trasmissione    | VARCHAR(20), NOTNULL, INDEX