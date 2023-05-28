# Ordenando os dados
* é possivel ordenar os dados de forma crescente ou descrescente
```sql
    --Ordenando nome de forma crescente
    SELECT * FROM Clientes ORDER BY Nome
    --Ordenando sobrenome de ordem descrescente
    SELECT * FROM Clientes ORDER BY Sobrenome DESC
    --Ordenando por nome e sobrenome
    SELECT * FROM Clientes ORDER BY Nome, Sobrenome
```
