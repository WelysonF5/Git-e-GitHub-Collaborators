<H1>Git</h1><br>
<h2>Trata-se do compartilhamento e divisão de tarefas entre desenvolvedores. É possivel separar códigos e testa-los, além de isolar versões para teste e desnvolvimento garantindo que seja realizado de forma organizada e segura;<br>
certificar o local correto da pasta do projeto;
<br>
1)Abri o terminal,
<br>
2)echo "# <!--nome-do-projeto-->" >> README.md<br>
//Para começar um projeto do zero//
<br>
3)git init 
<br>
<!--comçar um projeto existente--><br>
<!--se já não estiver instalado dará erro.-->
<br>
<br>
<h1>1)BAIXAR E INSTALAR O GIT , TAMBÉM REINICIAR O VSC</h1>
<br>
2)git init
<br> 
3)git add .
<br>
5)git config --global user.email "<!--seu-email-->
<br>
6)git config --global user.name "<!--seu-nome-->
<br>
7)git commit -m "<!--nome-do-projeto-->"
<br>
<br>
8)git branch -M main
<br>
9)git remote add origin (ou SSH)https://github.com/<!--usuario-repositorio--> <br>
//Os protocólos SSH podem ser usados para gerar chaves de acesso retrito ao projeto.
<br>
10)git push -u origin main <br>
//se o GitHub não for configurado previamente dará erro
<br>
<br>
<h1>CONFIGURANDO O GITHUB</h1>
<br>
1)ssh-keygen -t ed25519 -c "<!--seu-email--><br>
//Verificar a pasta de Usuário no explorador, cópiar a chave publica.
<br>
2)git push -u origin main
<br>
<br>
<br>
<br>
<h2>
<h1>Clonando Repositório para permitir que outras pessoas possam escrever no código</h1>
<br>
AO CÓPIA O PROJETO DO DIRETÓRIO NO GITHUB,
ABRIR O TERMINAL WINDOWS POWERSHELL,
<br>
1)git clone <!--url-colar-->
<br>
Abrir Pasta no vsc,
<br>
Abrir o terminal,
<br>
1)git status <br>
//registros em "cor vermelho" significa que as atualizações não foi global
<br>
2)git add . <br>
//adicona as atualizações de uma vez(global)
<br>
3)git status
//Alteração de "cor verde" significa que os eventos atualizados estão em todo o projeto, mas só serão aplicados após o 'commit'
<br>
<br>
4)git commit -m "<!--mensagem de atualização do usuário-->" <br>
//Faz com que as alterações sejam salvas tanto no clone do projeto local
<br>
<br>
<h1>HISTÓRICO DE ATUALIZAÇÕES DO COMMIT
</h2>
<br>
1)git log<br>
//OO histórico de atualizações
<br>
<br>
<h1>ENVIANDO COMMIT</h1>
1)git remote <br>
//irá abrir o [origin] com erro
<br>
O USUÁRIO DO PROJETO ORIGIN (o primeiro)DEVERÁ PERMITIR QUE OS COLABORATIVOS SEJAM ADICINADOS MANUALMENTE.
1)Abrir o GitHub>settings>collaborators,<br>
2)adicionar usuários colaborativos,
<br>
O COLABORATIVO DEVERÁ ESCREVER NO TERMINAL,<br>
1)git push origin main <br>
//Com isso as atualizações do cobalorativo serão implementados no projeto do diretório main no GitHub
<br>
<br>
<h1>PUXANDO AS ATUALIZAÇÕES DO GITHUB PARA O PRIEMIRO USUÁRIO</h1>
<br>
1)git pull origin main
<br>
<br>
<h1>MANIPULANDO O GIT NO GITHUB</h1>
<br>
É possivel "commitar" o projeto, através do Control de Recursos do vsc
<br>
<br>
<h1>COMO REVERTER ATUALIZAÇÕES</h1>
<br>

 1)git log<br>
 //Buscando o id, de qual alteração será revertida
 <br>
 2)git revert "<!--id-colar-->"
 <br>
 <br>
 <h1>COMO APAGAR UM COMMIT DO HISTÓRICO</h1>
 <br>
 1)git log
 <br>
 2)git revert --hard "<!--id-colar-(do commit anterior-->"
 <br>
 <br>
 <h1>COMO ALTERAR UMA MENSAGEM DE UM COMMIT QUE JÁ LANÇADO</h1>
 <br>
 1)git commit --ament -m "Mensagem correta"
<br>
<br>
<h1>COMO FAZER COM QUE O GIT OCULTE DETERMINADOS ARQUIVOS</h1>
<br>
Na mesma pasta do projeto, criar arquivo '.gitignore',<br>
escrever cada linha o nome do arquivo com dados não abertos aos colaborativos
<br>





</h2>




</h2>

