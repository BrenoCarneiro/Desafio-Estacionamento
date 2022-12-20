# DIO - Trilha .NET - Desafio de projeto


Sistema para um estacionamento, que pode ser usado para gerenciar os veículos estacionados e realizar suas operações, como por exemplo adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

![image](https://user-images.githubusercontent.com/102473053/208756807-61973442-19ba-425d-9768-8f49b230adba.png)

A classe Estacionamento contém três variáveis, sendo:

- precoInicial: Tipo decimal. É o preço cobrado para deixar seu veículo estacionado.

- precoPorHora: Tipo decimal. É o preço por hora que o veículo permanecer estacionado.

- veiculos: É uma lista de string, representando uma coleção de veículos estacionados. Contém apenas a placa do veículo.

A classe contém três métodos, sendo:

- AdicionarVeiculo: Método responsável por receber uma placa digitada pelo usuário e guardar na variável veiculos.

- RemoverVeiculo: Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: precoInicial * precoPorHora, exibindo para o usuário.

- ListarVeiculos: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".

No menu interativo há as seguintes opções:
- Cadastrar veículo
- Remover veículo
- Listar veículos
- Encerrar
