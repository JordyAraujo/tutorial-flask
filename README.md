# Tutorial Flask
> Este repositório tem como objetivo reproduzir o [tutorial da documentação do Flask](https://flask.palletsprojects.com/en/2.2.x/tutorial/), comentando, pesquisando, estudando e principalmente traduzindo para o português, na intenção de trazer conhecimento de forma didática e acessível.

O tutorial passa pela criação de um blog chamado Flaskr. A ideia é que usuários possam se registrar, logar e criar, editar ou deletar posts. Também será possível empacotar e instalar a aplicação em outros computadores.
Alguns comentários são feitos na primeira página e eu resolvi traduzí-los diretamente aqui:

- Assumimos que você já é familiar com Python. O [tutorial oficial](https://docs.python.org/pt-br/3/tutorial/) na documentação do Python é uma boa forma de aprender ou revisar primeiro;
- Apesar de ser pensado para dar um bom ponto de partida, este tutorial não cobre todas as características e ferramentas do Flask. Dá uma olhada no [_Quickstart_](https://flask.palletsprojects.com/en/2.2.x/quickstart/) para ver mais do que o Flask pode fazer, e então mergulhe na documentação para encontrar ainda mais. O tutorial também só usa o que é dado pelo Python e pelo Flask em si. Em outros projetos, você pode decidir usar as [Extensões](https://flask.palletsprojects.com/en/2.2.x/extensions/) do Flask ou outras bibliotecas para facilitar algumas atividades;
- O Flask é flexível. Ele não requer que você use nenhum projeto ou _layout_ particular. Porém, quando estamos começando, ajuda se formos mais estruturados e organizados. Portanto, o tutorial vai seguir uma certa estrutura, para evitar certas "armadilhas" ou "vícios" que podem ser encontrados por iniciantes, além de criar um projeto fácil de expandir. À medida que ficar mais confortável com o Flask, você poderá sair dessa estrutura e tirar maior proveito da flexibilidade do Flask;
- [O projeto completo do tutorial está disponível como exemplo no repositório do Flask](https://github.com/pallets/flask/tree/main/examples/tutorial), caso queira comparar com o nosso, à medida que proseguimos.