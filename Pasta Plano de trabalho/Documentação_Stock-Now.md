1. **Descrição Geral do Projeto**  
   1.1 **Nome do Projeto**  
   Stock Now  
     
   1.2 **Descrição do Produto**  
   O Stock Now é um aplicativo de gerenciamento de estoque tanto de empresas de grande porte quanto de pequenos empreendedores ou até mesmo um usuário doméstico.  
     
   1.3 **Objetivo**  
   Desenvolvimento de um aplicativo para controle de estoque que ajude empresas e empreendedores a gerenciar de forma eficiente seus inventários.  
     
   1.4 **Motivação**  
   Com o ritmo acelerado da sociedade moderna as empresas buscam otimizar a forma com que utilizam seus recursos através de um gerenciamento preciso e confiável. E o Stock Now foi desenvolvido para atender essa demanda.  
     
   1.5 **Equipe de Desenvolvimento**  
* Felipe Aliel Ramos da Silva  
* Marcos Gabriel Peixoto  
* Laís Samily Xavier da Silva  
* Tiago dos Santos Mendonça  
* Ana Clarissy de Souza Soares


	1.6 **Descrição dos Usuários Finais**

Exemplo:

Os usuários finais do aplicativo são:

* Clientes Pessoas Físicas que utilizam o app para gerenciar seus estoques.   
* Clientes Pessoas Jurídicas (empresas) que utilizam funcionalidades específicas para otimizar o gerenciamento de seu inventário.


  

2. **Escopo**  
   2.1 **Escopo Específico**

                 2.1.1 **Requisitos Funcionais**

		

| ID | Descrição  | Prioridade |
| :---- | :---- | :---- |
| RF001 | O sistema deve permitir o cadastro de novos produtos | Essencial |
| RF002 | O sistema deve atualizar a quantidade e lote quando um produto já estiver cadastrado. | Importante |
| RF003 | O sistema deve permitir registrar a data de validade dos produtos. | Essencial |
| RF004 | O sistema deve notificar quando algum produto estiver próximo da data de validade | Essencial |
| RF005 | O sistema deve gerar relatórios de vendas, estoque e gastos. | Essencial |
| RF006 | Os relatórios devem conter o nome do produto, entrada, saída e estoque atual e a quantidade vendida. | Importante |
| RF007 | O sistema deve notificar quando houver devolução ou cancelamento de venda.  | Essencial |
| RF008 | O sistema deve enviar relatórios semanais por e-mail. | Importante |
| RF009 | O relatório deve conter data de início e fim da semana, quantidade de produtos vendidos e total arrecadado. | Importante |
| RF010 | O sistema deve enviar solicitação de reposição quando um produto estiver em pouca quantidade. | Essencial |
| RF011 | O sistema deve gerar uma notificação quando um produto estiver em falta. | Essencial  |
| RF012 | O sistema deve calcular a margem de lucro sobre cada produto. | Importante |
| RF013 | O sistema deve gerar um código único para cada produto registrado. | Essencial |
| RF014 | O sistema deve listar produtos separados por categoria. | Importante |
| RF015 | O sistema deve permitir que o gerente cadastre novos funcionários. | Essencial |
| RF016 | O cadastro deve conter Nome, CPF, RG, Endereço, CEP e Data de Nascimento. | Importante |
| RF017 | O sistema deve disponibilizar um tutorial em vídeo. | Desejável |
| RF018 | O sistema deve gerar relatórios mensais de gastos. | Importante |
| RF019 | O relatório deve incluir todas as vendas realizadas no mês. | Importante |
| RF020 | O relatório deve comparar os gastos com os meses anteriores. | Desejável |
| RF021 | O sistema deve gerar um código de segurança para cada novo funcionário. | Essencial |

                 2.1.2 **Requisitos Não Funcionais** 

