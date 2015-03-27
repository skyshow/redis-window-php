php 安装redis

1.解压php_igbinary和php_redis
2.解压后的 php_igbinary.dll和php_redis.dll放入php的ext目录下  
3.php.ini添加扩展

extension=php_igbinary.dll
extension=php_redis.dll

4.重启apache

5.php中phpinfo 看到redis，安装成功

6.解压redis-2.4.0-win32-win64.zip，window根据系统版本安装redis软件

7.	测试php

	$redis = new MyRedis();
	$redis->set('name','lilei');
	echo $redis->get('name');
	exit;


