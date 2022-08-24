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

addInHostsFiles  <br />
RestartServer  <br />
Atualização do repositorio do Debian  <br />
Habilitar acesso SSH  <br />
Habilitar acesso HTTP  <br />
Habilitar acesso HTTPS  <br />
Habilitar acesso MariaDB localhost  <br />
Regra input default - DROP  <br />
Regra outgoing default - ACCEPT  <br />
Habilita o UFW  <br />


Licença
-------

BSD

Autor
------------------

Paulo Xavier
