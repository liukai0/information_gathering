# IFG(信息收集系统)
目前实现的功能为根据标签(项目中IndexAndType枚举)去网站(目前仅实现了推酷)爬取感兴趣的文章并存储到es。使用es_head查看，感兴趣则通过url跳转到网站查看。
待开发:添加更多的源页面。做一个前台展示页面，不需要再通过url去源站看。同时可以将优秀的文章保存到数据库。

项目启动:替换ifg.properties中的数据源地址和es的地址。(目前没有使用到数据源，可以直接注释掉dataSource这个bean，只提供es的地址)
