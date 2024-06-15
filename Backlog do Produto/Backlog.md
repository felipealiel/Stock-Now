# Relatório Personas e user story

Discentes Luanna, Felipe Aliel, Marcos Gabriel, Jander, Michel e Tiago.
# Personas 

## Persona 1
|Nome: Pablo |
|------------|
|Idade: 40   |

|Quem?                                                                                  |
|---------------------------------------------------------------------------------------|
|Q1: Especialista em Inventário.                                                        |
|Q2: Ensino superior completo.                                                          |
|Q3: Uma pessoa muito organizada, comunicativa e pró-ativa.                             |
|Q4: Medo de quando algo sai fora do controle, gosto de coisas com bastante organização.|

|Contexto                                                                                                                                                  |
|----------------------------------------------------------------------------------------------------------------------------------------------------------|
|C1: monitoramento e gerência de estoque, comunicação com outros setores, compartilhamento de arquivos, relatórios e comunicação com amigos e familiares.  |


|Problemas                                                                 |
|--------------------------------------------------------------------------|
|P1: A falta de atualização do sistema, a interface não é muito intuitiva. |
|P2: Diminuir o tempo de atualização e deixar a interface mais intuitiva.  |

|Experiência com tecnologia                                                                                                            |
|--------------------------------------------------------------------------------------------------------------------------------------|
|E1: As conversas, sistema de notificações e organização                                                                               |
|E2: Atualização lenta, não está notificando, falta atualização, depois de um tempo com o armazenamento cheio, o app não notifica mais.|
|E3: Computador, celular, tablet.                                                                                                      |
|E4: Perguntas e pesquisas.                                                                                                            |
|E5: Passo a passo.                                                                                                                    |
|E6: Aprendo melhor observando imagens.                                                                                                |
|E7: Compartilhar acontecimentos.                                                                                                      |

|Soluções       |
|---------------|
|S1: Não.       |
|S2: Não existe.|
|S3: Não existe.|

## Persona 2

|Nome: Carlos |
|-------------|
|Idade: 35    |

|Quem?                                                                                                         |
|--------------------------------------------------------------------------------------------------------------|
|Q1: Analista de estoque.                                                                                      |
|Q2: Ensino superior completo.                                                                                 |
|Q3: Atento, organizado e comunicativo.                                                                        |
|Q4: Medo de não acompanhar bem os desenvolvimentos das coisas, e de coisas que não transmitem segurança.      |

|Contexto                                                                                                                                              |
|------------------------------------------------------------------------------------------------------------------------------------------------------|
|C1: para fazer análise de estoque, comunicação com outros setores, compartilhamento de arquivos, relatórios e comunicação com amigos e familiares.    |

|Problemas                                                                       |
|--------------------------------------------------------------------------------|
|P1: A falta de atualização do sistema, falta de armazenamento e a organização.  |
|P2: ajudar a resolver meus problemas de uma forma mais rápida e eficiente.      |

|Experiência com tecnologia                                                                | 
|------------------------------------------------------------------------------------------|
|E1: A interação e facilidade de comunicação.                                              |
|E2: Atualização lenta, falta atualização, falta de mais armazenamento e facilidade de uso.|
|E3: Computador, celular, tablet.                                                          |
|E4: Perguntando e pesquisando.                                                            |
|E5: Passo a passo.                                                                        |
|E6: Aprendo melhor observando imagens e apresentações gráficas.                           |
|E7: Compartilhar acontecimentos.                                                          |

|Soluções                                           |
|---------------------------------------------------|
|S1: No momento não conheço.                        |
|S2: Talvez possam ajudar na facilidade de uso.     |
|S3: Não conheço.                                   |

## Persona 3

|Nome: José |
|-----------|
|Idade: 38  |

|Quem?                                                                                                                                                               |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Q1: Estoquista.                                                                                                                                                     |
|Q2: Ensino superior incompleto.                                                                                                                                     |
|Q3: Uma pessoa muito detalhista, organizada e pró-ativa.                                                                                                            |
|Q4: Desorganização, perda de tempo pois a preocupação em desperdiçar tempo em tarefas desnecessárias ou ineficientes devido à falta de organização ou planejamento. |

|Contexto                                                                                                                                                            |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|C1:organizar estoque, comunicação com seus superiores e outros setores, compartilhamento de arquivos, relatórios e comunicação com amigos e familiares.             |

|Problemas                                                                                                      |
|---------------------------------------------------------------------------------------------------------------|
|P1: A falta de atualização do sistema, a interface não é muito intuitiva e dificulta a utilização do sistema.  |
|P2: Diminuir o tempo de atualização e deixar a interface mais intuitiva.

