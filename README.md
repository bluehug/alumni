# 河南工学院校友网管理系统

## 项目来源
校友系统不只是一套软件系统，而是一整套“互联网+校友”的解决方案。校友系统通过帮助院校搭建校友互动平台和校友管理系统，拓展院校在校友服务方面的效率和范围，帮助院校提升校友工作信息化水平。
## 设计任务说明
按软件工程规范描述管理员端需求，细化用例规约，合理设计数据库，实现以下功能：
### 后台管理模块功能
1. 校友数据管理 
    1. 校友增删改 
    2. 校友快速搜索、高级搜索
    3. 校友分组的增删改 
    4. 为校友重置登陆密码 
    提供以下10项校友统计方式：毕业年份、教育阶段、年龄、性别、民族、籍贯、政治面貌、单位性质、行业、所在省份。
2. 校友活动管理 
    1. 发起活动 
    2. 修改、删除活动 
    3. 管理活动报名情况（增删） 
    4. 导出活动报名表 
    5. 审核校友发起的活动
3. 新闻、公告管理 
    1. 新闻分类管理（增删改、排序） 
    2. 新闻管理（增删改、查询） 
    3. 公告管理（增删改、查询）
4. 校友资料管理 
    1. 校友文档分类管理（增删改、排序） 
    2. 校友文档管理（增删改、查询） 
    3. 校友相册管理（增删改、排序） 
    4. 校友视频分类管理（增删查改、排序）  
    5. 所有资料均可设置查看权限 
    6. 所有类型资料均支持校友上传，后台审核 
### 前台模块功能 
1. 网站首页 
    1. 能够显示出最新网站通知公告、校友新闻和学校活动，双击每个新闻通告的标题，可看到新闻内容，点击“更多”则进入该类的标题列表项。 
    2. 显示 Flash，可切换图片新闻，点击进入新闻内容。 
    3. 显示友情链接、网站帮助版权、信息和校庆专栏。 
2. 校友新闻
    - 显示最新若干条校友新闻标题，点击后可进入详细内容，点击“更多”将显示该标题下的所有新闻列表。 
3. 校友风采 
    1. 显示知名校友的姓名、简介和照片，点击“详细介绍”可了解该校友的详细情况。 
    2. 校友相册：对于每个注册成功的校友，可显示其名称、创建和更新日期和相册简介等。对于相册个人登录的情形，可进行新建和修改操作；查看他人相册，也可以发表评论。 
4. 校友捐赠 
    - 校友捐赠：显示最新若干条捐赠情况记录，点击“更多”进入所有列表，最新的若干条捐赠项目显示出来。向下滚动显示最新捐赠的捐赠校友的姓名、金额、捐赠日期等，并显示部分捐赠图片。
5. 校友服务 
    - 学院简介及一些校内的相关部门链接。 
6. 用户注册和登陆 
    - 在某一页面左侧栏点击“登录校友网“即可进入登录页面，输入用户名、密码和验证码后点击“登录”，若信息正确则显示“登录成功”，同时异步更新页面的个人信息，显示个人头像、姓名、控制面板等信息；若看不清楚验证码，可点击验证码更换图片）。 
7. 调查问卷功能： 
    1. 投票：阅读并填写调查问卷，点击投票按钮将投票信息上传至后台。 
    2. 查看结果：查看所有参与本次问卷调查校友的投票数据统计结果。
8. 站内搜索功能
