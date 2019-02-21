# LearningMysql
Learning Mysql

## Install MariaDB in Arch

```
# sudo pacman -S mariadb
# mysql_install_db --user=mysql --basedir=/usr --datadir=/var/lib/mysql
# systemctl start mariadb
# mysql_secure_installation
# systemctl restart mariadb
# mysql -u root -p

```

参考：
https://wiki.archlinux.org/index.php/MySQL_(%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87)

DDL: Data Definition Language, 数据定义语言

用来创建或者删除存储数据用的数据库以及数据库中的表等对象。

包括： CREATE DROP ALTER
