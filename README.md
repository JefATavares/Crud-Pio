# CRUD PROJETO BAR DO ZÉ

Para a criação deste projeto utilizamos o Visual Studio para criação do layout e o código C# e o SQLServer para utilização do banco. O projeto se trata de uma tela de cadastro, onde será feito o cadastro de barman de um bar.

## Criação do banco de dados
No SQLServer iremos criar a tabela de funcionário com os campos Nome, e-mail, Senha, Endereço e ID, onde o ID será a chave primária abaixo está a tabela criada no SQL:

![Banco de Dados](https://user-images.githubusercontent.com/105616979/168860781-8671e2fd-4461-40a1-b8e7-16d18e51736f.jpg)


## Visual Studio
Ao abrir o Visual Studio  criamos a tela de cadastro com as seguintes funções e campos NOME, E-MAIL, SENHA, ENDEREÇO e ID, os Botões CREATE, READ, UPDATE, DELETE, e incluir um DATAGRIDVIEW, está pronto o layout da tela de cadastro conforme a imagem abaixo:

![Tela de cadastro_1](https://user-images.githubusercontent.com/105616979/168852197-9f5a47ef-9c8c-4135-a6f0-183231c887a2.jpg)

Para darmos as funçoes para as  principais opções na tela de cadastro sera necessario fazer a conexão com o banco onde o codigo utilizado abaixo é necessario:

(Img)

## Fução Create.
Para que a função incluir esteja funcionando,é necessario fazer com que ao clicar no botão Crete, os dados digitados nos campos sejam armazenados no banco de dados atravez dos codigos abaixo:

(Img)

Exemplo de inclusão:

(Img)

Dados incluso:

(Img)

Em caso de erro presente fizemos a sequencia de comandos try catch para nos apensentar a mensagem de erro conforme imagens abaixo:

(Img)

linhas de comandos try catch:

(Img)

## Função Read
para função consultar no banco de dados, fizemos com que ao clicar no botão Read de o comando de consult pela chave primaria no banco, fazendo assim com que retorne o usuario de acordo com o ID(chave primaria) e nos mostre na tabela, os codigos para fazer a conexão com o banco e dar o comando a ele na imagem abaixo:

(Img)

abaixo temos uma consulta efetuada:

(Img)

Em caso de erro é utilizado o mesmo esquema de try catch:

(Img)

## Função Update

Para fazer uma alteração de cadastro o botão Update basta colocar o numero do ID(chave primaria) e clicar Update. Para essa função funcionar é necessario que ao coloar o ID, apartir desse ID a informação do campo que deseja alterar foi utilizado os comandos abaixo:

(Img)

Dados de um cadastro ja efetuado:

(Img)

Efetuando a alteração em um cadastro:

(Img)

Try catch em caso de erro:

(Img)

## Função Delete

Para a função de deletar um cadastro dentro do banco de dados, foi necessario a utilização do codigo abaixo para que quando clicar em delete o comando seja executado no banco e remova o cadastro:

(Img banco)

Deletando um castro:

(Img deletando um cadastro)

(codigo execultando exclusão)

Em caso de erro a mensagem é exibida com a sequencia de comando try catch apresentada

(Img comando)

(Img erro)

obrigado!

