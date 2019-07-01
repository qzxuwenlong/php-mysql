# php-mysql
MySQL是一个 **关系型数据库管理系统**
mysql基本的增删改查
# php连接mysql
#### 最近时间匆忙，先记录一下以前没有注意到的点
* html表单请求php要在form 元素添加action="mysql.php"
* php增删改查 **传变量到sql语句时变量一定要加 ' 号例子:'"$name"'**
* mysql-query("set name 'utf8'") //设置utf-8 ; //一般加到连接数据库的php里面
* $con =mysql_connect("localhost","root",""); //保存登录mysql的方法
* mysql_error(); //php操作mysql出现问题时，能看到哪里出错
* $mysql_select_db("数据库名",$con); //登录要登录那个数据库 在第一个参数据库名
* $rows=mysql_quer($sql,$con);  //发送请求数据
* while($row=mysql_fatch_array($rows)); //获取请求的数据
echo $rot['字段名'];
[新版连接方式](https://github.com/qzxuwenlong/php-mysql/blob/master/img/2bda0ee4ed6de97a49632e186b25b6f.png)
