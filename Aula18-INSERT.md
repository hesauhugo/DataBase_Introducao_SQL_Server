# Realizando comando insert
* Como inserir registro no banco de dados

```sql

    --inserindo um registro
    INSERT INTO CLIENTES 
    (Nome,Sobrenome,Email,AceitaComunicados, DataCadastro)
    VALUES 
    ('ENZO','GABRIEL','enzo.gabriel@gmail.com',1,GETDATE())
    
    -- CONSULTANDO O REGISTRO INCLUIDO
    SELECT * FROM Clientes WHERE Nome = 'ENZO'

```
