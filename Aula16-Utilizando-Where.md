# Exemplo de clausula where
* é ideal para selecionar dados especificos, fazendo filtros
```sql
    --Buscando apenas com nome Adam
    SELECT * FROM Clientes
    WHERE  Nome  = 'Adam'
    ORDER BY Nome, Sobrenome
    --Buscando apenas Adam e Reynolds
    SELECT * FROM Clientes
    WHERE  Nome  = 'Adam' AND  Sobrenome ='Reynolds'
    ORDER BY Nome, Sobrenome
    --Buscando Com  Adam ou Reynolds
    SELECT * FROM Clientes
    WHERE  Nome  = 'Adam' OR  Sobrenome ='Reynolds'
    ORDER BY Nome, Sobrenome

    --Buscando clientes que aceita comunicados
    SELECT * FROM Clientes
    WHERE  AceitaComunicados = 1
    ORDER BY Nome, Sobrenome

```
