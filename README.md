
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

**O que as pessoas fazem?**
Produção e vendas de esfihas em pequena/média escala na cidade de Cornélio Procópio.  

**Quais os artefatos envolvidos?**
Um meio de comunicação entre cliente e fornecedor, um tipo de banco de dados para o registro de informações como as vendas diárias, gastos, quantidade de esfirras, etc. 
um meio de comunicação entre o fornecedor e um meio de entregas, um meio de comunicação entre o cliente e o meio de entregas.  

**O que eles precisam saber?**  
Saber se comunicar com os clientes, saber calcular o custo e o preço do produto a ser vendido, saber achar a localização para entregas, saber anotar as informações de vendas diárias.  

***Cenários:***

**Cenário Antes:**
Marcia faz esfirras, ela oferece e vende seus produtos através do WhatsApp. Ela recebe os pedidos dos clientes por mensagem e anota todas as informações necessárias em um caderno, como o sabor das esfirras, a quantidade desejada, o nome e endereço do cliente, além do horário de entrega solicitado. Após anotar os pedidos, ela prepara as esfirras conforme solicitado e faz as entregas pessoalmente ou por meio de um serviço de entrega.


**Cenário Depois:**
Marcia criou um sistema online para oferecer esfirras e receber os pedidos dos clientes. Agora, os clientes acessam um link específico para fazer seus pedidos, escolhendo os sabores e a quantidade desejada de esfirras. Além disso, o sistema permite que os clientes façam o pagamento online, utilizando métodos como cartão de crédito, débito ou transferência bancária. Assim que o pedido é realizado e o pagamento confirmado, Marcia recebe automaticamente todas as informações do pedido em seu sistema, incluindo o endereço do cliente e o horário de entrega desejado. Com essas informações, ela prepara as esfirras e faz as entregas, mantendo um registro completo de todos os pedidos e pagamentos.



## 2. Documentos gerais no repositório

|Requisitos Funcionais|Descrição|Prioridade|
|---------------------|--------------|------------|
|RF01 | O sistema deve apresentar o subtotal ao usuário antes de finalizar a compra| Alta
|RF02 | O sistema deve apresentar o sabor das esfirras ao usuário quando solicitado| Media
|RF03 | O sistema deve ser capaz de calcular o custo de produção| Baixa
|RF04 | O sistema deve registrar a entrada e saída de caixa| Alta
|RF05 | O sistema deve ser capaz de calcular e mostrar o lucro diario| Media
|RF06 | O sistema deve permitir que o cliente possa selecionar os sabores das esfirras| Media
|RF07 | O sistema deve ser capaz de deixar que o administrador consulte e finalize os pedidos feitos pelos clientes| Alta
|RF08 | O sistema deve permitir que o administrador possa inserir os tipos de sabores no sistema| Alta
|RF09 | O sistema deve permitir que o administrador possa consultar os endereços dos usuários na hora da entrega| Alta
|RF10 | O sistema deve garantir que o administrador seja capaz de visualizar o gasto para a produção| Baixa
|RF11 | O sistema deve permitir que o cliente consiga adicionar itens ao carrinho| Media
|RF12 | O sistema deve permitir que o usuário faça seu cadastro usando seus dados pessoais| Alta
|RF13 | O sistema deve permitir que o usuário escolha qual tipo de login irá fazer, sendo Administrador ou Cliente| Alta
|RF14 | O sistema deve permitir que o usuário acesse uma interface de histórico das entradas, saídas e registros de caixa realizados pelo sistema|Alta
|RF15 | O sistema deve permitir que os usuários acessem o botão de suporte/contato online em qualquer pagina do sistema|Media
|RF16 | O sistema deve permitir que os usuários vejam o tempo médio de entrega do produto|Media

|Requisitos Não Funcionais|Descrição|Prioridade|
|-|-|-|
|RN01| O sistema deve poder ser acessado em qualquer dispositivos mobile (Android e Ios)|Alta
|RN02| O sistema deve suportar até o android 5| Media
|RN03| O sistema deve suportar português, inglês e espanhol para maximizar a abrangência de público|Baixa
|RN40| O administrador deve ser o único com acesso aos dados dos clientes| Alta
|RN05| O sistema deve estar de acordo com a LGPD| Alta
|RN06| O sistema deve suportar 100 usuários concorrentemente|Alta
|RN07| As notificações de push deverão ser enviadas por meio da Firebase|Baixa
|RN08| Todos os processos menores deverão usar meória cache para maior otimização|Media
|RN09| O sistema deve ser implementado em Kotlin para android e Swift para IOS|Alta
|RN10| O sistema deve fazer com que a compra do usuário seja realizada com menos de 4 cliques no app|Baixa
|RN11| O sistema deve ter seu banco de dados implementado em MySQL|Baixa



