flutterw
========
flutterw is a shell script which downloads and executes the Flutter SDK with the exact version defined in itself. It can keep the flutter sdk version consistent for your co-workers and on the CI servers.

Feature
--------
- keep the flutter sdk version consistent for your co-workers and on the CI servers.
- added extra commands like "./flutterw dart" can run a dart command, for example:
```java
./flutterw dart --version
```
- support windows os, need run with git bash

Config
--------
- Config flutter version:
```java
flutter_channel="stable"
flutter_version="1.9.1+hotfix.6"
```

Run
--------
```java
./flutterw --version
```

Thanks
--------
https://github.com/LinXiaoTao/flutterw

# Contact me:

- Blog:http://blog.csdn.net/masonblog
- Email:MasonLiuChn@gmail.com

中文：
---------

flutterw
========
flutterw 用来下载Flutter SDK,类似于gradlew。通过在脚本内配置特定版本号，使得同一工程的所有开发者或CI服务器（例如Jenkins）使用Flutter的版本一致。

功能
--------
- 保证所有开发者或CI服务器（例如Jenkins）使用Flutter的版本一致
- 添加了一些额外的常用命令，如 ./flutterw dart 可以直接运行dart命令:
```java
./flutterw dart --version
```
- 支持windows系统，需要在 git bash 环境下运行

配置
--------
- 配置flutter版本号:
```java
flutter_channel="stable"
flutter_version="1.9.1+hotfix.6"
```

执行
--------
```java
./flutterw --version
```

感谢
--------
https://github.com/LinXiaoTao/flutterw

# Contact me:

- Blog:http://blog.csdn.net/masonblog
- Email:MasonLiuChn@gmail.com