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
<h1>1)BAIXAR E INSTALAR O GIT , TAMBÉM REINICIAR O O VSC</h1>
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


</h2>