| ID | Descrição  | Categoria | Prioridade |
| :---- | :---- | :---- | :---- |
| RNF001 |  O sistema deve permitir apenas um cadastro de 1 produto por vez em cada máquina. | Desempenho | Importante |
| RNF002 | O sistema deve exibir a mensagem “operação inválida” quando houver tentativa de cadastrar mais de um produto por vez. | Usabilidade | Importante |
| RNF003 | A notificação de validade deve ser exibida com 30 dias de antecedência. | Confiabilidade | Essencial |
| RNF004 | O relatório de vendas, estoque e gastos deve ser gerado conforme configuração do usuário, podendo ser diário, semanal ou mensal.  | Usabilidade | Importante |
| RNF005 | Os relatórios devem conter o nome do produto, entrada, saída e estoque atual e a quantidade vendida. | Usabilidade  | Importante |
| RNF006 | As notificações devem ser enviadas por e-mail e podem também aparecer como alerta no sistema. | Confiabilidade | Importante |
| RNF007 | O envio de e-mails deve ocorrer apenas no horário de trabalho dos funcionários. | Confiabilidade | Desejável |
| RNF008 |  O alerta de falta de produtos deve garantir que o usuário seja informado antes de repassar dados ao cliente. | Confiabilidade | Essencial |
| RNF009 | A notificação de falta de produto deve ser enviada para o e-mail do usuário, podendo também ser exibida como alerta no sistema. | Usabilidade  | Importante |
| RNF010 | O relatório de gastos deve ser exibido de forma detalhada, com informações claras e organizadas em tabelas e gráficos, e deve poder ser exportado em PDF ou .docx. | Usabilidade | Essencial |
| RNF011 | Não pode haver mais de um produto com o mesmo código. | Confiabilidade | Essencial |
| RNF012 | A lista de produtos por categoria deve ser exibida de forma clara e organizada, permitindo filtros e ordenação. | Usabilidade | Importante |
| RNF013 | Apenas usuários com perfil de “Gerente” podem cadastrar funcionários. | Segurança | Essencial |
| RNF014 | O tutorial deve ter no máximo 15 minutos de duração. | Usabilidade | Desejável |
| RNF015 | O relatório mensal de gastos deve ser apresentado em formato gráfico e/ou tabular. | Usabilidade | Importante |
| RNF016 | O código de segurança deve ser armazenado de forma segura e intransferível. | Segurança | Essencial |
| RNF017 | O sistema deve atualizar automaticamente o código de cada funcionário a cada 6 meses, com notificação enviada ao gerente responsável. | Segurança | Importante |

                 2.1.3 **Regras de Negócio** 

| Identificador | Descrição  | Escopo | Prioridade |
| ----- | :---- | :---- | :---- |
| RN001 | Não é permitido cadastrar o mesmo produto mais de uma vez; novos lotes apenas atualizam a quantidade. | Geral | Importante |
| RN002 | Produtos devem ser retirados das prateleiras uma semana antes do vencimento. | Geral | Essencial |
| RN003 | Produtos retirados podem ser colocados em promoção. | Geral | Desejável |
| RN004 | O cliente pode devolver o produto em até 7 dias, sem necessidade de justificativa. | Geral | Essencial |
| RN005 | Produtos em pouca quantidade devem gerar solicitação automática de reposição. | Geral | Essencial |
| RN006 | A margem mínima deve ser 15% sobre o valor de compra. | Geral | Importante |
| RN007 | A margem máxima não pode ultrapassar 100% do valor de compra. | Geral | Importante |
| RN008 | Cada categoria deve conter apenas produtos correspondentes (ex.: sabonete líquido não pode aparecer na categoria de sabão em pó). | Geral | Importante |
| RN009 | O funcionário deve ter no mínimo 18 anos para ser registrado. | Geral | Essencial |
| RN010 | O controle de gastos deve sempre ser comparado com o mês anterior. | Geral | Importante |
| RN011 | O código de segurança deve ser desativado quando o funcionário for desligado da empresa.  | Geral | Essencial |

 2.2 **Escopo Futuro**

      2.2.1 **Requisitos Funcionais** 

* **RF022**: O sistema deve disponibilizar acesso multiplataforma, podendo ser utilizado em versão web, desktop ou aplicativo mobile (Android/iOS).  
* **RF023**: O sistema deve permitir integração com sistemas de vendas  
* **RF026**: O sistema deve oferecer um sistema de busca avançada de produtos.


           2.2.2 **Requisitos Não Funcionais**

* **RNF018**: O sistema deve ser responsivo e acessível em diferentes dispositivos.  
* **RNF019**: O sistema deve garantir tempo de resposta inferior a 2 segundos para consultas de estoque.  
* **RNF020**: O sistema deve oferecer backup automático em nuvem.

          


     2.2.3 **Regras de Negócio** 

* **RN012:** Apenas usuários com permissão especial poderão excluir registros de produtos.  
* **RN013**: Produtos importados devem ter registro separado de nacionalizados.

     3\. **Diagramas UML**

         3.1 **Casos de Uso**

 **Caso de uso 1** 

         3.2 **Classes**

\<Diagrama de Classes\>

**Caso de uso 2** 

 3.2 **Classes**

3.3 **Diagrama de Classes**

