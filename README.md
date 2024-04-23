
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Apresentação do pitch: https://www.canva.com/design/DAGB4CU5PtU/vX7Toe6p2_bopGCY0FV7eA/edit?utm_content=DAGB4CU5PtU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

## 1. Introdução

***1.1.  Nome do Grupo***

**Grupo 7 - Esfirras da Márcia**

*@JocimarBj* - link: https://github.com/JocimarBJ  
*@Andromeda-Queen* - link: https://github.com/Andromeda-Queen  
*@BrinoMD* - link: https://github.com/BrinoMD  
*@Caduber* - link: https://github.com/Caduber  
*@GabrielB2101* - link: https://github.com/GabrielB2101  
*@lucasouza20* - link: https://github.com/lucasouza20  

**Link padlet = [https://padlet.com/carlosemdl/requisitos-de-software-4iyf40lcl07kw08d]**

***1.2.  Nome do Sistema***

**Esfirras da Márcia**

***1.3.  Propósito do Sistema***

Oferecer um cardápio online em que os clientes consigam encomendar esfirras, além de gerar benefícios para quem compra fielmente. Para os donos da loja, também há opções de controle de recursos e gastos.

O objetivo da **Esfirras da Márcia** é facilitar a encomenda de esfirras para o usuário e o gerenciamento de recursos e entregas para o comerciante. 

***1.4.  Público Alvo***

O público alvo é tanto a loja *(de esfirras)* quanto para os clientes da loja.

***1.5. Descrição dos usuários***

Planilha:
https://docs.google.com/document/d/11KBDEbPJdz3StuBsYBrMCwRkD2JUd2fKU2W7mhlEpco/edit

Personas:

![3](https://github.com/JocimarBJ/esfirras-da-marcia/assets/75817277/3ef256a1-7168-4bf3-9604-a4cfd2879a69)
![2](https://github.com/JocimarBJ/esfirras-da-marcia/assets/75817277/654c9948-d3ef-464d-b630-b8cb7d985b93)
![1](https://github.com/JocimarBJ/esfirras-da-marcia/assets/75817277/991ca6db-4d1a-4fa4-9b93-5dd4b52b2ad8)

  
Análise de tarefas:  

O que as pessoas fazem?  
Produção e vendas de esfihas em pequena/média escala na cidade de Cornélio Procópio.  

Quais os artefatos envolvidos?  
Um meio de comunicação entre cliente e fornecedor, um tipo de banco de dados para o registro de informações como as vendas diárias, gastos, quantidade de esfirras, etc. 
um meio de comunicação entre o fornecedor e um meio de entregas, um meio de comunicação entre o cliente e o meio de entregas.  

O que eles precisam saber?  
Saber se comunicar com os clientes, saber calcular o custo e o preço do produto a ser vendido, saber achar a localização para entregas, saber anotar as informações de vendas diárias.  

Cenários:

Cenário Antes:
Marcia faz esfirras, ela oferece e vende seus produtos através do WhatsApp. Ela recebe os pedidos dos clientes por mensagem e anota todas as informações necessárias em um caderno, como o sabor das esfirras, a quantidade desejada, o nome e endereço do cliente, além do horário de entrega solicitado. Após anotar os pedidos, ela prepara as esfirras conforme solicitado e faz as entregas pessoalmente ou por meio de um serviço de entrega.


Cenário Depois:
Marcia criou um sistema online para oferecer esfirras e receber os pedidos dos clientes. Agora, os clientes acessam um link específico para fazer seus pedidos, escolhendo os sabores e a quantidade desejada de esfirras. Além disso, o sistema permite que os clientes façam o pagamento online, utilizando métodos como cartão de crédito, débito ou transferência bancária. Assim que o pedido é realizado e o pagamento confirmado, Marcia recebe automaticamente todas as informações do pedido em seu sistema, incluindo o endereço do cliente e o horário de entrega desejado. Com essas informações, ela prepara as esfirras e faz as entregas, mantendo um registro completo de todos os pedidos e pagamentos.



## 2. Documentos gerais no repositório

|Identificador|Descricao|Prioridade|
|---------------------|--------------|
|RF01 | O sistema sistema deve apresentar o subtotal ao usuário antes de finalizar a compra|
|RF02 | O sistema deve apresentar o sabor das esfirras ao usuário quando solicitado|
|RF03 | O sistema deve ser capaz de calcular o custo de produção| **
|RF04 | O sistema deve registrar a entrada e saída de caixa| **
|RF05 | O sistema deve ser capaz de calcular o lucro diario| **
|RF06 | O software no perfil de usuário deve poder selecionar os sabores e adicionar ao carrinho| **
|RF07 | O software no perfil de administrador deve ser capaz de consultar os pedidos dos usuários|
|RF08 | O software no perfil de administrador pode inserir os tipos de sabores no sistema|
|RF09 | O software no perfil de administrador pode consultar os endereços dos usuários|
|RF10 | O software no perfil de administrador deve ser capaz de visualizar o gasto para a produção|


|Identificador|Requisitos Não Funcionais|
|--|--|
|RNF01 | O sistema deve armazenar os pedidos em um banco de dados|
|RNF02 | O sistema deve gerenciar os pontos fidelidade de cada usuário| **
|RNF03 | O sistema deve apresentar uma interface diferente para os administradores| **
|RNF04 | O sistema deve mostrar os insumos restantes das esfirras|
|RNF05 | O sistema deve permitir a alteração dos preços das esfirras|
|RNF06 | O sistema deve gerar um relatório diário com base no lucro|
|RNF07 | O sistema deve separar os pedidos em "realizando" e "concluído"|
|RNF08 | O sistema deverá oferecer opções de pagamento em dinheiro ou cartão|
|RNF09 | O sistema deve manter um histórico de compras dos clientes| **
|RNF10 | O sistema deverá salvar os dados de pedidos que não foram finalizados pelos clientes|**


***2.3. Protótipos***

*<Link para a pasta com os protótipos.>*

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
