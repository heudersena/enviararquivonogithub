# enviararquivonogithub
Tutorial de como enviar arquivos para o GITHUB
<br>
1º PASSO =<br>
ENTRAR NO SITE GITHUB <br>

2º PASSO =<br>
CRIE UM NOVO REPOSITÓRIO<br>

3º PASSO =<br>
OLHA EU ESTOU PARTINDO E ACREDITANDO QUE VOCÊ TENHA INSTALADO O SOFTWARE NECESSÁRIO NO SEU WINDOWS OU LINUX, QUE GERENCIA O UPLOAD PARA O SERVIDOR DO GITHUB, ENTÃO VAMOS LÁ, CASO VOCÊ NÃO SAIBA COMO INSTALAR PROCURE UM TUTORIAL QUE TE AJUDE A INSTALAR NA SUA MAQUINA.
	<br>git config –global user.name “seu nome”<br>
	git config –global user.email “seuemail@email.com”<br>
4º PASSO=<br>
CRIE UM REPOSITÓRIO (PASTA) EM SEU COMPUTADOR COM O MESMO NOME DO DIRETÓRIO CRIADO NO GITHUB.<br>

5º PASSO=<br>
ABRA O TERMINAL DO GIT NO DIRETORIO CRIADO.<br>
	git init<br>

6º PASSO=<br>
	git remote add origin <aqui vai o endereço do ssh que você criou no github>
	exemplo: git remot add origin https://github.com/heudersena/sisTotal.git<br>

7º PASSO =<br>
	git pull origin master<br>

8º PASSO=<br>
	git add <nome do arquivo><br>
	
	ou usa o comando de baixo que envia todos de um só vez para o github<br>

	git add . <br>

9º PASSO=<br>
	git commit -m “escreva uma mensagem de sua preferencia”<br>

10º PASSO=<br>
	git push origin master<br>


========== BONUS =======<br>
ao trabalhar em equipe é bom ter a boa pratica de fazer o git fetch origin, caso outra pessoa que tambem participe do projeto fazer uma alteração do push o proxímo será regeitado, por isso á importância dessa pratica.
<br>
E-mail: contato@galeguinhodobrasil.com.br<br><br>
whatsapp: (61)9 9302-9884<br>
