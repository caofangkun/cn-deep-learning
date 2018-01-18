### 安装 Anaconda

Anaconda 可用于 Windows、Mac OS X 和 Linux。可以在 https://www.continuum.io/downloads 上找到安装程序和安装说明

安装后可以执行下如下命令，升级下相关软件

```conda upgrade --all```


### 管理包

安装包的方式 ：``` conda install package_name```

例如，要安装 numpy，键入 ```conda install numpy```
以同时安装多个包。类似 ```conda install numpy scipy pandas``` 的命令会同时安装所有这些包
还可以通过添加版本号（例如 ```conda install numpy=1.10```）来指定所需的包版本

### 管理环境

终端中使用 ```conda create -n env_name list of packages```
在这里，```-n env_name``` 设置环境的名称（```-n``` 是指名称），
而 ```list of packages``` 是要安装在环境中的包的列表。
例如，要创建名为 ```my_env``` 的环境并在其中安装 ```numpy```，请键入 ```conda create -n my_env numpy```


