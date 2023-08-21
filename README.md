![QQ截图20230822002323](https://github.com/kayaladream/Clash-Core-Change/assets/136615856/23fecc3f-eaac-4316-a718-221f2bcb0463)
### 概述：
-  我们最喜欢使用的代理软件Clash for windows，因为原版是集成的Premium内核，所有并不支持Xray的一些协议，如VLESS、XTLS、Trojan、Hysteria等强大的自建节点，于是也就就衍生出来了Clash.Meta内核。
- 不过Clash for windows并不支持在客户端更换内核，而且Meta内核与Clash for windows还有些兼容性的问题，所以有些人就会频繁更换内核，但操作起来很麻烦。本项目利用批处量bat文件一键来回切换Premium、Meta内核，方便快捷。

### 使用方法：
- 下载“Clash-Core-Change.bat”与“Clash.Meta内核“一起放在此目录下
 `%LocalAppData%\Programs\Clash for Windows\resources\static\files\win\x64`
- 右击“Clash-Core-Change.bat”批处理文件选择”创建快捷方式“
- 打开Clash for windows，选择”常规“，鼠标移到”配置文件主目录“，点击”打开目录“
- 将第2步创建好的批处理快捷方式剪切到”配置文件主目录“
-双击“Clash-Core-Change.bat - 快捷方式”，即可切换内核

- > 下次需要更换内核就可以在Clash for windows客户端”常规“→”配置文件主目录“→”打开目录“实现快速一键切换。
- > Clash for windows客户端会自动重启使用新内核。
- >Clash for windows免安装版本如不是默认安装目录，则需要手动重启Clash for windows。

- > [Clash.Meta内核下载地址](https://github.com/MetaCubeX/Clash.Meta)
