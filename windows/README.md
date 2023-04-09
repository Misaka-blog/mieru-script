# Windows 端使用方法

1. 打开 https://github.com/enfein/mieru/releases ，下载最新的 Windows 程序文件
2. 在存放 Mieru 的程序目录，创建一个名为 `client_config.json` 的文件，编辑，复制粘贴脚本生成的配置文件。
3. 打开命令行，使用以下命令应用配置文件

```powershell
./mieru apply config client_config.json
```

4. Mieru 客户端常用命令

* 启动：`./mieru start`
* 停止：`./mieru stop`