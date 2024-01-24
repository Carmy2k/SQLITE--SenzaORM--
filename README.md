# SQLite senza ORM - Esempi CRUD con Person

Benvenuto nel repository che ti guiderà attraverso l'utilizzo di SQLite senza un ORM, concentrandoci sulle operazioni CRUD su una tabella "Person". 🚀

## Setup Iniziale

Assicurati di avere SQLite installato sul tuo sistema. Puoi farlo seguendo la guida ufficiale [qui](https://www.sqlite.org/download.html).

## Esempi di Utilizzo

### 1. Creazione del Database


```
python
CREATE TABLE Person (
    id INTEGER PRIMARY KEY,
    name TEXT,
    age INTEGER
);

```

### 2. Inserimento di una Persona


```
python
INSERT INTO Person (name, age) VALUES ('John Doe', 30);
```

### 3. Lettura di tutte le Persone


```
python
SELECT * FROM Person;

```
