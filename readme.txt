;;;;;;;;;;;;;importar o site wordpress;;;;;;;
1. instalar xampp
2. criar banco de dados, latin2_general_ci
usu�rio padr�o: root; senha:*vazio*
3.fazer as configura��es para envio de email
4. mover o installer.php e o scardosolp para o projeto em htdos no xampp
5.acessar: localhost/nomedo projeto/installer.php
6.seguir a instala��o, colocar o nome do banco de dados, usu�rio e senha criados anteriormente
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;envio de email;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;configura��o xampp;;;;;;;;;;;;;;;;;;
;;arquivo php.ini, na mail function;;;;;;;;;;

[mail function]
SMTP=smtp.gmail.com
smtp_port=587
sendmail_from= lppscalina@gmail.com
sendmail_path= "\"C:\xampp\sendmail\sendmail.exe\" -t"

;;arquivo sendmail.ini, usando a senha de apps do google;;;;

[sendmail]
smtp_server=smtp.gmail.com
smtp_port=587
error_logfile=error.log
debug_logfile=debug.log
auth_username=lppscalina@gmail.com
auth_password=ksyuogtsxmqsgitn
force_sender=lppscalina@gmail.com