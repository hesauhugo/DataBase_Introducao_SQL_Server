# Inserindo registro omitindo colunas
* passando apenas a informação de values sem passar o nome das colunas
* vantagem é que tem uma sintaxe mais enxuta
* desvantagem é que você precisa obedecer a ordem que está na tabela

```sql 
    INSERT INTO CLIENTES 
    VALUES 
    ('ENZO','MIGUEL','enzo.miguel@gmail.com',1,GETDATE())
```