|Requisitos trocados|Descrição|Prioridade|
|-|-|-|
|RN02| O sistema deve suportar diferentes tipos de moedas|Baixa
|RN04| O sistema deve armazenar os pedidos dos clientes em um banco de dados|Alta
|RN05| O sistema deve armazenar as contas dos usuários com cpf, nome e telefone no banco de dados|Alta
|RN07| O sistema deve oferecer opções de pagamento em dinheiro, cartão ou pix|Alta
|RN08| O sistema deve salvar os dados de pedidos que não foram finalizados pelos clientes|Alta
|RN10| O sistema deve retringir o acesso aos dados pessoais dos usuários apenas aos administradores|Alta
|RN11| O sistema deve garantir que o cadastro seja realizado com os dados do CPF, Nome e Telefone do usuário para todo usuário| Alta
|RN12| O sistema deve garantir que o cadastro do Administrador contenha um conjunto adicional de informações, incluindo o cargo e a data de admissão do administrador| Alta
|RN15| O sistema deve calcular tempo medio da entrega do produto por cliente utilizando a API do google maps|Media

### **Roteiro Entrevista**

1. Quais foram os maiores desafios que enfrentou ao empreender nesse ramo?
2. Quais problemas você acredita que o aplicativo poderia resolver?
3. O que a motivou a iniciar seu negócio de esfirras?
4. Quais são os sabores mais populares entre seus clientes?
5. Como você interage com seus clientes?
6. Como você promove atualmente suas esfirras?
7. Como você lidaria com um crescimento inexperado do seu negócio? Franquias, Terceirizar alguma tarefa?
8. Que funcionalidades você acha essenciais para ajudar nas vendas?
9. Você acha que seus clientes se adaptariam ao aplicativo?
10. E você se adaptaria ao aplicativo?
11. Qual o seu processo de venda atualmente?

### **Histórias de Usuário**

|Número|Historias de Usuário|Tipo|
|-|-|-|
|1| Como cliente, quero verificar o tempo estimado para a chegada do produto, para poder me organizar para recebê-lo||
|2| Como cliente, quero ver o valor da compra antes de finalizá-la, para saber quanto devo pagar||
|3| Como funcionário, quero poder consultar e finalizar os pedidos feitos pelos clientes, para que os pedidos não fiquem em demanda||
|4| Como cliente, quero ver os sabores do produto, para escolher os de minha preferência||
|5| Como funcionário, quero poder adicionar sabores ao aplicativo, para poder aumentar meu catálogo||
|6| Como funcionário, quero ter acesso aos endereços dos pedidos, para poder realizar as entregas corretamente||
|7| Como funcionário, quero ver o gastos que terei com a produção, para poder reajustar os preços das esfirras||
|8| Como cliente, quero adicionar diferentes produtos a um carrinho virtual, para poder comprar mais de um produto||
|9| Como cliente, quero poder me cadastrar no aplicativo, para ter minhas informações salvas||
|10| Como usuário, quero escolher qual tipo de login realizar, para acessar minha conta||
|11| Como funcionário, quero poder acessar meu fluxo de caixa, para ter mais agilidade e organização no meu negócio||
|12| Como cliente, quero poder acessar um suporte online, para poder sanar quaisquer dúvidas ou problemas que possam ocorrer||


### Entrevista

https://drive.google.com/file/d/1h1JIyD0GbjGOFi9dKXTOqYi0zFZBnbku/view?usp=sharing

***2.3. Protótipos***

[https://injamock.com/Designer/Workplace/195324393](https://ninjamock.com/s/DG43JLx)

***2.4 Documentação dos Diagramas de Caso de Uso***

| |FINANCEIRO| |
|-|-|-|
|ID|Nome|Ator|
|UC01|Consultar Endereço|Funcionário e Administrador|
|UC02|Verificar Distância/Tempo|Funcionário Administrador|
|UC03|Inserir Gastos|Administrador|
|UC04|Calcular Custo|Administrador e Sistema|
|UC05|Verificar Lucro|Administrador|
|UC06|Inserir Ganhos|Administrador|
|UC07|Calcular Receita|Administrador|

| |Estoque| |
|-|-|-|
|ID|Nome|Ator|
|UC01|Consultar estoque|Funcionário|
|UC02|Consultar processo de produção|Funcionário e Administrador|
|UC03|Ver quantidade para a produção|Funcionário e Administrador|
|UC04|Ver quantidade de ingredientes|Funcionario e Administrador|
|UC05|Ver quantidade de produtos|Funcionario e Administrador|
|UC06|Registrar produtos|Administrador|
|UC07|Registrar saída de produtos|Administrador|
|UC08|Registrar entrada de produtos|Administrador|
|UC09|Atualizar informações|Administrador|
|UC10|Remover produtos|Administrador|
|UC11|Ver gasto para produção|Administrador|
|UC12|Gerar relatórios de estoque|Sistema|

| |Compra| |
|-|-|-|
|ID|Nome|Ator|
|UC01|Navegar pelo catalogo|Cliente|
|UC02|Adicionar item ao carrinho|Cliente|
|UC03|Finalizar compra|Cliente|
|UC04|Informar endereço|Cliente|
|UC05|Selecionar forma de pagamento|Cliente|
|UC06|Preencher dados do cartão|Cliente|
|UC07|Validar cartão|Cliente e Sistema|
|UC08|Rastrear pedido|Cliente e Sistema|
|UC09|Confirmar pedido|Sistema|

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
