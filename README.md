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

## DDL: Data Definition Language, 数据定义语言

用来创建或者删除存储数据用的数据库以及数据库中的表等对象。

包括： 

CREATE 创建数据库和表对象

DROP 删除数据库和表对象

ALTER 修改数据库和表对象的结构

## DML: Data Manipulation Language, 数据操纵语言

用来查询或者变更表中的记录。

包括： SELECT INSERT UPDATE DELETE

## DCL: Data Control Language, 数据控制语言

用来确认或者取消对数据库中的数据进行的变更。
除此之外，还可以对RDBMS的用户是否有权限操作数据库中的对象（数据库表等）进行设定。

包括：

COMMIT： 确认对数据库中的数据进行的变更

ROLLBACK： 取消对数据库中的数据进行的变更

GRANT： 赋予用户操作权限

REVOKE： 取消用户的操作权限
