# 电子书
- SUMMARY.md 电子书的目录文件即章节导航  （这些大写文件名的文件是具有特殊用途的文件）
- 超链接表示 { [显示内容](链接的地址) } 
  “ - ” 代表了无序列表
- 全局安装 npm i -g gitbook-cli  gitbook --version
    - gitbook build 构建电子书（build就是将md文件转化为HTML文件）
    - 执行gitbook init 初始化GitBook，会在当前目录下生成 README.md 和 SUMMARY.md文件。SUMMARY.md是GitBook的目录文件。README.md是电子书介绍文件，必须存在。也可以先手动创建SUMMARY.md，再执行gitbook init，如果SUMMARY.md中配置的文件夹和文件不存在，就会自动创建文件夹和文件，已经存在的文件夹和文件不会被覆盖。一般情况下是先在gitbook-demo目录下执行gitbook init，然后将要制作文档的md文件放到gitbook-demo里，接着再修改SUMMARY.md。