# SQLite senza ORM - Esempi CRUD con Person

Benvenuto nel repository che ti guiderà attraverso l'utilizzo di SQLite senza un ORM, concentrandoci sulle operazioni CRUD su una tabella "Person". 🚀

## Setup Iniziale

Assicurati di avere SQLite installato sul tuo sistema. Puoi farlo seguendo la guida ufficiale [qui](https://www.sqlite.org/download.html).

## Esempi di Utilizzo

### 1. Creazione del Database

```sql
CREATE TABLE Person (
    id INTEGER PRIMARY KEY,
    name TEXT,
    age INTEGER
);
```

### 2. Inserimento di una Persona

```sql
INSERT INTO Person (name, age) VALUES ('John Doe', 30);
```

### 3. Lettura di tutte le Persone

```sql
SELECT * FROM Person;
```

### 4. Aggiornamento di una Persona

```sql
UPDATE Person SET age = 31 WHERE name = 'John Doe';
```

### 5. Cancellazione di una Persona

```sql
DELETE FROM Person WHERE name = 'John Doe';
```

## Contribuisci

Se vuoi migliorare questo repository, sentiti libero di inviare una pull request! 🎉

Grazie per essere qui e divertiti a esplorare SQLite senza ORM con operazioni CRUD su una tabella Person! 😊
