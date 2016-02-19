<!--Meta
category:项目文档
title:深度商店开发记录
DO NOT Delete Meta Above-->


开发完成度记录
==============

数据相关
--------

### 信息变更通知

#### 应用信息 :@夏彬:

-   版本号
-   商店数据

#### 排行榜如何更新? :@新楷:@夏彬:@补充:

#### 下载量、评分数更新如何通知 :@新楷:@补充:

#### 应用上下架 :@新楷:@全超:@补充:

### deb生成

#### 应用测试源的处理 :@补充:

#### 应用软件deb的生成 :@龙宇:

#### 应用软件deb的测试 :@陈科云:

#### apk/webapp

##### deb生成

##### deb结构调整成适当的布局

### 翻译

#### 国际化

##### 登陆界面似乎没有根据主页面的locale的切换而切换 :@夏彬:@确认:

##### 整理各页面出现的ID并替换为英文 :@文杰:@补充:

##### 整理哪些地方需要做国际化 :@王珈:@补充:

-   详情页面: 应用名称、描述、截图
-   客户端以及网页项目本身所有显示的文字

#### 本地化

##### 项目的transifex配置 :@新楷:@夏彬:

##### 非固定po方式的数据整合 :@夏彬:@补充:

###### CMS中直接编辑

###### 分类信息

##### 文案信息没有使用中文 :@夏彬:@补充:

### 评分数据真实化 :@夏彬:@补充:

### 下载数据真实化 :@夏彬:@补充:

### [\#A] 调整缓存机制，使资源可以在短时间内过期 + 压缩请求数（需要服务端合并请求结果） :@新楷:

工具相关
--------

### 批量导入数据

#### 确定数据格式 :@夏彬:@补充:

### 压力测试工具 :@陈科云:

-   智能仓库压力测试
-   网站压力测试

CMS
---

### CMS界面

#### 位置信息、链接ID等宽度过长 :@全超:

#### 补充需要明显调整的地方(是否改进再讨论) :@王珈:@补充:

### bucket API无法正常使用 :@全超:@李鹤:@确认:

### /metadatas?query=q 搜索功能 :@夏彬:

### metadatas新增接口 :@夏彬:@补充:

### 新创建时候提供默认数据 :@全超:

### 数据用例图绘制 :@夏彬:@补充:

### 镜像管理 :@夏彬:@补充:

### 编辑下载量

#### 提供接口走正常流程刷数据 :@夏彬:

### 下架功能(测试) :@陈科云:

### 发布按钮功能无法使用 :@全超:

评论API
-------

### 接口确定?

### API返回结构调整 (可能需要重写) :@全超:

### 是否移动CMS

测试
----

### 深度商店页面测试用例完善

### 保证appstore.deepin.test和cms.deepin.test已有功能正常 :@陈科云:

#### 考虑是否可以部分自动测试

登陆窗口
--------

### [\#A] 登录窗口的遮罩效果 :@文杰:

### 登陆窗口出现后，页面后方行为不一致(有部分事件被遮盖) :@李鹤:@文杰:@确认:

### 登陆界面无法点击“记住密码" :@李鹤:@确认:

### "注册"|"忘记密码" 不要下划线效果 :@李鹤:

### Mac下出现了滚动条 :@舒乐:@文杰:@确认:

### 测试效果(功能已完成) :@陈科云:

### 目前的右上角如何处理 :@夏彬:@文杰:@王珈:@舒乐:@补充:

### 相关设计图补充 :@舒乐:@文杰:

页面&客户端
-----------

### 首页

#### 确认首页slide点击行为 :@王珈:@确认:

### 搜索

#### 搜索补全列表样式细节调整 :@界面:@文杰:

#### 页面搜索框与主内容间的细节调整 :@文杰:

##### 增加padding

#### 搜索行为

##### 容回车后，下拉菜单没有消失 :@文杰:

##### 页面切换后，搜索框内容不消失 :@王珈:@确认:

#### [\#A] 搜索页面 细节 :@文杰:

##### 搜索栏到主内容间的搜索提示细节 :@舒乐:@补充:

### 专题

#### 背景图与背景主体渐变 :@文杰:

#### 背景图位置调整 :@文杰:

-专题页面背景图只显示了一部分图片

### 详细页

#### "相关应用"按钮的布局 :@文杰:

#### 详细页面没有任何评论时，不显示"所有版本" :@文杰:

#### 截图位置尽量处于居中状态 :@文杰:

-   页面宽度宽时，目前截图没有居中.

#### 截图点击后位置改变 :@舒乐:@确认:@补充:

##### 讨论是否目前做这个功能

#### 截图下方的"相关应用"、"评论"的细节

##### 没有切换效果 :@文杰:

##### 按钮本身文字没有居中 :@文杰:

