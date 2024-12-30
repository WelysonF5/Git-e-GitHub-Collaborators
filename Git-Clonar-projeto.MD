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