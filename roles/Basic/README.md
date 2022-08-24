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

addInHostsFiles  
RestartServer  
Atualização do repositorio do Debian  
Habilitar acesso SSH  
Habilitar acesso HTTP  
Habilitar acesso HTTPS  
Habilitar acesso MariaDB localhost  
Regra input default - DROP  
Regra outgoing default - ACCEPT  
Habilita o UFW  


Licença
-------

BSD

Autor
------------------

Paulo Xavier
