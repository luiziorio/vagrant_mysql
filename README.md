# vagrant_mysql
Infrastructure and Cloud Computing - MBA ES21

Tarefa:
Subir uma máquina virtual, usando Vagrant, com MySQL instalado e que esteja acessível no host da máquina na porta 3306. Enviar a URL Github do código. Atividade individual ou em grupo, vocês que definem.

Box utilizada "anhdht/mysql"
https://app.vagrantup.com/anhdht/boxes/mysql
Porta 3306: config.vm.network "forwarded_port", guest: 3306, host: 3306

Para checar o mysql na maquina:
1-Vagrant ssh
2-mysql -u root -p
3-senha: F&Bb7_T!$RNkgMKn
Será comprovado que voce cairá dentro do aplicativo do mysql para começar a trabalhar o banco.

Arquivo VagrantFileAnexo.
Obrigado.
