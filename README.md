# 拾光AI浏览器（Shiguang AI Browser）

公网下载与检查更新：[https://gmoon.online](https://gmoon.online)

本仓库存放 Windows 安装包与公开说明书。以下为产品说明书正文。

---

# 拾光AI超级浏览器说明书

![image1](media/image1.jpg)

# 拾光AI超级浏览器

拾光浏览器的安装器地址：[https://gmoon.online](https://gmoon.online)

之后不再使用全称 全文对象保持【拾光AI浏览器】

注册方式

从地址拉取安装器进行安装 安装完启动

![image2](media/image2.jpg)

登录方式

启动之后进行注册账号 注册完成返回登录 勾选记住密码 每29日强制登录一次

![image3](media/image3.jpg)

 

![image4](media/image4.jpg)

# 第一部分主界面介绍

# 进入主界面

先说主界面上20处标记

![image5](media/image5.jpg)

## 1窗口状态

最小化、最大化\适中

## 2 左侧栏收放

按钮 下面为收起状态

![image6](media/image6.jpg)

## 3url输入框

## 4 收藏按钮

点击收藏再次点击取消收藏、收藏的变成橘黄色取消默认无色

![image7](media/image7.jpg)

 

![image8](media/image8.jpg)

## 5 密码填充

按钮-需要在设置-密码 面板进行配置 当处于配置过密码的登录页时候 单击即可自动填充密码

![image9](media/image9.jpg)

## 6 客服中心

右侧抽屉收放按钮 同时有状态提示 掉线数 工单数 会话数 数量指未读未处理数

![image10](media/image10.jpg)

## 7 通知中心

点击收放通知中心右侧抽屉，图标上有消息状态，里面配置webhook和显示消息列表

![image11](media/image11.jpg)

## 8 添加新标签

## 9 开发者工具

收放按钮 点击展开，可切换devtools和响应区。Devtools是浏览器内核原生 响应区域是二开捕获可进行各种操作 涉及【请求重放、 定时请求、 监听转发请求、请求生成代码[python|node|go]、AI解析响应内容】

![image12](media/image12.jpg)

 

![image13](media/image13.jpg)

## 10标签

## 11空间

是浏览器的一些常规演示 有 起始页、收藏夹、下载中心、页面智析、网站权限、历史记录、数据中心、信息中心、设置、都是以右侧抽屉形式收放展示 区域可上下滚动 点击对应菜单可收放对应抽屉 抽屉同时只能展开一个 即自动切换

![image14](media/image14.jpg)

## 12智能工坊

这一块涉及自动化+AI 执行指令 、脚本执行、工作流程、计划任务、资料库

![image15](media/image15.jpg)

## 13 浏览环境控制区

## 14 新建浏览环境

新建的浏览环境分为 业务型 私密型、业务型可解智能工坊、私密型则不进行任何的对外开放 包括不能打开开发者工具

![image16](media/image16.jpg)

 

![image17](media/image17.jpg)

## 15切换浏览环境

从下拉框进型切换浏览环境。界面一次只能展示一个环境的全部页面 其它环境处于隐藏但活跃状态

![image18](media/image18.jpg)

## 16环境重命名

对当前的环境进行重新命名 内部环境管理依靠环境id不受名称影响 名称只是为了方便识别

## 17 环境管理

对已经创建的环境进行管理设计 打开 重命名、清空、删除 、加锁[需设密码] 出口节点配置 打开即切换浏览环境、清空是指其缓存清空、删除即删除profile 加锁为 当用户因为某种需求需要防止随意切换时候 为其配置密码 之后从别的环境切换过来时候就会需要提供解锁密码 否则无法切换浏览、出口节点 一般是企业配置 当企业需要指定ip对某个站点进行访问时候可以配置 企业节点配置在设置-企业节点配置

![image19](media/image19.jpg)

## 18 主题管理区域

## 19 主题切换

这个主题是系统配色

## 20 自定义主题

也就是浏览器背景 可以是某张图片也可以是某个图片链接

![image20](media/image20.jpg)

# 第二部分 工作空间介绍

![image21](media/image21.jpg)

 

![image22](media/image22.jpg)

## 11.1起始页

点击时候当前环境切换到起始页

## 11.2收藏夹

点击收放收藏夹抽屉，抽屉内操作，收藏当前页同收藏图标小星星编辑重命名 选择对应收藏分类修改分类名称，新建收藏夹即创建新的收藏类目 删除 删除指定收藏类目或页面 打开 打开指定收藏页面双击亦可 迁移 迁移收藏数据有也就是数据转移 当备份数据时候可用

![image23](media/image23.jpg)

## 11.3下载中心

顶部 打开文件夹按钮 下面分别是下载记录和回调规则面板 下方是文件筛选框 右侧是文件展示形式行和卡片 下方是 文件信息总览和文件列表，文件上面 查看文件信息展示信息为文件的来源和链路大小等详情信息不是文件具体内容，取消暂停指下载状态 删除指删除文件信息和物理路径 添加回调是指当文件下载完成事件触发后可以外接脚本直接对文件进行自动化操作 执行按钮即手动执行回调脚本，添加回调的文件都会形成一个回调规则 在回调规则面板可以对规则进行增删改查。

![image24](media/image24.jpg)

## 11.4 页面智解

对接AI模型对当前页面或指定页面的dom结构元素内容进行问答交互 不限于生成自动化操作dom页面的js函数

![image25](media/image25.jpg)

## 11.5网站权限

对页面的权限进行管理 有些页面需要麦克风权限 譬如七鱼等功能性页面，处理方式分为 运行 拒绝 每次询问 三种

![image26](media/image26.jpg)

## 11.6历史记录

全部的访问记录都会保存在这里 双击记录可以打开 并且是跟随之前的环境

![image27](media/image27.jpg)

## 11.7 数据中心

浏览器的基础信息 提供查看

![image28](media/image28.jpg)

## 11.8信息中心

所有在开发者工具-响应=监听 的 响应数据都会传到信息中心。同时信息中心的每条都可以进行 创作清洗脚本 清洗脚本是为了将数据处理之后回灌到客服中心进行显示和后续处理

![image29](media/image29.jpg)

## 11.9 设置面板

进行的各种设置 里面有很多指定设置的面板

常规，安全，下载，python，外观，AI，监听回调，保活规则，监听规则，密码管理，企业节点，扩展，插件，私域套件，锁屏，账号

![image30](media/image30.jpg)

![image31](media/image31.jpg)

# 第三部分

智能工坊介绍 分为5个板块 执行指令，脚本中心 工作流程 计划任务 资料库 这里面可自动化任务+AI相关

![image32](media/image32.jpg)

## 12.1执行指令

点击收放抽屉 抽屉内在指定页面执行js脚本 一般用于临时测试

![image33](media/image33.jpg)

## 12.2 脚本中心

![image34](media/image34.jpg)

![image35](media/image35.jpg)

## 12.3工作流程

![image36](media/image36.jpg)

![image37](media/image37.jpg)

![image38](media/image38.jpg)

![image39](media/image39.jpg)

## 12.4计划任务

![image40](media/image40.jpg)

## 12.5资料库

![image41](media/image41.jpg)

 

![image42](media/image42.jpg)

 

![image43](media/image43.jpg)

 

![image44](media/image44.jpg)

![image45](media/image45.jpg)

# 第四部分 设置区域各个菜单介绍

## 1常规

![image46](media/image46.jpg)

## 2 安全

![image47](media/image47.jpg)

## 3下载

![image48](media/image48.jpg)

## 4python

![image49](media/image49.jpg)

## 5外观

![image50](media/image50.jpg)

## 6AI

![image51](media/image51.jpg)

## 7监听回调

![image52](media/image52.jpg)

## 8保活规则

![image53](media/image53.jpg)

## 9监听规则

![image54](media/image54.jpg)

## 10密码管理

![image55](media/image55.jpg)

## 11企业节点

![image56](media/image56.jpg)

## 12扩展

![image57](media/image57.jpg)

## 13插件

![image58](media/image58.jpg)

## 14 私域套件

![image59](media/image59.jpg)

## 15 锁屏

![image60](media/image60.jpg)

## 16账号

![image61](media/image61.jpg)