|Experiência com tecnologia 
|-------------------------------------------------------------------------------|
|E1: Chat de conversa, pois pode se comunicar com outras pessoas                |
|E2: a falta de organização das interfaces, pois elas não são muito intuitivas. |
|E3: Computador, celular, tablet.                                               |
|E4: Perguntas e pesquisas.                                                     |
|E5: Passo a passo.                                                             |
|E6: Aprendo melhor observando imagens.                                         |
|E7: Compartilhar acontecimentos.                                               |

|Soluções             |
|---------------------|
|S1: Não.             |
|S2: Não existe.      |
|S3: Não existe.      |


# User story
**Funcionalidade 1: Registrar novos produtos**
Como analista de estoque, eu quero cadastrar novos produtos, para complementar meu estoque.
**Critérios de aceitação :** Os usuários podem cadastrar apenas 1 produto por vez.
Os usuários não deverão cadastrar o mesmo produto mais de 1 vez, mesmo que mude as datas de entrada.

**Funcionalidade 2: Registrar a data de validade dos produtos**
Como estoquista, eu quero poder registrar a data de validade dos produtos, para retirar os produtos que já estão próximos da validade.
**Critérios de aceitação:** O sistema irá notificar quando alguns produtos  estiverem com a validade próxima.
**Regras de negócio:** Os produtos devem ser retirados das prateleiras 1 semana antes de vencerem.

**Funcionalidade 3: Emissão de relatórios**
Como especialista em inventário, eu quero receber relatórios diários sobre todas  as vendas do dia, para manter um controle de estoque.
**Critérios de aceitação:** O sistema deve notificar quando algum produto foi devolvido ou a venda cancelada.
**Regras de negócio:** O cliente pode devolver o produto para o estoque em até uma semana.

**Funcionalidade 4: Contagem de produtos**
Como especialista em inventário, eu quero receber um relatório relatando a quantidade total de produtos que entraram, saíram ou que ainda estão disponíveis durante a semana, para ter um controle das vendas da semana.
**Critérios de aceitação:** Se um produto estiver em pouca quantidade o sistema deverá notificar.

**Funcionalidade 5: Alerta para falta de produtos**
Como especialista em inventário, eu quero receber um alerta sempre que um produto estiver em falta, para que seja solicitada a reposição.
**Critérios de aceitação:** O sistema deverá garantir que os usuários saibam que o produto está com uma quantidade mínima, antes que ele acabe.

**Funcionalidade 6: Totalizar gastos**
Como analista de estoque, eu quero ser informado sobre a quantidade total de gastos de cada produto dentro do estoque, para obter a margem de lucro.
**Critérios de aceitação:** O sistema deve garantir que o produto seja no mínimo 15% a mais que o valor inicial.
Regras de negócio: A margem de lucro sobre cada produto, não deverá ultrapassar 100%.

**Funcionalidade 7: Codificação** 
Como estoquista, eu quero que um código de identificação seja gerado para cada novo produto registrado, para facilitar a leitura de código  no caixa .
**Critérios de aceitação:** Não pode haver 2 produtos com o mesmo código. 

**Funcionalidade 8: Listagem por categoria**
Como estoquista, eu quero receber  listas dos produtos divididos por categorias nas quais foram registrados, para diferenciar melhor os produtos.
**Critérios de aceitação:** Cada categoria só deve ter produtos que possuem semelhanças.

**Funcionalidade 9: Cadastro**
Como analista de estoque , eu quero poder realizar o cadastro de novos estoquistas, para aumentar a rapidez e o desenvolvimento do controle de estoque.
**Critérios de aceitação:** Somente o analista de estoque pode cadastrar um novo funcionário.
**Regras de negócio:** O funcionário deve ter no mínimo 18 anos, para começar a trabalhar.

**Funcionalidade 10: Tutorial**
Como funcionário, eu quero ter acesso a um tutorial para usar o app, para que possa utilizá-lo da forma correta.
**Critérios de aceitação:** O tutorial não deverá conter nenhum dado empresarial do sistema, apenas as suas funcionalidades.


**Funcionalidade 11: Controle de gastos**
Como analista de estoque, eu quero ter uma comparação de gastos mensais, para saber se houve aumento ou diminuição da taxa de gastos.
**Critérios de aceitação:** O controle de gastos deve ser gerado em forma de relatório, relatando junto com tudo que foi vendido durante o mês. 

**Funcionalidade 12:** Controle de segurança 
Como gerente, eu quero que seja gerado um código de segurança para cada novo funcionário registrado, para controlar os acessos.
**Critérios de aceitação:** A cada 6 meses, cada funcionário terá um código novo.
**Regras de negócio:** Ao ser desligado da empresa, o código será desativado. 