#### 截图区域图片外加阴影 :@舒乐:@确认:

#### 评论功能

##### [\#A] 评论分页功能 :@文杰:

##### [\#A] 评论失败处理和样式 :@文杰:

###### 补全相关设计图 :@舒乐:@补充:

##### [\#A] 评论字数限制？ :@文杰:

###### 明确需求 :@王珈:@补充:

#### 安装按钮状态切换

##### 安装状态检测 :@新楷:@夏彬:@补充:

##### 功能实现 :@新楷:

-   可先模拟

##### 界面实现 :@文杰:

##### 不支持当前架构时的提示 :@夏彬:@补充:@王珈:@舒乐:

#### 文案布局细节

##### 描述收起 :@文杰:

##### 对齐 :@文杰:

#### 最后更新时间

##### API提供此字段 :@夏彬:

##### 计算真实数据 :@夏彬:

#### 截图无法显示

##### 查找原因,图挂了 :@新楷:

##### 如何避免 :@新楷:@全超:

#### 评分功能

##### 历史评论接口需要只返回特定应用的数据 :@全超:

##### 评论发出后需要即使更新 :@全超:@确认:

###### 若无法做到，给出原因，统一态度

#### 截图区域的预加载图 :@文杰:

#### [\#A] 应用页面时高亮对应的分类(需求商讨中) :@补充:@王珈:

### 应用商品展示窗口

#### 首页、下载排行中的应用下方的短描述是否应该有　 :@陈祥帮:@确认:@王珈:

#### 应用封面处于hover状态时，底下圆角细节不对 :@文杰:

#### 文字与图标的布局调整 :@文杰:

### 侧边栏导航

#### 字体设置 :@确认:@舒乐:

#### 文字间距不对 :@补充:@舒乐:

#### 图标和文字没有对齐 :@文杰:

#### 激活状态文字颜色未响应 :@文杰:

### 下载排行榜页面 :@文杰:

-   编号
-   角标

### 其他

#### 小分辨率时候界面布局的处理 :@文杰:@确认:@舒乐:

-   支持到什么程度,　最大最小

#### tooltip提示功能 :@新楷:@文杰:

#### 统一右的键菜单(确定要做什么) :@新楷:@王珈:

#### 各种出错页面样式 :@文杰:

-   网络错误 无网络
-   页面未找到 404
-   内部错误 500

##### 网络检测功能

#### 预载入效果 :@文杰:

##### 整页加载 :@文杰:

##### DONE 商品展示框

##### 应用截图 :@文杰:

#### 返回按钮的显示隐藏（QtWebkit bug：不能记录历史，需要自己实现） :@新楷:

#### 导航Title信息缺失 :@文杰:@确认:@补充:@王珈:

#### 评论的星星目前都是半颗星星且图片不对 :@文杰:

#### 评分评论下载量的布局不对 :@文杰:

#### 更新设计图时的通知 :@补充:@王珈:@舒乐:

-   保证方便的前提下，做到通知到相关人员

### 主菜单功能

#### DONE 登陆

#### DONE 注销

#### 关于

##### 补全界面设计图 :@补充:@舒乐:

#### 帮助

##### 帮助手册内容 :@补充:@王珈:

#### 展示在哪里 :@补充:@王珈:@舒乐:

### 安装应用

#### 界面框架的实现 :@新楷:@补充:

#### 界面细节 :@文杰:

#### 功能

##### 下载

###### 提供lastore需要的信息 :@新楷:

-   应用包名
-   来源地区
-   deepinid
-   镜像源(lastore处理)
-   架构(lastore

##### 安装

##### 接口API :@新楷:@夏彬:@补充:

##### 接口实现 :@夏彬:

#### 中途退出

##### 如何交互 :@补充:@王珈:

#### [\#A] 下载进度窗口

##### 数据接口 :@新楷:@夏彬:@补充:

###### 确定接口API

##### 界面 :@文杰:

### 卸载应用

#### 接口API :@夏彬:

#### 接口实现 :@夏彬:

#### 界面实现 :@夏彬:@补充:

### 更新

#### 更新数据格式 :@夏彬:@补充:

#### 应用更新 :@夏彬:@补充:

#### 系统更新 :@夏彬:@补充:

进度会议
========

DONE 第32周任务安排
-------------------

CLOSED: [2015-08-03 Mon 12:33] SCHEDULED: \<2015-08-03 Mon\>

1.  完成所有android和web应用的deb生成。
    预先完成deb生成，细节调整，优化之后进行。
2.  所有精品应用的deb测试由陈科云负责，同时此支线任务的进度由陈科云负责。黄志然、龙宇、王珈、马福鸿等人配合。
3.  客户端支持安装删除软件。 陈新楷负责。夏彬配合完成
4.  商店页面实现。 陈新楷负责安排范文杰的任务，王珈验收协调
