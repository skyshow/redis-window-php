php ��װredis

1.��ѹphp_igbinary��php_redis
2.��ѹ��� php_igbinary.dll��php_redis.dll����php��extĿ¼��  
3.php.ini�����չ

extension=php_igbinary.dll
extension=php_redis.dll

4.����apache

5.php��phpinfo ����redis����װ�ɹ�

6.��ѹredis-2.4.0-win32-win64.zip��window����ϵͳ�汾��װredis���

7.	����php

	$redis = new MyRedis();
	$redis->set('name','lilei');
	echo $redis->get('name');
	exit;


