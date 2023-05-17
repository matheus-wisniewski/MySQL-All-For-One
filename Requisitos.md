# Desafios Iniciais
# 1. Exiba apenas os nomes dos produtos na tabela products.
## Resolução
[desafio 1](./desafio1.sql)
<br><br>

# 2. Exiba os dados de todas as colunas da tabela products.
## Resolução
[desafio 2](./desafio2.sql)
<br><br>

# 3. Escreva uma query que exiba os valores da coluna que representa a primary key da tabela products.
## Resolução
[desafio 3](./desafio3.sql)
<br><br>

# 4. Conte quantos registros existem na coluna product_name da tabela products.
## Resolução
[desafio 4](./desafio4.sql)
<br><br>

# 5. Monte uma query que exiba os dados da tabela products a partir do quarto registro até o décimo terceiro.
## Resolução
[desafio 5](./desafio5.sql)
<br><br>

# 6. Exiba os dados das colunas product_name e id da tabela products de maneira que os resultados estejam em ordem alfabética dos nomes.
## Resolução
[desafio 6](./desafio6.sql)
<br><br>

# 7. Mostre apenas os ids dos 5 últimos registros da tabela products (a ordenação deve ser baseada na coluna id).
## Resolução
[desafio 7](./desafio7.sql)
<br><br>

# 8. Faça uma consulta na tabela employees que retorne o nome completo da pessoa colaboradora (colunas first_name e last_name) com o nome full_name e também a localização completa (colunas city, state_province e address) com o nome location.
## Resolução
[desafio 8](./desafio8.sql)
<br><br><br>

# Desafios sobre filtragem de dados <br>
# 9. Mostre todos os valores de notes da tabela purchase_orders que não são nulos.
## Resolução
[desafio 9](./desafio9.sql)
<br><br>

# 10. Mostre todos os dados da tabela purchase_orders em ordem decrescente, ordenados por created_by em que o created_by é maior ou igual a 3 e ordene também os resultados pelo id de forma crescente, como critério de desempate para a ordenação.
## Resolução
[desafio 10](./desafio10.sql)
<br><br>

# 11. Exiba os dados da coluna notes da tabela purchase_orders em que seu valor de Purchase generated based on Order é maior ou igual a 30 e menor ou igual a 39.
## Resolução
[desafio 11](./desafio11.sql)
<br><br>

# 12. Mostre as submitted_date de purchase_orders em que a submitted_date é do dia 26 de abril de 2006.
## Resolução
[desafio 12](./desafio12.sql)
<br><br>

# 13. Mostre o supplier_id das purchase_orders em que o supplier_id seja 1 ou 3.
## Resolução
[desafio 13](./desafio13.sql)
<br><br>

# 14. Mostre os resultados da coluna supplier_id da tabela purchase_orders em que o supplier_id seja maior ou igual a 1 e menor ou igual 3.
## Resolução
[desafio 14](./desafio14.sql)
<br><br>

# 15. Mostre somente as horas (sem os minutos e os segundos) da coluna submitted_date de todos registros da tabela purchase_orders. No resultado, a hora extraída da coluna submitted_date deve ser chamada de submitted_hour.
## Resolução
[desafio 15](./desafio15.sql)
<br><br>

# 16. Exiba a submitted_date das purchase_orders que estão entre 2006-01-26 00:00:00 e 2006-03-31 23:59:59.
## Resolução
[desafio 16](./desafio16.sql)
<br><br>

# 17. Mostre os registros das colunas id e supplier_id das purchase_orders em que os supplier_id sejam tanto 1, ou 3, ou 5, ou 7.
## Resolução
[desafio 17](./desafio17.sql)
<br><br>

# 18. Mostre todos os registros de purchase_orders que tem o supplier_id igual a 3 e status_id igual a 2.
## Resolução
[desafio 18](./desafio18.sql)
<br><br>

# 19. Mostre a quantidade de pedidos que foram feitos na tabela orders pelo employee_id igual a 5 ou 6, e que foram enviados através do método(coluna) shipper_id igual a 2. No resultado, a coluna que contém a contagem de pedidos deve ser chamada de orders_count.
## Resolução
[desafio 19](./desafio19.sql)
<br><br>

# Desafios de manipulação de tabelas
# 20. Adicione à tabela order_details um registro com order_id: 69, product_id: 80, quantity: 15.0000, unit_price: 15.0000, discount: 0, status_id: 2, date_allocated: NULL, purchase_order_id: NULL e inventory_id: 129.
## Resolução
[desafio 20](./desafio20.sql)
<br><br>

# 21. Adicione com um único INSERT, duas linhas à tabela order_details com os mesmos dados do requisito 20.
## Resolução
[desafio 21](./desafio21.sql)
<br><br>

# 22. Atualize todos os dados da coluna discount, na tabela order_details, para 15.
## Resolução
[desafio 22](./desafio22.sql)
<br><br>

# 23. Atualize os dados da coluna discount da tabela order_details para 30, onde o valor na coluna unit_price seja menor que 10.0000.
## Resolução
[desafio 23](./desafio23.sql)
<br><br>

# 24. Atualize os dados da coluna discount da tabela order_details para 45, onde o valor na coluna unit_price seja maior que 10.0000 e o id seja um número entre 30 e 40.
## Resolução
[desafio 24](./desafio24.sql)
<br><br>

# 25. Delete todos os dados em que a unit_price da tabela order_details seja menor que 10.0000.
## Resolução
[desafio 25](./desafio25.sql)
<br><br>

# 26. Delete todos os dados em que a unit_price da tabela order_details seja maior que 10.0000.
## Resolução
[desafio 26](./desafio26.sql)
<br><br>

# 27. Delete todos os dados da tabela order_details.
## Resolução
[desafio 27](./desafio27.sql)