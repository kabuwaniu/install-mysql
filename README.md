# install-mysql
sudo apt-get install mysql-server

#查看进程中是否有mysql服务

ps ajx|grep mysql

停止服务
sudo service mysql stop

重启服务
sudo service mysql restart

mysql -u root -pmysql
