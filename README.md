# Emails em português para o PERFEX CRM

### Instalação:

1. Faça um backup do seu banco de dados. SÉRIO!
2. Acesse o seu banco de dados com PHPMyAdmin ou similar, procure pelos emails em português do Brasil:

`SELECT * FROM `tblemailtemplates` WHERE `language` LIKE 'portuguese_br'`

3. Delete todos os resultados encontrados (se você usar PERFEX CRM maior que a versão 2.2.0, verifique se não foi adicionado nenhum email novo)
4. Insira os novos emails que estão no arquivo SQL deste repositório, executando ele como um comando SQL
5. Acesse seu Perfex -> Configurações -> Modelos de Email e clique em algum para ver se funcionou.

### Categorias de Email traduzidos:
- Tickets
- Orçamentos
- Faturas
- Nota de Crédito
- Tarefas
- Clientes
- Projetos
- Leads

### Falta traduzir emails relativos à:
- Contratos
- Assinaturas
- Propostas
- Colaboradores

### Observaçoes:
- "Tickets" são chamados de "Solicitações"
- "Discussões" são chamados de "Conversas"

PULL-REQUESTS SÃO BEM VINDOS
