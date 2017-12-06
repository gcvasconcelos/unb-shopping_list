Para compilar o algoritmo:
	1.Abra o terminal;
	2.Entre no diretorio Sources;
	3.digite make all;
	4.digite ./run main;
	5.Siga  as orientacoes do algoritmo;



# Projeto Final - Métodos de Programação

Este projeto consiste no trabalho final da matéria de Métodos de Programação ofertada pelo Departamento de Ciência da Computação e lecionada pelo professos Jan Correa. 

O seguinte projeto tem o objetivo de botar em prática os métodos ensinados na disciplina por meio do desenvolvimento de uma aplicação, implementada em C++ e seguindo o padrão de de codificação desenvolvido pela Google e descrito no CPPGuide.

## Funcionamento



## Descrição do aplicativo

O aplicativo permite que o usuário gerencie uma lista de compras que ele quer fazer em um estabelecimento qualquer. Supondo que o usuário queira fazer compras em um supermercado, pode começar fazendo uma lista de compras nova. O usuário pode usar uma lista de compras em branco onde pode adicionar e remover itens. Existem vários itens cadastrados e novos itens podem ser cadastrados. O sistema deve manter a consistência dos itens, verificando se diferentes nomes são na verdade o mesmo item (usando, por exemplo, o número do código de barras).O usuário também pode utilizar listas de compras anteriores que podem ser editadas. 

O usuário vai então efetuar a compra indo ao caixa. O aplicativo deve permitir que o usuário confira se o preço dos itens que aparecem no caixa são os mesmos que constam nas etiquetas nas estantes (ou outro lugar onde a informação sobre o preço foi dada).  

## Desenvolvimento do código

O código acima foi organizado de forma modular desenvolvido orientado a testes, utilizando o framework GTest, de forma a garantir seu funcionamento de acordo com as especificações. Para se assegurar da cobertura que os testes tem do código, foi utilizado o verificador de cobertura gcov. Outra técnica usada para manter essa garantia foi a constante revisão do código pelo membros do grupo, da forma como foi ensinada em sala de aula.

O analisador estático escolhido para o programa foi o cppcheck e os erros apontados por esta feramenta foram resolvidos. Para detectar vazamentos de memória, foi utilizada a ferramenta valgrind.

O github foi a ferramenta de versionamento e acompanhamento do desenvolvimento orientado a testes do código.

Para faciliar o entendimento do código também foram contruídas assertivas de entrada e saída, além de comentários sobre o funcionamento das funções e sobre o motivo das escolhas na hora do desenvolvimento. Também foram explicadas, por meio de comentários, as interfaces ímplicitas e ímplicitas de cada função e quais são seus requesitos e hipóteses. Tudo isso foi aplicado utilizando as orientações ensinadas pelo professor.

A modelagem das estruturas de dados e do 'banco de dados' foram decicidas de forma unânime e em grupo, para que todos soubessem antes do desenvolvimento do código em si, o que devia ser implementado. 

## Gerenciamento da equipe

Para o gerenciamento da equipe e do projeto foram aplicados os conceitos de KanBan e do método de desenvolvimento ágil SCRUM, principalmente o conceito da sprint. Estes conceitos foram aplicados no Trello, ferramenta que se encaixou perfeitamente para esta aplicação.

A maior parte do desenvolvimento ocorreu em grupo, sendo os integrantes Jonas Prado e Felipe Ayres os maiores contribuidores.

As horas de trabalho foram estimadas pelo time de desenvolvimento.
