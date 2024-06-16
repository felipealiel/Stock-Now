# User story
## Funcionalidade 1: Registrar novos produtos
Como analista de estoque, eu quero cadastrar novos produtos, para complementar meu estoque.

**Critérios de aceitação :** Os usuários podem cadastrar apenas 1 produto por vez.
Os usuários não deverão cadastrar o mesmo produto mais de 1 vez, mesmo que mude as datas de entrada.

## Funcionalidade 2: Registrar a data de validade dos produtos
Como estoquista, eu quero poder registrar a data de validade dos produtos, para retirar os produtos que já estão próximos da validade.

**Critérios de aceitação:** O sistema irá notificar quando alguns produtos  estiverem com a validade próxima.

**Regras de negócio:** Os produtos devem ser retirados das prateleiras 1 semana antes de vencerem.

## Funcionalidade 3: Emissão de relatórios
Como especialista em inventário, eu quero receber relatórios diários sobre todas  as vendas do dia, para manter um controle de estoque.

**Critérios de aceitação:** O sistema deve notificar quando algum produto foi devolvido ou a venda cancelada.

**Regras de negócio:** O cliente pode devolver o produto para o estoque em até uma semana.

## Funcionalidade 4: Contagem de produtos
Como especialista em inventário, eu quero receber um relatório relatando a quantidade total de produtos que entraram, saíram ou que ainda estão disponíveis durante a semana, para ter um controle das vendas da semana.

**Critérios de aceitação:** Se um produto estiver em pouca quantidade o sistema deverá notificar.

## Funcionalidade 5: Alerta para falta de produtos
Como especialista em inventário, eu quero receber um alerta sempre que um produto estiver em falta, para que seja solicitada a reposição.

**Critérios de aceitação:** O sistema deverá garantir que os usuários saibam que o produto está com uma quantidade mínima, antes que ele acabe.

## Funcionalidade 6: Totalizar gastos
Como analista de estoque, eu quero ser informado sobre a quantidade total de gastos de cada produto dentro do estoque, para obter a margem de lucro.

**Critérios de aceitação:** O sistema deve garantir que o produto seja no mínimo 15% a mais que o valor inicial.
Regras de negócio: A margem de lucro sobre cada produto, não deverá ultrapassar 100%.

## Funcionalidade 7: Codificação
Como estoquista, eu quero que um código de identificação seja gerado para cada novo produto registrado, para facilitar a leitura de código  no caixa .

**Critérios de aceitação:** Não pode haver 2 produtos com o mesmo código. 

## Funcionalidade 8: Listagem por categoria
Como estoquista, eu quero receber  listas dos produtos divididos por categorias nas quais foram registrados, para diferenciar melhor os produtos.

**Critérios de aceitação:** Cada categoria só deve ter produtos que possuem semelhanças.

## Funcionalidade 9: Cadastro
Como analista de estoque , eu quero poder realizar o cadastro de novos estoquistas, para aumentar a rapidez e o desenvolvimento do controle de estoque.

**Critérios de aceitação:** Somente o analista de estoque pode cadastrar um novo funcionário.

**Regras de negócio:** O funcionário deve ter no mínimo 18 anos, para começar a trabalhar.

## Funcionalidade 10: Tutorial
Como funcionário, eu quero ter acesso a um tutorial para usar o app, para que possa utilizá-lo da forma correta.

**Critérios de aceitação:** O tutorial não deverá conter nenhum dado empresarial do sistema, apenas as suas funcionalidades.

## Funcionalidade 11: Controle de gastos
Como analista de estoque, eu quero ter uma comparação de gastos mensais, para saber se houve aumento ou diminuição da taxa de gastos.

**Critérios de aceitação:** O controle de gastos deve ser gerado em forma de relatório, relatando junto com tudo que foi vendido durante o mês. 

## Funcionalidade 12: Controle de segurança 
Como gerente, eu quero que seja gerado um código de segurança para cada novo funcionário registrado, para controlar os acessos.

**Critérios de aceitação:** A cada 6 meses, cada funcionário terá um código novo.

**Regras de negócio:** Ao ser desligado da empresa, o código será desativado. 



