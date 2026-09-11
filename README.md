# 法院短信转发器

自动识别并转发法院相关短信（如 12368 送达）到邮箱的 Android 应用。

包名：`cn.senrylee.courtsms`

## 下载（请装这个）

**v1.0.2 调试包（送达笺界面重设计）：**

https://github.com/SenryLee/SmsForwarder/releases/download/courtsms-v1.0.2/CourtSms_1.0.2.260911_100102_universal_debug.apk

发布页：https://github.com/SenryLee/SmsForwarder/releases/tag/courtsms-v1.0.2

> 请先卸载旧版再安装。

## 本版更新

- 界面全面重设计：宣纸底色、印泥柔红、衬线标题字体
- 日志 / 规则页自定义页眉，去掉杂乱系统标题栏
- 设置页改为简洁单栏（邮箱、授权码、转发开关、恢复预置规则）
- 保留 v1.0.1 稳定性修复与法院预置规则

## 怎么用

1. 安装 APK，授予短信 / 通知权限
2. 打开设置，填写邮箱与 SMTP 授权码
3. 保存后规则自动绑定该邮箱
4. 在「转发日志」核对结果

## 源码

完整代码当前在开发分支 / PR：

https://github.com/SenryLee/SmsForwarder/pull/2

分支：`cursor/court-sms-app-a186`

> 说明：当前自动化账号对 `CourtSmsForwarder` 仓库没有 git push 权限（仅能改 README）。
> 请你在 GitHub 把该仓库的 Write 权限授给 Cursor bot，或本地执行：
>
> ```bash
> git clone https://github.com/SenryLee/SmsForwarder.git
> cd SmsForwarder && git checkout cursor/court-sms-app-a186
> git remote add court https://github.com/SenryLee/CourtSmsForwarder.git
> git push court cursor/court-sms-app-a186:main --force
> ```
