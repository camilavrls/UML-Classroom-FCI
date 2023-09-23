<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
Pizza-Expres
</center></font>

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do projeto](#introdução-do-projeto)
- [Análise de requisitos funcionais e não-fucionais](#descrição-dos-requisitos)
- [Diagrama de casos de uso](#diagrama-de-comportamento-atores)
- [Descrição dos casos de uso](#descrição-das-funcões)
- [Diagrama de senquencia](#diagrama-de-ordem-interações)
- [Diagrama de classes](#diagrama-orientado-objetos)
- [Diagrama de componentes](#diagrama-estrutura-componente)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Alex Albert - 31895972
* Antonio Cesar - 32348800
* Camila Vitória - 32094094
* Guilherme Almeida - 32327765


# Descrição do projeto

A Pizza-Express é uma cadeia de 40 lojas de fast-food e entrega em casa. <br>
Pizza-Express tem perdido recentemente 30% do rendimento de vendas devido a um problema em seu negócio da entrega. Atribuem este problema a seu concorrente principal que promoveu um programa que garante o serviço de entrega em 30 minutos, desde a entrada da ordem de serviço até a entrega na casa do cliente (delivery).<br>
Pizza-Express anuncia a entrega em uma hora.<br>
Pizza-Express usa atualmente computadores para armazenar as operações e as funções usuais do negócio, mas não auxiliam nas funções para processar a entrega dos pedidos dos seus clientes.<br>
Elonn Muske, o gerente de sistemas de informação é o encarregado para desenvolver uma aplicação do software para identificar a localização de lojas de pizza Pizza-Express mais próxima do cliente e para criar o sistema de software necessário para operá-las.<br>
O patrocinador deste projeto, a empresa Papa-Léguas Delivery, disse que o futuro da Pizza-Express depende deste projeto.<br>
A equipe deverá investigar uma opção para entregar a pizza em menos de 30 minutos.<br>
A sua idéia é montar lojas de pizza Pizza-Express que não teriam nenhum espaço de varejo, pois a sua função é somente receber ordens, preparar e entregar as pizzas.<br>
A loja deverá ser localizada o mais próximo do cliente receberá a ordem através de uma central, processará, e entregará a ordem dentro de 10 ou 15 minutos da entrada do pedido.<br>
Há dois projetos do desenvolvimento do software identificados aqui:<br>
primeiro é um sistema de software para o atendimento do pedido e para encontrar localização da fábrica da pizza mais próxima do cliente para fazer a entrega; e
segundo é um sistema de software para suportar operações da fábrica de pizzas.<br>

# Análise de requisitos funcionais e não-funcionais
Requisitos funcionais: O sistema precisa processar o recebimento do pedido, buscar pizzarias de acordo com a localização do cliente, direcionar o pedido para a pizzaria, monitorar o status do pedido, cronometrar o pedido e o encerrar quando for necessário. <br>
<br>
Requisitos não funcionais: A resposta a confirmação do pedido do cliente deve ser imediata, o sistema deve estar de acordo com as normas de acessibilidade, o sistema deve suportar lidar com uma grande quantidade de pedidos ao mesmo tempo. 

# Diagrama de casos de uso

![image](https://github.com/camilavrls/UML-Classroom-FCI/assets/86975387/8c2a5f27-ab65-418e-8ad1-4ce602e8312f)
![WhatsApp Image 2023-09-19 at 20 01 41](https://github.com/camilavrls/UML-Classroom-FCI/assets/86975387/519d4213-7d8c-4957-b603-431ebf5cd158)
![WhatsApp Image 2023-09-19 at 20 17 23](https://github.com/camilavrls/UML-Classroom-FCI/assets/86975387/d5052d41-b9a4-4130-884b-668983a61d59)
![WhatsApp Image 2023-09-19 at 20 27 37](https://github.com/camilavrls/UML-Classroom-FCI/assets/86975387/1bde9d12-988a-42f8-88f7-8a47c5c7e215)

<br>


# Descrição dos casos de uso
Caso de uso 1: solicitação e entrega do pedido <br>
Contexto: solicitação e entrega do pedido <br>
•	Cliente confirma o pedido <br>
•	Sistema recebe o pedido <br>
•	Sistema busca as pizzarias mais próximas com base na localização do cliente <br>
•	Sistema direciona o pedido para a pizzaria mais próxima encontrada <br>
•	Pizzaria aceita o pedido <br>
•	Pizzaria começa a preparar o pedido <br>
•	Pizzaria registra no sistema que o pedido está em preparação <br>
•	Pizzaria termina o pedido e registra no sistema que saiu para entrega <br>
•	Entregador entrega o pedido e registra entrega no sistema <br>
•	Sistema contabiliza o tempo do processo <br>
•	Sistema encerra o pedido <br>
<br>

# Diagrama de sequencia

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Componentes

*&lt;Diagrama para exibir a relação estrutural dos componentes de um sistema de software

# Decisões de arquitetura

*&lt;Descrever a infraestrutura escolhida para arquitetura do projeto&gt;*

# Diagrama de implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
