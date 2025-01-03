

# Cursor Pro 自动化工具使用说明

## 功能介绍
自动注册账号，自动刷新本地token，解放双手。

## 重要提示
**1.确保你有一个chrome浏览器；如果你没有；[下载地址](https://www.google.com/intl/en_pk/chrome/)**

**2.首先，你要自己已经登录过账号不管你的账号是不是有效，登录是必须的。**

**3.有一个稳定的网络连接。尽量是国外的节点。不要开启全局代理。一定不要开启全局代理。**


## 运行方法

### Mac 版本
1. 打开终端，进入应用所在目录
2. 运行命令：授权文件可以执行
```bash
chmod +x ./CursorPro
```
3. 运行程序：
   - 在终端中运行：
```bash
./CursorPro
```
   - 或直接在访达（Finder）中双击运行

### Windows 版本
直接双击运行 `CursorPro.exe`


## 如何验证是否有效
**运行脚本完成之后，重启你的编辑器，你会看到下面图片的账号和你的脚本输出的日志账号一致就搞定了。**
![image](./screen/截屏2025-01-01%2010.20.08.png)


## 使用注意事项

1. 运行环境要求：
   - 稳定的网络连接
   - 足够的系统权限

2. 使用过程中：
   - 请勿手动关闭浏览器窗口
   - 等待程序自动完成所有操作
   - 看到"脚本执行完毕"提示后再关闭程序

## 常见问题解决

1. 程序运行过程中卡住：
   - 检查网络连接
   - 重启程序重试


## 免责声明
本工具仅供学习研究使用，请遵守相关服务条款。使用本工具产生的任何后果由使用者自行承担。

## cursor-id-modifier 使用说明
> 工具来源 https://github.com/yuaotian/go-cursor-help

下载之后，使用管理员权限运行就行。

mac方式：
```bash
chmod +x ./cursor-id-modifier
sudo ./cursor-id-modifier
```

windows方式：
右键选择以管理员权限运行就行。


仓库源码来自开源；自行优化了验证和邮箱注册逻辑；解决了无法获取邮箱验证码的问题。