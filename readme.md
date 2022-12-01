Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


# Modello Struttura 

## Tabella ##


* vehicle_id_number | CHAR(17) | NOTNULL UNIQUE
* image | BLOB | NULL
* make | VARCHAR(20) | NOTNULL
* type ? | VARCHAR(20) | NULL
* model | VARCHAR(20) | NULL
* description | TEXT | NULL
* fabbrication_date | DATE | NOTNULL
* registration_year ? | YEAR |NULL 
* km | INT | NOTNULL
* engine_specs (cc, gear, power) | TEXT | NULL
* fuel_supply | VARCHAR(10) | NULL