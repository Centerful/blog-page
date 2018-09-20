# Html -> Vue 组件化
- Body(背景色,左侧图标,右侧用户中心toolbar,尾部网站声明)
- layout
    - layout-head
    - layout-body
        - wrapper(对该组件进行路由.专栏,文章列表,文章内容,talk,个人中心页面都是对wrapper进行路由.)
- mutil-bar

### 通用
- layout-head,两种形态(fixed与relative).
- footer-loading,尾部加载
- 表单组件:输入框,多行输入框,图片选择,纸片,单选框,按钮,侧边按钮,水印按钮
- split-line,区域分割线(title + line)
- 头像
- 标签
- flag-circle

### 专栏
- .wrapper.columns
- columns-showcase,展示页面(开始写文章,开通专栏)
- column-card,专栏展示卡
- column-form,专栏开通表单
- column-card-large,大型专栏展示卡

### 文章
- .wrapper.blog
- .wrapper.blog-content
- blogs,文章展示列表
    - blog-card,文章卡
- blog-content,文章内容
    - blog-meta,文章展示(img,gif,video)
    - auth-card,作者信息
    - blog-md,博客MD内容
    - blog-column,收录专栏
    - recommendations,推荐阅读区
- blog-comments,查看文章回复
    + comment-talk,查看对话
    + comment-title,标题
    + comment-item,一条对话
    + comment-input,回复

### 编辑
- .wrapper.edit(no header)
- edit-sidebar,侧边栏
    + sidebar-head
    + sidebar-blogs,管理文章与文集
    + sidebar-footer
- edit-meta,题图
- edit-title
- edit-md

### Talk
- .wrapper.talk
- talk-send,发表心情
- talk-card,talk-card-private,talk-card-encrypt(公开,仅自己可见,加密)
    + talk-meta,文字内容下方的图片或视频区.
    + talk-input,回复栏
    + talk-replies,回复区
    + talk-replie,某条回复

### 个人主页
- .wrapper.auth
    + full-img
- auth-container
    + auth-info
    + auth-meta

### Login(背景)
- login-card,登录卡(no layout,状态与动效较多)

### 插件
- gooey menu
- fancy box
- font-awesome
- wave



# Css 样式

### 文字

### 配色

### 卡片阴影