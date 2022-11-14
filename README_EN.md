![GitHub all releases](https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.mhook.dialog.new/total?color=1&style=plastic) 
![GitHub release (latest by date)](https://img.shields.io/github/v/release/Xposed-Modules-Repo/com.mhook.dialog.new?style=plastic)
![GitHub issues](https://img.shields.io/github/issues-raw/Xposed-Modules-Repo/com.mhook.dialog.new?style=plastic)
![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/Xposed-Modules-Repo/com.mhook.dialog.new?style=plastic)  
[中文](https://github.com/Xposed-Modules-Repo/com.mhook.dialog.new/blob/main/README.md)  
# Introduction
Due to the update of many features, but also placed in the [fix version](https://github.com/Xposed-Modules-Repo/com.mhook.dialog.fix) is not quite appropriate, so another branch was built, the main new core functionality is: Frida injection, welcome to try.  
In addition, because there is no server, the dialog box to cancel the new version of the built-in updates is a direct access to github, Frida script repository and download configuration environment is also in github.com  
There is also feedback can be directly in Cool On -> Topics -> # Dialog Cancellation under the release of feedback and suggestions, if there is a github account, you can submit feedback directly under the current issues (Dialog Cancellation -> About -> One Click Feedback (Cool On))  
# Function
This module can cancel some dialogs that are forced to be set as uncancelable, such as some forced update dialogs, and some ads (some rogue ads always make the x small).

## Extended Functions
1. Cancel button disabled(enabled)  
2. disable exit(exit+finish)(can be combined with key control)  
3. Disable popup box by keyword (hover window + dialog box) (can be combined with key control)  
4. Version customization (version number + version name)  
5. Disguise the system time (system time + GPS time + local access to the server time)  
6. Anti-detection of this module, Xposed, Root  
7. Disable network at startup (can set the disable time)  
8. Force to end the current activity (Activity) (control by key combination)  
9. Anti-disable Xposed (simple disable)  
## Cautions
1. This module does not support the latest dialogs and game dialogs! (Some latest dialogs are very similar to normal dialogs, please pay attention to distinguish them!)  

# Update Preview
//todo
# Change log
ref: [Release](https://github.com/Xposed-Modules-Repo/com.mhook.dialog.new/releases)  
> Injecting Frida scripting functionality will enhance dialog cancellation across milestones, and any Xposed countermeasures will be useless, as Frida's injection will still work with Xposed disabled
# Frida inject
Cloud Warehouse: https://github.com/orgs/Frida-Modules-Repo/repositories
> You can upload your own scripts  
# Feedback and Communication
- [Discord](https://discord.gg/hDNx5mYGtA)      
- [酷安->一键提交反馈](https://www.coolapk.com/feed/writer?type=topic&tag=对话框取消)(点击->打开方式选择酷安)  
- [酷安->#对话框取消](https://www.coolapk.com/t/%E5%AF%B9%E8%AF%9D%E6%A1%86%E5%8F%96%E6%B6%88) 话题页面
