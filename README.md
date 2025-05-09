# API-Ecommerce
projeto de desenvolvimento de API para E-commerce usando python e flask

== instalar o python e configurar o path e vscode antes de começar a usar a aplicação ==

 <h2>instalar e configurar o postman de acordo com o projeto</h2>
 *baixar o arquivo swagger.yaml e realizar o import no postman como postman collection
 <br>
 *abrir o vscode e baixar as bibliotecas através do documento requirements em um venv usando o comando: pip3 install -r requirements.txt
 <br>
 *no terminal, usar o comando "flask shell", em seguda o comando "db.create_all()" para criar os Models no db, e por último o comando "db.session.commit()" para realizar o commit das informações no db
<br>
 *após executar os comandos acima, saia do banco de dados usando o comando "exit()"
 <br>
 *baixe a extensão SQLite Viewer para conseguir visualizar o banco de dados e, após isso, selecione-o como editor do seu banco de dados
 <br>
 *configure a baseUrl, para isso abra a aba environments do postman e clique no símbolo de + (Create new Environment). Feito isso, crie uma variável com o nome "baseUrl" e defina o seu valor host, obtido no terminal ("Running on http://...") ao rodar a aplicação no vscode. cole essa URL em Initial Value.
 <br>
 *após configurar a URL, atualize o environment da api para o environment criado localmente, podendo ser alterado na parte superior direita do postman
