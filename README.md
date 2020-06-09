hexo-theme-Yulia
================

Yulia 是一个简洁优雅的 hexo 主题。

本项目是在 hexo-theme-yulia 主题的基础上，进行了一些优化和改动。

Yulia 为 [hexo](https://github.com/tommy351/hexo) 2.4+制作的主题。

崇尚简约优雅，以及极致的性能。 你可以点击 [我的博客](http://bujige.net/) 查看效果。          

此主题在原有主题基础上进行了如下修改：

#### 1. 页面相关：

1. 添加网站访问量统计功能：访客人数统计、访问次数统计。
2. 添加文章页阅读统计功能：字数统计、阅读时长、访问次数。
3. 增加页面底部网站版权说明：成立年份，网站作者，备案号设置。
4. 增加文章页版权说明，可进行自定义版权协议、版权内容。
5. 删除首页 more 标签。
6. 添加页面点击小红心功能。
7. 添加页面加载进度条。
8. 增加图片鼠标悬停效果。
9. 增加百度自动推送功能。
10. 删除多说、网易云跟帖等失效评论系统。
11. 增加 Giteement 评论， Valine 评论。
12. 提升 Gitment、Giteement 评论访问速度。
13. 增加 Daovoice 在线沟通工具。
14. 增加手机端点击头像跳转主页功能。
15. 添加 GitHub Ribbons 和 GitHub Corners，可自定义位置。
16. 优化网站图标显示。
17. 增加网站关键字设置。

#### 2. 导航栏相关：

1. 优化左侧导航页面智能菜单样式显示。
2. 增加左侧导航页面社交图标显示。
3. 左侧导航页面智能菜单增加「分类」标签。
4. 左侧导航栏头像增加转动效果。

#### 3. 修复 BUG

1. 修复底部上下页符号显示问题。

2. 修复文章页微信二维码分享不显示图片问题。

3. 修复代码行数显示错乱问题。

   

---

如果想体验手机浏览效果，可以扫一下二维码：

![](http://qncdn.bujige.net/images/20200609204759.png)

---

**关于主题：**

1. 崇尚简约       
2. 追求移动端体验     
3. 希望把加载速度做到极致（努力中）    
4. 让大家把注意力放到内容上。这是本主题设计初衷      
5. 主题不支持IE6，7，8。以后也不会
              

## 一、外观

#### **常规**

![常规](https://cloud.githubusercontent.com/assets/2024949/19027861/92879edc-8967-11e6-8e60-7987b6507c8d.gif)

#### **手机**

![手机](https://cloud.githubusercontent.com/assets/2024949/19027020/1c5b756a-895f-11e6-99bf-ddff9687aee0.gif)   

#### **ipad横竖屏切换**

![ipad横竖屏切换](https://cloud.githubusercontent.com/assets/2024949/19026392/e74e1816-8957-11e6-8f08-eac9b3c8c036.gif)                    

## 二、开发者

为了性能和开发工程化考虑，Yulia 需要使用 webpack 进行构建生成。

如果您对主题有一些定制化的需求，请参考 wiki[《Yilia源码目录结构及构建须知》](https://github.com/litten/hexo-theme-yilia/wiki/Yilia%E6%BA%90%E7%A0%81%E7%9B%AE%E5%BD%95%E7%BB%93%E6%9E%84%E5%8F%8A%E6%9E%84%E5%BB%BA%E9%A1%BB%E7%9F%A5)

## 三、使用

#### 3.1 安装

使用终端命令，切换到 hexo 博客的根目录，然后执行下面的命令

``` bash
$ git clone https://github.com/bujige/hexo-theme-yulia.git themes/yulia
```

#### 3.2 配置

修改 hexo 根目录下的 `_config.yml` ： `theme: yulia`

#### 3.3 更新

``` bash
cd themes/yulia
git pull
```

## 四、配置

主题配置文件在主目录下的 `_config.yml`，请根据自己需要修改使用。

```
# Header

menu:
  主页: /
  归档: /archives

# SubNav
subnav:
  blog: "https://bujige.net"         # blog 
  github: "https://github.com/bujige"# GitHub
  weixin: "/img/wexin.png"          # 微信
  weibo: "#"                         # 微博
#  rss: "#"                           # rss
#  zhihu: "#"                         # 知乎
#  csdn: "#"                          # CSDN
#  cnblogs: "#"                       # 博客园
#  gitee: "#"                         # 码云
#  qq: "#"                            # QQ
#  jianshu: "#"                       # 简书
#  douban: "#"                        # 豆瓣
#  segmentfault: "#"                  # 思否
#  bilibili: "#"                      # 哔哩哔哩
#  acfun: "#"                         # AcFun
#  mail: "mailto:xxxxx@xx.com"        # mail
#  facebook: "#"                      # Facebook
#  google: "#"                        # Google
#  twitter: "#"                       # Twitter
#  linkedin: "#"                      # LinkedIn

rss: /atom.xml

# 是否需要修改 root 路径
# 如果您的网站存放在子目录中，例如 http://yoursite.com/blog，
# 请将您的 url 设为 http://yoursite.com/blog 并把 root 设为 /blog/。
root: /

# Content

# 文章卡片右下角常驻链接，不需要请设置为 false
show_all_link: '展开全文'
# 数学公式
mathjax: false
# 是否在新窗口打开链接
open_in_new: false

# 打赏
# 打赏 type 设定：0-关闭打赏; 1-文章对应的.md文件里有 reward:true 属性，才有打赏; 2-所有文章均有打赏.
reward_type: 2
# 打赏 wording
reward_wording: '谢谢你请我吃糖果'
# 支付宝收款二维码图片地址，跟你设置头像的方式一样。比如：/assets/img/alipay.jpg
alipay: 
# 微信收款二维码图片地址
weixin: 

# 目录
# 目录设定：0-不显示目录; 1-文章对应的.md文件里有 toc:true 属性，才有目录; 2-所有文章均显示目录
toc: 1
# 根据自己的习惯来设置，如果你的目录标题习惯有标号，置为 true 即可隐藏 hexo 重复的序号；否则置为 false
toc_hide_index: true
# 目录为空时的提示
toc_empty_wording: '目录，不存在的…'

# 是否有快速回到顶部的按钮
top: true

# Miscellaneous
baidu_analytics: ''
google_analytics: ''

# 网站图标 url
# 默认的 Yulia 图标放置在  xxx/themes/yulia/source/img/ 目录中. 
# xxx 为你的 hexo 博客目录。
favicon: 
  normal: /img/favicon-32x32-yulia.png
#  small: /img/favicon-16x16-yulia.png
#  medium: /img/favicon-32x32-yulia.png
#  apple_touch_icon: /img/apple-touch-icon-yulia.png
#  safari_pinned_tab: /images/logo-yulia.svg

# 你的头像 url
avatar: /img/avatar.png

# 网站关键字，用 "," 隔开，例如：blog,skill,life
keywords: ""

# 是否开启分享
share_jia: true

# 评论：1. 畅言云评; 2. Disqus; 3. Gitment; 4. Giteement; DaoVoice 在线沟通工具
# 不需要使用某项，直接设置值为 false，或注释掉。
# 具体请参考 wiki：https://github.com/litten/hexo-theme-yilia/wiki/

# 1. 畅言云评
changyan_appid: false
changyan_conf: false

# 2. Disqus 评论：在 hexo 根目录的 config 里也有 disqus_shortname 字段，优先使用 Yulia 的
disqus: false

# 3. Gitment 评论
gitment:
  enable: false            # 是否启用 Gitment 评论系统
  owner: ''                # 你的 GitHub ID
  repo: ''                 # 存储评论的 GitHub Repo
  oauth_client_id: ''      # client ID
  oauth_client_secret: ''  # client secret
  accelerate: true         # 是否使用自定义 js 提升访问速度（置为 true 则使用本地 js 加速，置为 false 则使用官网默认 js）

# 4. Giteement 评论
giteement:
  enable: false            # 是否启用码云评论系统
  owner: ''                # 你的码云账号英文名
  repo: ''                 # 存储评论的 码云 Repo
  oauth_client_id: ''      # client ID
  oauth_client_secret: ''  # client secret
  backcall_uri: ''         # 应用回调地址（请和配置的第三方应用保持一致）
  accelerate: true         # 是否使用自定义 js 提升访问速度（置为 true 则使用本地 js 加速，置为 false 则使用官网默认 js）
  
# 5. Valine https://valine.js.org
valine: 
  enable: false            # 是否启用 Valine 评论系统
  appid:                   # Leancloud 应用的 appId
  appkey:                  # Leancloud 应用的 appKey
  verify: false            # 验证码
  notify: false            # 评论回复提醒
  avatar: mm               # 评论列表头像样式：''/mm/identicon/monsterid/wavatar/retro/hide
  placeholder: Just go go  # 评论框占位符  
  
# 6. DaoVoice 在线沟通工具
daovoice:
  enable: false            # 是否启用 DaoVoice 在线沟通工具
  app_id: ''               # DaoVoice 上的 app_id



# 样式定制 - 一般不需要修改，除非有很强的定制欲望…
style:
  # 头像上面的背景颜色
  header: '#4d4d4d'
  # 右滑板块背景
  slider: 'linear-gradient(200deg,#a0cfe4,#e8c37e)'

# slider 的设置
slider:
  # 是否默认展开 tags 板块
  showTags: false

# 智能菜单
# 如不需要，将该对应项置为 false
# 比如
# smart_menu:
#   friends: false
smart_menu:
  innerArchive: '文章'
  category: '分类'
  friends: '友链'
  aboutme: '关于'
  

friends:
  友情链接1: https://bujige.net
  友情链接2: http://localhost:4000/
  友情链接3: http://localhost:4000/
  友情链接4: http://localhost:4000/
  友情链接5: http://localhost:4000/
  友情链接6: http://localhost:4000/

aboutme: 把我的全部，<br>奉献给我所热爱的一切。<br><br>谢谢大家 ~


# -———————— 以下为 Yulia 添加的自定义功能 —————————


# 开启百度站长平台自动推送，有利于 SEO 搜索（https://ziyuan.baidu.com/linksubmit/index）
baidu_push_auto: false
  
# 文章版权说明：默认开启，关闭将 enable 设置为 false。
post_copyright:
  enable: true
  # 版权协议名称
  license: CC BY-NC-SA 3.0
  # 版权协议地址
  license_url: https://creativecommons.org/licenses/by-nc-sa/3.0/
  
# 网站访问量统计：访客人数统计、访问次数统计。
site_count:
  # enable 设置为 false 时不显示网站访问统计。
  enable: false
  # 网站访客人数统计设置
  site_uv: true
  site_uv_header: <i class="icon-user icon"></i> 本站访客数
  site_uv_footer: 人
  # 网站访问次数统计设置
  site_pv: true
  site_pv_header: <i class="icon-eye icon"></i> 本站总访问量
  site_pv_footer: 次
  
# 文章页阅读统计：字数统计、阅读时长、访问次数
page_read_count:
  # enable 置为 false 不显示阅读相关统计。
  enable: false
  # 文章字数统计
  word_count: true
  word_count_header: <i class="icon-statistics icon"></i> 字数统计：
  word_count_footer: 字
  # 文章最低阅读时间
  read_time: true
  read_time_header: <i class="icon-book icon"></i> 阅读时长 ≈
  read_time_footer: 分
  # 文章页访问次数统计设置
  page_pv: true
  page_pv_header: <i class="icon-eye icon"></i> 阅读数：
  page_pv_footer: 次

# 页面点击小红心
clickLove:
  # 关闭请设置为 false
  enable: true
  
# 悬停预览图片效果
hover_effect:
  # 'global' 0: 分开设置; 1: 全局启用, 2: 全局关闭
  global: 1
  # subNav - 导航栏悬停预览图片效果
  subNav: true
  
# 页面加载进度条 | progressBar
# Demo: http://github.hubspot.com/pace/docs/welcome/
# type: barber-shop|big-counter|bounce|center-atom|center-circle|
#       center-radar|center-simple|corner-indicator|flash|flat-top|
#       loading-bar|mac-osx|minimal
# color: black|blue|green|orange|pink|purple|red|silver|white|yellow|
progressBar:
  enable: false
  type: 'minimal'  # Keep Quotes | 注意保留引号
  color: blue
  
# Github Fork View:
# type-显示类型; position-显示位置; repo-你的 GitHub 仓库地址
# type: ribbon | corner
# positon: left-top | left-bottom | right-top | right-bottom
github_fork:
  enable: false
  type: 'corner'                      # 显示类型，默认为 ribbon 类型
  position: 'right-top'               # 显示位置，默认为 右上角
  repo: 'https://github.com/bujige/'  # 你的 GitHub 仓库地址
  
# 底部
footer:
# 网站成立年份,置为 false 则默认显示今年（显示格式为：© 2018-2020）
  since: 2018
# 网站版权信息说明，置为 false 则默认显示作者或网站标题
  copyright: false
# 网站备案号，置为 false 则不显示（显示格式为：© XXXICP备XXXX号）
  icp: XXXICP备XXXX号
```


