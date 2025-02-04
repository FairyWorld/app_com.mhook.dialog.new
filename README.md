![GitHub all releases](https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.mhook.dialog.new/total?color=1&style=plastic) 
![GitHub release (latest by date)](https://img.shields.io/github/v/release/Xposed-Modules-Repo/com.mhook.dialog.new?style=plastic)
![GitHub issues](https://img.shields.io/github/issues-raw/Xposed-Modules-Repo/com.mhook.dialog.new?style=plastic)
![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/Xposed-Modules-Repo/com.mhook.dialog.new?style=plastic)  
[English](https://github.com/Xposed-Modules-Repo/com.mhook.dialog.new/blob/main/README_EN.md)  
# 简介
由于更新了很多功能，还放在[修复版](https://github.com/Xposed-Modules-Repo/com.mhook.dialog.fix)里并不太合适，所以另建了一个分支，主要新增核心功能就是：Frida注入，欢迎尝鲜。  
另外由于没有服务器，对话框取消新版的内置更新是直接访问github的，Frida脚本仓库和下载配置环境也是在github.com  
还有反馈可以直接在酷安->话题->#对话框取消 下发布反馈和建议，若是有github账号的，可以直接在当前issues下提交反馈（对话框取消->关于->一键反馈（酷安））  
# 功能
本模块可以取消一些强制被设置为不能取消的对话框，比如一些强制更新对话框，及一些广告（有的流氓广告总是把x弄得很小）。

## 扩展功能
1.取消按钮禁用(enabled)  
2.禁止退出(exit+finish)(可组合按键控制)  
3按关键字禁用弹框(悬浮窗+对话框)(可组合按键控制)  
4.版本自定义(版本号+版本名)  
5.伪装系统时间(系统时间+GPS时间+本地获取服务器时间)  
6.防检测本模块,Xposed,Root  
7.启动时禁用网络(可设置禁用时间)  
8.强制结束当前活动(Activity)(用组合按键控制)  
9.反禁用Xposed(简单禁用)  
## 注意事项
1.本模块不支持最新对话框和游戏对话框！（有些最新对话框与普通对话框非常像，请注意区分！）  

# 测试版更新
https://install.appcenter.ms/users/serifer/apps/Dialbox
# 更新日志
参见 [Release](https://github.com/Xposed-Modules-Repo/com.mhook.dialog.new/releases)  
> 注入Frida脚本功能，将跨里程碑式的加强对话框取消的能力，任何Xposed的反制措施都是没用的，因为在禁用Xposed的情况下，Frida的注入功能仍然是有效的
# Frida 注入
云端仓库：https://github.com/orgs/Frida-Modules-Repo/repositories
> 可以上传自己的脚本  
# 用户配置仓库
https://github.com/Dialbox-User-Profile
# 反馈与交流
- [Discord](https://discord.gg/hDNx5mYGtA)      
- [酷安->一键提交反馈](https://www.coolapk.com/feed/writer?type=topic&tag=对话框取消)(点击->打开方式选择酷安)  
- [酷安->#对话框取消](https://www.coolapk.com/t/%E5%AF%B9%E8%AF%9D%E6%A1%86%E5%8F%96%E6%B6%88) 话题页面
