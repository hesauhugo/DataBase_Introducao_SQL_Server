# Executando queries com like
* utilizar para pegar clientes que comecem com um determinada letra
```sql

    --Trazendo todos cliente que comecem com a letra G
    SELECT * FROM Clientes
    WHERE  Nome LIKE 'G%'
    ORDER BY Nome, Sobrenome

    --Trazendo todos cliente que TEM a letra G nome
    SELECT * FROM Clientes
    WHERE  Nome LIKE '%G%'
    ORDER BY Nome, Sobrenome
```