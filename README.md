# ex-express-api-crud-relationships

## Esercizio

Per l'esercizio di oggi, partendo dal lavoro svolto ieri, aggiungeremo i seguenti modelli con le relative relazioni col modello `Post`:

1. **Category** (one-to-many): 
   - Ogni `Post` deve avere una categoria associata, e una categoria può avere più `Post` associati.
   
2. **Tags** (many-to-many): 
   - Ogni `Post` può avere uno o più tag associati, e ogni `Tag` può avere uno o più `Post` associati.

Successivamente, aggiungeremo la validazione dei dati utilizzando **Express Validator** alle rotte del nostro blog.

Infine, ci assicureremo che le richieste di lettura `GET` restituiscano anche la categoria e i tags di ogni singolo `Post`.

### Piccolo suggerimento
Se avete già popolato la tabella dei `posts`, indicate il campo `categoryId` come nullable o con un valore di default, altrimenti avrete un errore in fase di migrazione.

## BONUS
1. Implementare le operazioni di CRUD per il modello `Category`.
2. Implementare le operazioni di CRUD per il modello `Tag`.