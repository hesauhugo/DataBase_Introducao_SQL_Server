# Realizando update
* serve para atualizar alguma informação de da tabela
* atenção no where sempre usar o id
* uma dica é primeiro fazer um select com `where` caso de certo usa no where
```sql 
    --atualizando apenas um campo de um id
    UPDATE Clientes
    SET Email = 'emailatualizado@hotmail.com'
    WHERE id = 1000
    --atualizando dois campos de um id
    UPDATE Clientes
    SET Email = 'emailatualizado@hotmail.com', AceitaComunicados = 1
    WHERE id = 1000
    
    --avaliando
    SELECT * FROM Clientes WHERE Id = 1000

```
