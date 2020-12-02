# Fuck闽政通

由于福建省强制推行闽政通APP用于福建省内的健康码验证，不认支付宝等全国健康码，且闽政通APP用户体验极差，于是开发本APP用于快速生成八闽健康码。

闽政通问题:

1. APP臃肿,启动速度慢,索求大量权限
2. 经常掉登录(登录过期)，导致很多时候需要健康码时，需要重新登录而浪费时间，导致人群拥堵
3. 强制推广安装闽政通，不认全国健康码


## Web版

> https://shirosakimieru.github.io/FuckMinZhengTong/app/src/main/assets/mzt.html?name=YOUR_NAME&idcard=YOUR_ID

请直接替换 ``YOUR_NAME`` 和 ``YOUR_ID`` 为姓名和身份证号即可

## 使用方法

本APP不需要特殊权限，所有数据均存放在本地应用目录。

测试版本：Android 10 (低版本未测试)
最低支持版本：Android 5.0 (API 21)

1. 安装此APP。
2. 点击打开，设置姓名和身份证。
3. 点击生成健康码
    * 如需重新设置个人信息，请点击 主页 的 [设置] 或 健康码页面 右上方 [菜单]。
    * 此健康码不支持扫描

![demo](./img1.gif)


## 更新记录

> ### v1.4.0 2020-12-02
> 1. 重构 程序主页
> 2. 移除 旧版设置页面，使用Android原生的偏好库
> 3. 增加 部分文本国际化支持(English)
> 4. 增加 其他设置项
> 5. 修正 健康码界面 ToolBar 使用原生返回按键
> ### v1.3.0 2020-11-25
> 1. 更新 健康码样式 (就个破健康码页面为啥天天换首页style。。)
> 2. 修复 首页小眼睛点击后图标消失的问题
> 3. 更新 gradle依赖
> 4. 移除 不需要的资源文件
> ### v1.2.0 2020-10-21
> 1. 移除 无用的资源文件，优化加载速度
> ### v1.1.0 2020-10-21
> 1. 修复 页面显示错误的问题
> 2. 移除 网络权限，所有资源全部存放本地，可离线使用
> 3. 更新 健康码页面
> 4. 优化 健康码页面返回体验
> ### v1.0.0 2020-10-19
> 1. release
