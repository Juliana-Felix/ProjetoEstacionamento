# Projeto Estacionamento UNIESP


O UNIESP está expandindo dia a dia e a rotatividade de pessoas é crescente no centro universitário. Neste sentido, o monitoramento de acesso e a segurança do campus são questões que precisam ser melhoradas constantemente. Apesar do campus ter um estacionamento gratuito, é fundamental para a segurança desenvolver uma forma monitorar a entrada e saída de veículos (carros, motos, ônibus e bicicletas). Para isso, o presente projeto pretende desenvolver uma solução de gerenciamento do estacionamento do campus. O sistema de gerenciamento de estacionamento possui tecnologia de ponta, garantindo maior segurança e agilidade no controle de acesso de veículos.

Aluna: Juliana Félix de Souza Gomes.
Matrícula: 2021111510042.
Professor: Humberto Barros.

# Objetivo

O projeto tem o objetivo de realizar a gestão do estacionamento, possibilitando monitoramento e alterações de vagas, cadastro do cliente e do véiculo, geração de ID de vaga, e check-out.

# Parte técnica 

A solução roda no terminal utilizando o JDK.

A classe ArrayList é utilizado para fazer a gestão de dados, que é criado uma lista de objetos, a lista é encadeada, portanto não é necessário colocar a quantidade de elementos no momento da instanciação. Sempre que uma vaga é cadastrada, ela é adicionada a lista uma instanciação do objeto com os dados que foram prenchidos pelo usuário, ao final, quando é necessário apagar alguma vaga é localizado utilizando o atributo do objeto "ID" o local onde consta na lista o objeto instanciado e removido utiliando a função "remove" da classe.


# Programa em funcionamento:

menu inicial:

![image](https://user-images.githubusercontent.com/83127826/144335438-2c0672d3-c312-4f8e-ab77-203207957970.png)

A opção “1 – Cadastrar vaga” é direcionada para essa tela:

Algumas informações deverão ser preenchidas para o cadastro da vaga e no final é gerado um ID, esse ID possibilita que usuario efetua o check-out na saída 

![image](https://user-images.githubusercontent.com/83127826/144338232-903abe3a-2b5b-4b8a-a4d7-18c303623586.png)

No final é retornado para o menu novamente, selecionando a opção “2 – Pesquisar vaga” é direcionado para essa tela:

![image](https://user-images.githubusercontent.com/83127826/144338645-a054e06d-b3b7-4444-915d-15aa1dd92f76.png)

Na tela é pedido o ID da vaga que foi gerada no cadastro, após isso é mostrado as informações da vaga e se o usuário deseja liberar ou não, liberando a vaga, uma vaga fica disponível a mais, ao final é retornado ao menu.
selecionando a opção “3 – Opções de Administrador” é direcionado para essa tela:

![image](https://user-images.githubusercontent.com/83127826/144338745-490d8137-6ba9-40ae-80e5-b864d9bb2fc6.png)

Essa tela é restrita apenas para administradores, portanto é necessário digitar a palavra passe para ter acesso. Nessa tela é possível alterar a quantidade de vagas totais no estacionamento, realizar o check-out de um usuario, e listar a vagas preenchidas. Ao final é retornado a tela de menu, selecionando a opção “0 – Encerrar” o software encerra.














