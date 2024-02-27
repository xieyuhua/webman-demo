# webman-demo
webman-demo

### 安装命令行工具

```
composer create-project workerman/webman
composer require webman/console ^1.2.24
composer require -W webman/think-orm
composer require tinywan/limit-traffic
composer require shopwwi/webman-filesystem
composer require shopwwi/filesystem-oss
composer require tinywan/storage
composer require aliyuncs/oss-sdk-php
composer require webman/log
```

### 运行命令

```
chmod -R 777 ./
 php -d phar.readonly=0 ./webman build:bin
```

![d80ec7980ecabdb9c7c368c9c632445](https://github.com/xieyuhua/webman-demo/assets/29120060/b2503891-e9f6-47d0-954e-16177b1faaab)

