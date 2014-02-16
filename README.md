LICHEN's BLOG
------------------------------------------

### 目录结构
  root
   | - articles.yml #文章配置
   | - ext.yml      #用户自定义扩展配置
   | - navbar.yml   #导航菜单配置
   | - pages.yml    #独立页面配置
   | - site.yml     #站点主配置
   | - index.html   #首页（自动生成）
   | - rss.xml      #RSS订阅源（自动生成）
   | - tag.html     #标签索引页（自动生成）
   | - articles #放置文章的目录
        |- post1.md    #post1元文本
        |- post1.html  #post1文章页面（自动生成）
        |- post2.md    #post2元文本
        |- post2.html  #post2文章页面（自动生成）
   | - pages #放置独立页面的目录
        |- page1.md    #page1元文本
        |- page1.html  #page1独立页面（自动生成）
   | - assets #资源目录
        |- vendor  #第三方资源
        |- themes  #主题
            |- default #默认主题
   | - templates #模板目录
