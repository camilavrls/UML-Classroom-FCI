<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
Pizza-Expres
</center></font>

**Conteúdo**

- [Autores](#autores)
- [Descrição do projeto](#descrição-do-projeto)
- [Análise de requisitos funcionais e não-fucionais](#análise-de-requisitos-funcionais-e-não-funcionais)
- [Diagrama de casos de uso](#diagrama-de-casos-de-uso)
- [Descrição dos casos de uso](#descrição-dos-casos-de-uso)
- [Diagrama de sequencia](#diagrama-de-sequencia)
- [Diagrama de classes](#diagrama-de-classes)
- [Diagrama de componentes](#diagrama-de-componentes)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-implantação)
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

<br>


# Descrição dos casos de uso
<br>
Caso de Uso 1 

![image](https://github.com/camilavrls/UML-Classroom-FCI/assets/86975387/a4508355-6a97-43e2-9803-5813c0054820)
<br>
Caso de Uso 2

![image](https://github.com/camilavrls/UML-Classroom-FCI/assets/86975387/533cf9f0-af3a-4b4e-bb32-90f1b87a8f05)
<br>
Caso de Uso 3

![image](https://github.com/camilavrls/UML-Classroom-FCI/assets/86975387/63364f26-de06-4e78-8f91-758c6fb5429f)

<br>

# Diagrama de sequencia

![image](https://github.com/camilavrls/UML-Classroom-FCI/assets/86975387/71bdb142-6c1c-4741-a05f-151a9910de0b)
<br>

# Diagrama de classes

![image](https://github.com/camilavrls/UML-Classroom-FCI/assets/86975387/d1cc87c2-8075-4c38-aada-9e54fd9d5ed5)


# Diagrama de Componentes

![image](https://github.com/camilavrls/UML-Classroom-FCI/assets/86975387/96d40ce2-f021-41fd-afa6-9e6edcf9c8f7)


# Decisões de arquitetura

Servidores:
Um servidor para hospedar a aplicação do cliente e gerenciar a lógica de negócios.
Servidores para hospedar o processamento de pedidos, incluindo o localizador de pizzarias, o sistema de processamento de pagamentos e o sistema da pizzaria.

Banco de Dados:
Um banco de dados para armazenar informações do cliente, pedidos, pizzarias, e outros dados relevantes.

Rede:
Conexão com uma rede para permitir a comunicação entre o aplicativo do cliente, o sistema de processamento de pedidos, os servidores da pizzaria, e outros componentes.

Dispositivos de Venda:
Celulares (smartphones) para confirmar pedidos, ligados com impressoras para gerar comprovantes de pedidos.

Dispositivos de Rastreamento de Entregas:
Dispositivos ligados ao gps e ao dispositivo do entregador, para rastrear a localização dos pedidos.

Dispositivos de Pagamento:
Para processar pagamentos online, será necessário um hardware adicional para suportar transações seguras.

Sistema de Backup e Recuperação:
Infraestrutura para backup e recuperação de dados, garantindo a segurança e disponibilidade das informações.

Firewalls e Segurança:
Mecanismos de segurança, como firewalls, para proteger contra ameaças de segurança.

Câmeras de Monitoramento:
Em locais físicos, como a pizzaria, câmeras de monitoramento podem ser instaladas para segurança e registro de eventos.


# Diagrama de implantação

![image](https://github.com/camilavrls/UML-Classroom-FCI/assets/86975387/0ae27634-6ced-4196-9f91-ee038867ebff)


# Referências

*&lt;Lista de referências&gt;*
