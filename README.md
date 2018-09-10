# Exercícios

Aqui constam os exercícios que me foram passados para resolver.

Os três primeiros são apenas páginas simples.

O de criação da API REST foi desenvolvido com o CAKE PHP, mas não foi adicionado nenhum tipo de biblioteca externa, bastando que se baixe e rode o projeto. Consta com em index.php que faz a listagem básica das tarefas incluidas no BD e um cliente teste para realizar requisições básicas para demonstrar o funcionamento da API.

Cliente: http://localhost/tarefas/index.php/client
Listagem Simples: http://localhost/tarefas

Crição do BD: CREATE  TABLE `api_rest`.`tarefas` (
  `id` INT NOT NULL AUTO_INCREMENT ,
  `trf_titulo` VARCHAR(45) NOT NULL ,
  `trf_descricao` VARCHAR(150) NOT NULL ,
  `trf_data_criacao` DATETIME NOT NULL ,
  `trf_prioridade` INT NOT NULL ,
  PRIMARY KEY (`id`) );

Popular BD: INSERT INTO tarefas (trf_titulo, trf_descricao, trf_data_criacao, trf_prioridade)
VALUES ('Teste 2', 'Tarefa Teste 2', NOW(), 2), ('Teste 3', 'Tarefa Teste 3', NOW(), 3), ('Teste 4', 'Tarefa Teste 4', NOW(), 1), ('Teste 5', 'Tarefa Teste 5', NOW(), 2), ('Teste 6', 'Tarefa Teste 6', NOW(), 3);
