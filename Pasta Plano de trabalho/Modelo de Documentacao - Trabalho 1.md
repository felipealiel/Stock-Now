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

    - RF001: O sistema deve permitir o cadastro de novos produtos.
    - RF002: O sistema deve atualizar a quantidade e lote quando um produto já estiver cadastrado.
    - RF003: O sistema deve permitir registrar a data de validade dos produtos.
    - RF004: O sistema deve notificar quando algum produto estiver próximo da data de validade
    - RF005: O sistema deve gerar relatórios.
    - RF006: Os relatórios devem conter o nome do produto e a quantidade vendida.
    - RF007: O sistema deve notificar quando houver devolução ou cancelamento de venda.
    - RF008: O sistema deve enviar relatórios semanais por e-mail.
    - RF010: O relatório deve conter data de início e fim da semana, quantidade de produtos vendidos e total arrecadado.
    - RF011: O sistema deve enviar solicitação de reposição quando um produto estiver em pouca quantidade.
    - RF012: O sistema deve gerar uma notificação quando um produto estiver em falta.
    - RF013: O sistema deve calcular a margem de lucro sobre cada produto.
    - RF014: O sistema deve gerar um código único para cada produto registrado.
    - RF015: O sistema deve listar produtos separados por categoria.
    - RF016: O sistema deve permitir que o gerente cadastre novos funcionários.
    - RF017: O cadastro deve conter Nome, CPF, RG, Endereço, CEP.
    - RF018: O sistema deve disponibilizar um tutorial em vídeo.
    - RF019: O sistema deve gerar relatórios mensais de gastos.
    - RF020: O relatório deve incluir todas as vendas realizadas no mês.
    - RF021: O relatório deve comparar os gastos com os meses anteriores.
    - RF022: O sistema deve gerar um código de segurança para cada novo funcionário.




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

