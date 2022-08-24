Basic
=========

Aqui serão executadas as tarefas básicas de instalação de pacotes e configuração do Firewall UFW.

Tasks
------------

Substitui Arquivo sources.list  
Instala pacotes essenciais  
Definir Hostname do computador  
Instala UFW  

Variáveis
--------------

Não serão usadas variáveis nessa role.

Handlers
------------

<p>addInHostsFiles</p>
<p>RestartServer</p>
<p>Atualização do repositorio do Debian</p>
<p>Habilitar acesso SSH</p>
<p>Habilitar acesso HTTP</p>
<p>Habilitar acesso HTTPS</p>
<p>Habilitar acesso MariaDB localhost</p>
<p>Regra input default - DROP</p>
<p>Regra outgoing default - ACCEPT</p>
<p>Habilita o UFW</p>



Licença
-------

BSD

Autor
------------------

Paulo Xavier
