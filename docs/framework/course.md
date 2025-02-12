# 视频教程

## 创建机器人


### 服务器篇

#### 资源

- [腾讯云](https://cloud.tencent.com/act)
- [阿里云](https://www.aliyun.com/activity)

#### 视频

[《梦幻教程》如何创建机器人？ 服务器篇](https://www.bilibili.com/video/BV1bY4y1x7w3?p=1)

#### 步骤

1. 创建梦幻机器人需要什么条件？

需要一台PC电脑，需要一款机器人PC软件（梦幻框架+梦幻应用）

2. 假如我没有电脑怎么办？

你可以通过腾讯云、阿里云、或其他云平台购买云服务器，通过云服务器来登录机器人软件

3. 怎么通过手机连接我购买的服务器？

手机下载安装 [ Microsoft远程桌面 ] App，通过远程桌面App来连接登录购买的云服务器


### 通用篇

#### 资源

- [梦幻框架](https://open.drea.cc/51)
- [梦幻应用](https://open.drea.cc/6)

#### 视频

[《梦幻教程》如何创建机器人？ 通用篇](https://www.bilibili.com/video/BV1bY4y1x7w3?p=2)

#### 步骤

1. 下载梦幻框架

<!--

2. 下载语音组件（仅用于QQ平台，没有语音需求时也可以不安装）

-->

2. 下载梦幻应用

3. 整合框架和应用

4. 启动梦幻框架

5. 更新梦幻框架（第一次安装无需此步骤，后面更新框架时需要，一定要仔细看）

<!--

### QQ篇

#### 资源

- [官网](https://im.qq.com/)

#### 视频

[《梦幻教程》如何创建机器人？ QQ篇](https://www.bilibili.com/video/BV1bY4y1x7w3?p=3)

#### 步骤

1. 安装梦幻框架和应用，请查看 > [《梦幻教程》如何创建机器人？ 通用篇](#通用篇)

2. 下载QQ客户端

3. 注册并登录QQ小号，记住账号和密码

4. QQ小号加入到测试群

5. 在梦幻框架上登录QQ小号

6. 当显示在线状态时，进入测试群，发送“菜单”

7. 最后，请务必查看 > [问题答疑](../app/qa.md)

#### 答疑

***启动时卡住不动怎么办？***

框架启动时由于网络原因有时会比较慢，请耐心等待一会，若启动后卡住不动，可尝试在控制台内按回车键，或关闭程序等一会再次启动，重复几次，定可解决问题！

***密码登录和二维码登录选哪个？***

首次登录时，推荐使用二维码登录，否则会有验证码，需要自行抓包！

首次登录成功后，后续可使用密码登录，一般情况下就不需要验证码了！

***二维码登录遇到环境异常问题怎么办？***

遇到这种问题，大多是由于机器人QQ号是新号或QQ登录地变更导致。

1. 可以开启QQ设备锁，切换登录协议为`Android Phone`，登录时采用手机验证码登录！

2. 可以用在自己常用的网络内挂机器人，例如自家电脑，登录成功后，将整个框架打包，上传到无法登录的电脑上！

3. 可以尝试在目标电脑上安装官方QQ客户端登录机器人QQ，等挂一段时间稳定下来后，再次尝试登录框架进行扫码！如果还不行，就在QQ客户端上继续挂着，直到可以为止！

***密码登录时有验证码，如何抓包？***

1. 复制控制台中生成验证码链接

2. 打开浏览器，访问刚才的验证码链接

3. 按F12进入开发者模式，点开Network页签

4. 拖动页面中的验证码，完成校验

5. 观察Network页签，会发现检测到了一条请求

6. 点开请求，打开Response页签，会看到刚才生成的Ticket

7. 复制Ticket到控制台中，按回车即可

8. 如果看不懂，请使用二维码登录

***还是不会抓包怎么办？***

登录时，先选择二维码登录，后续再使用密码登录！

-->

### Q频篇

#### 资源

- [官网](https://im.qq.com/index)
- [QQ开放平台文档](https://bot.q.qq.com/wiki)
- [QQ开放平台后台](https://q.qq.com)
- [梦幻机器人-自测报告](https://open.drea.cc/101)

#### 视频

[《梦幻教程》如何创建机器人？ Q频篇](https://www.bilibili.com/video/BV1bY4y1x7w3?p=4)

#### 步骤

请严格按照视频教程配置，漏一步都不行！不好好看教程导致出问题，然后去群里反馈的，直接拉黑处理！

1. 安装梦幻框架和应用，请查看 > [《梦幻教程》如何创建机器人？ 通用篇](#通用篇)

2. 下载QQ客户端，登录QQ，开启QQ频道功能，创建测试群，创建文字频道

3. 进入QQ开放平台后台，注册开发者账号，审核通过后，登录开发者账号

4. 创建机器人，沙箱频道选择刚创建的测试群，机器人类型尽量选择私域

5. 创建成功后，进入测试群，将机器人添加到群内

6. 进入机器人详情

7. 点击开发 -> 开发配置，可以查看机器人ID和机器人令牌，记下来；将页面拉到下方，进行URL配置，新增URL配置项：open.drea.cc/i

8. 点击开发 -> 发布配置 -> 功能配置，配置菜单、签到、查询这3个功能指令即可！

9. 在梦幻框架上登录机器人账号

10. 当显示在线状态时，进入测试群，发送“菜单”，若没有任何问题，即可进行上线

11. 下载梦幻机器人-自测报告，自测报告内的Bot ID、主体名称修改成你自己的，功能点大家可以稍微修改下，尽量避免和其他机器人重复即可

12. 点击开发 -> 发布配置 -> 自测报告，上传刚修改好的自测报告，然后提交审核，等待审核

13. 审核通过后，点击频道管理，选择要灰度的频道（即你要机器人加入的群），点击灰度

14. 灰度成功后，进入刚灰度的群，将机器人添加到群内

15. 添加完毕后，群内发送“菜单”即可查看效果

16. 最后，请务必查看 > [问题答疑](../app/qa.md)


### DoDo篇

#### 资源

- [官网](https://www.imdodo.com)
- [DoDo开放平台文档](https://open.imdodo.com)
- [DoDo开放平台后台](https://doker.imdodo.com)

#### 视频

[《梦幻教程》如何创建机器人？ DoDo篇](https://www.bilibili.com/video/BV1bY4y1x7w3?p=5)

#### 步骤

1. 安装梦幻框架和应用，请查看 > [《梦幻教程》如何创建机器人？ 通用篇](#通用篇)

2. 进入DoDo官网，通过手机号注册DoDo账号，登录DoDo

3. 创建测试群和文字频道

4. 进入DoDo开放平台后台，通过手机号登录后台

5. 开发者类型选择个人开发者，填写申请理由，提交，等待审核

6. 审核通过后，重新登录开放平台后台，进入机器人列表页

7. 创建机器人，使用方式选择开发机器人

8. 进入机器人详情

9. 点击授权管理，可以看到clientId和Token，记下来；需要权限处，勾选超级管理员并保存

10. 复制机器人的邀请链接，访问邀请链接，将机器人邀请到刚创建的测试群

11. 在梦幻框架上登录机器人账号

12. 当显示在线状态时，进入测试群，发送“菜单”

13. 最后，请务必查看 > [问题答疑](../app/qa.md)


## 开发机器人

#### 资源

- [方法文档](./method.md)
- [易语言IDE](https://open.drea.cc/102)
- [梦幻框架SDK](https://open.drea.cc/56)

#### 视频

[《梦幻教程》如何开发机器人应用？ ](https://www.bilibili.com/video/BV1bY4y1x7w3?p=6)

#### 步骤

1. 梦幻框架内部已做多平台适配，事件和方法已做抽象化处理，您只需要在某个平台上开发一次应用，即可运行在多个平台上，没有任何后顾之忧！

2. 官方只推出了易语言SDK，对于使用其他语言的开发者们，可以按照方法文档进行开发！

3. 下载安装易语言IDE

4. 下载梦幻框架SDK

5. 将e后缀结尾的文件设置为用易语言打开

6. 打开demo项目，修改项目信息（应用ID等），查看demo示例代码，了解项目结构

7. 点击静态编译，文件名修改为你刚设置的应用ID，编译生成dll后缀的应用文件

8. 将刚编译好的dll文件拖拽置梦幻框架应用区即可

9. 机器人所在群内发送“示例功能”即可看到效果
