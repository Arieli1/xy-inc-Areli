# xy-inc-Areli
testezup POI


Programa feito em Java web, utilizando padrão MVC,JSP,Bootstrap para front end e banco de dados MYSQL
Teste realizados:
1) entrada de dados positivos e valores negativos abaixo de 0 recusados.
2) CRUD (INSERT,DELETE E UPDATE ) estão funcionando.
3) retorno de todos os dados cadastrados no sistema.
4) retorno do POI mais proximo, com entrada de informações dos eixos x,y e distância.

ESTRUTURA DO SISTEMA 
/TESTEZUP

/TESTEZUP/WEB - TELAS DO SISTEMA 

/TESTEZUP/SRC/JAVA/MODEL - CLASSE PARA CONEXAO COM BANCO DE DADOS E METODOS GET E SET.

/TESTEZUP/SRC/JAVA/CONTROLLER - CLASSE DE CONTROLE DO SISTEMA E DAO

ARQUIVOS PARA EXECUÇÃO 

ABRIR NETBEANS 
Clicar em Arquivo - Importar projeto - de zip e escolher o arquivo testezupit.
Adicionar o jar do mysql (arquivo em anexo) ao projeto.Botão direito em cima da pasta Biblioteca- Adicionar JAR/PASTA.
No Netbeans, clicar em ferramentas - Servidor e adicionar servidor Glassfish.
Abrir XAMPP, clicar em start apache e mysql. Na opção Mysql clicar em administrador e esperar abrir o navegador, criar uma database chamada zup . O script de banco de dados esta em anexo, so executar o mesmo.Informações de conexação do banco esta na classe Conexao na pasta model.
Executar a classe conexao para validar a conexão com o banco.
Depois botão direito em cima do projeto e e clicar em executar. A URL localhost:8080/testezup/index.jsp
