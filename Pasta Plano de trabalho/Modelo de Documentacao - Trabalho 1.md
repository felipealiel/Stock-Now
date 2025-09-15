1. **Descrição Geral do Projeto**  
   1.1 **Nome do Projeto**  
   Stock Now 
     
   1.2 **Descrição do Produto**  
   O Stock Now é um aplicativo de gerenciamento de estoque tanto de empresas quanto de empreendedores ou negócios em geral, de forma que o mesmo torne-se mais eficaz e diminua a margem de erro humano.
   
   1.3 **Objetivo**  
   Desenvolvimento de um aplicativo para  controle de estoque que ajude empresas e empreendedores a gerenciar de forma eficiente seus inventários.
   
   1.4 **Motivação**  
   Com o ritmo acelerado da sociedade moderna as empresas buscam otimizar a forma com que utilizam seus recursos através de um gerenciamento preciso e confiável. E o Stock Now foi desenvolvido para atender essa demanda.
     
   1.5 **Equipe de Desenvolvimento**  
   - Marcos Gabriel Peixoto Almeida
   - Felipe Aliel Ramos da Silva
   - Tiago dos Santos
   - Laiz Samile
   - Clarise

   

	1.6 **Descrição dos Usuários Finais**  
Exemplo:

Os usuários finais do aplicativo são:

* Clientes Pessoas Físicas que utilizam o app para abrir contas digitais, controlar gastos, realizar transferências, pagamentos e gerenciar investimentos.

* Clientes Pessoas Jurídicas (empresas) que utilizam funcionalidades específicas como contas PJ, emissão de boletos e gestão financeira simplificada.


2. **Escopo**  
   2.1 **Escopo Específico**

    - 2.1.1 **Requisitos Funcionais**

      - RF01: O sistema deve permitir o cadastro de novos produtos.
      - RF02: O sistema deve permitir apenas um cadastro de produto por vez em cada máquina.
      - RF03: O sistema deve atualizar a quantidade e lote quando um produto já existir.
      - RF04: O sistema deve permitir registrar a data de validade dos produtos.
      - RF05: O sistema deve notificar quando algum produto estiver a 7 dias da validade.
      - RF06: O sistema deve gerar relatórios diários em formato Excel.
      - RF07: O relatório deve conter o nome do produto e a quantidade vendida.
      - RF08: O sistema deve notificar quando houver devolução ou cancelamento de venda.
   	  - RF09: O sistema deve enviar relatórios semanais por e-mail com entrada, saída e estoque atual.
	  - RF10: O relatório deve conter data de início e fim da semana, quantidade de produtos vendidos e total arrecadado.
	  - RF11: O sistema deve enviar solicitação de reposição por e-mail quando um produto estiver em pouca quantidade.
	  - RF12: O sistema deve gerar uma notificação quando um produto estiver em falta.
	  - RF13: O sistema deve calcular os gastos com luz e armazenamento dos produtos.
	  - RF14: O sistema deve calcular a margem de lucro sobre cada produto.
	  - RF15: O sistema deve gerar um código único para cada produto registrado.
	  - RF16: O sistema deve listar produtos separados por categoria.
	  - RF17: O sistema deve permitir ao analista de estoque cadastrar novos funcionários.
	  - RF18: O cadastro deve conter Nome, CPF e RG.
	  - RF19: O sistema deve disponibilizar um tutorial em vídeo.
	  - RF20: O tutorial deve ter no máximo 15 minutos de duração.
	  - RF21: O sistema deve gerar relatórios mensais de gastos.
	  - RF22: O relatório deve incluir todas as vendas realizadas no mês.
	  - RF23: O relatório deve comparar os gastos com os meses anteriores.
	  - RF24: O sistema deve gerar um código de segurança para cada novo funcionário.
	  - RF25: O sistema deve atualizar o código de cada funcionário a cada 6 meses.



    - 2.1.2 **Requisitos Não Funcionais**
      
      - RNF01: O sistema deve exibir a mensagem “operação inválida” quando houver tentativa de cadastrar mais de um produto por vez.
      - RNF02: A notificação de validade deve ser exibida de forma clara e destacada.
	  - RNF03: O relatório diário deve estar disponível até o fim do expediente.
      - RNF04: O envio de e-mail deve ocorrer apenas no horário de trabalho dos funcionários.
      - RNF05: O alerta de falta de produtos deve garantir que o usuário seja informado antes de repassar dados ao cliente.
      - RNF06: O cálculo de gastos deve ser exibido em relatório detalhado.
      - RNF07: Não pode haver mais de um produto com o mesmo código.
      - RNF08: A lista por categoria deve ser exibida em formato claro e organizado.
      - RNF09: Apenas usuários com perfil de “analista de estoque” podem cadastrar funcionários.
      - RNF10: O tutorial não deve conter dados empresariais, apenas funcionalidades.
      - RNF11: O relatório mensal de gastos deve ser apresentado em formato gráfico e/ou tabular.
      - RNF12: O código de segurança deve ser armazenado de forma segura e intransferível.



    - 2.1.3 **Regras de Negócio**

      - RN01: Não é permitido cadastrar o mesmo produto mais de uma vez; novos lotes apenas atualizam a quantidade.
      - RN02: Produtos devem ser retirados das prateleiras uma semana antes do vencimento.
      - RN03: Produtos retirados podem ser colocados em promoção.
      - RN04: O cliente pode devolver o produto em até 7 dias, sem necessidade de justificativa.
      - RN05: Produtos em pouca quantidade devem gerar solicitação automática de reposição.
      - RN06: A margem mínima deve ser 15% sobre o valor de compra.
      - RN07: A margem máxima não pode ultrapassar 100% do valor de compra.
      - RN08: Cada categoria deve conter apenas produtos correspondentes (ex.: sabonete líquido não pode aparecer na categoria de sabão em pó).
      - RN09: O funcionário deve ter no mínimo 18 anos para ser registrado.
      - RN10: O controle de gastos deve sempre ser comparado com o mês anterior.
      - RN11: O código de segurança deve ser desativado quando o funcionário for desligado da empresa.


\<Lista de Regras de Negócio que serão entregues nesta versão\>

           2.2 **Escopo Futuro**

      2.2.1 **Requisitos Funcionais** 

\<Lista de Requisitos Funcionais planejados para próximas versões\>

                 2.2.2 **Requisitos Não Funcionais**

\<Lista de Requisitos Não Funcionais planejados para próximas versões\>

                 2.2.3 **Regras de Negócio** 

	   	\<Lista de Regras de Negócio planejados para próximas versões\>

       

     3\. **Diagramas UML**

         3.1 **Casos de Uso**

\<Diagrama de Caso de Uso\>

         3.2 **Classes**

\<Diagrama de Classes\>

