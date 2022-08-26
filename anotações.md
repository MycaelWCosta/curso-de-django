<style>
    .esplicacao-anterior{
        color:red; font-weight: bold
    }
    .codigo{
        color:#7CFC00;
        font-weight: bold
    }
    .variavel{
        color:#FF00FF;
        font-weight: bold;
    }
    h3{
        font-size: 20px
    }
</style>
<link >
<h1>Framework Django 2</h1>
<p><a href="https://www.youtube.com/watch?v=LZsjuSBW5YM&list=PLnDvRpP8BnewqnMzRnBT5LeTpld5bMvsj&index=1">curso em questão</a></p>
<dl>
    <p>Será visto no projeto.</p>
    <li>CRUD</li>
    <li>autenticação</li>
    <li>Bootstrap</li>
</dl>

<h2>iniciando projeto do curso</h2>

<p>Será visto a diferença entre app e projeto no Django, ao passo que criamos um app e um projeto.</p>

<p>Enquanto Projeto é criado uma vez na vida, app são diversas partes do projeto, podendo ser uma ou milhares de vezes não tem limite.</p>

<hr>
<p>Foi criado um Arquivo com o comando <spam class="codigo">virtualenv {nome do aquivo}</spam>, que no caso é ventodo (mas deveria ser venvtodo, eu que errei o nome😅) </p>
<div class="esplicacao-anterior">
    <p>virtualenv: Ele cria um ambiente que possui seus próprios diretórios de instalação, que não compartilha bibliotecas com outros ambientes virtualenv (e opcionalmente também não acessa as bibliotecas instaladas globalmente).</p>
</div><hr>
<p>Depois ativamos a venv como o comando <spam class="codigo">source ventodo/Scripts/activate<spam/></p>
<div class="esplicacao-anterior">
    <p>Ativando uma  virtualenv <br>Após criar uma virtualenv, precisamos ativá-la para que possamos instalar os pacotes necessários do projeto. Para isso, utilizamos o seguinte comando: source nome_da_virtualenv/bin/activate (Linux ou macOS) nome_da_virtualenv/Scripts/Activate (Windows)</p><hr> 
</div>
<p>Essa parte do processo eu tive que fazer no git bash , pois pelo terminal não funciona.</p><hr>
<p>Após foi instalado o django pelo comando <spam class="codigo">pip install django</spam></p><hr>
<p>Após instalar o django, use <span class="codigo">django-admin --version</span></p><hr>
<p>Então vai ser dado íniciado o projeto com o comando <spam class="codigo">django-admin startproject todo</spam> onde todo é o nome do projeto.</p><hr>
<p>se você digitar <spam class="codigo">code .</spam> no git bash ,sem estar no vscode, ele abre o vscode</p><hr>
<p>ai foi criado a pasta do projeto com o nome que foi escrito no final no caso "todo".</p><hr>
<h3>Pastas dentro do Projeto</h3>
<dl>
    <li>__init__.py</li>
    <p>aqui vai arquivos que precisam ser executados.</p>
    <li>settings.py</li>
    <p>arquivos de segurança do projeto.</p>
    <li>urls.py</li>
    <p></p>
    <li>wsgi.py</li>
    <p></p>
    <li>wsgi.py</li>
    <p></p>
    <li>manage.py</li>
    <p>arquivo que está relacionado ao terminal.</p>
</dl><hr>

<p>usamos o comando <spam class="codigo">django-admin startapp noomeDaApp</spam> para criar uma aplicação</p>

<p>Devemos registrar os aplicativos na variavel <spam class="variavel">INSTALLED_APPS</spam> que se encontra no arquivo <spam class="variavel">settings.py</spam> através da sequinte forma: <spam class="codigo"><br>'tasks',<br>'about',<br>'users',<br>'nomeDaApp',</spam></p

