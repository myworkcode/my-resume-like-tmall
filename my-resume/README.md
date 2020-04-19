# 电子商务版的简历模板（纯手写，无框架）
###原生JS+HTML+CSS，没有用任何框架
###兼容到IE56789，全兼容，优雅降低方案

预览的地址：[http://taobao.fm/works/my-resume-like-tmall/index.html](http://taobao.fm/works/my-resume-like-tmall/index.html)

预览：
![](http://i.imgur.com/FnpYxFw.png)

PSD设计稿在：[http://pan.baidu.com/s/1ntPl6Fv](http://pan.baidu.com/s/1ntPl6Fv)；修改文件方式可以在 PSCC 里面，先要设置，首选项>增效工具>启动生成器；并且在文件>生成>图像资源前打钩；在 PSD 所在的文件夹下会自动生成修改后的文件；可以直接修改； 这个仓库里也有单独模块的PSD文件，也可以在那里改

测试环境

- chrome
- IETeser中的678910
- win系统自带的IE57891011；

现在的作品品展示页等都是给写死的，打算等功能加的差不多后，再重构下；作品页，技能总结都做成json格式，直接用过拼接字符串的形式显示；高度自适应；

#写这个简历踩到的坑
因为用原生JS写的，并且JS,CSS都兼容到IE56789，所以才到的坑还是很多的；[点此查看](https://github.com/Broszhu/my-resume-like-tmall/blob/master/%E5%BC%80%E5%8F%91%E6%AD%A4%E9%A1%B9%E7%9B%AE%E8%B8%A9%E7%9A%84%E5%9D%91.md)；

#下次打算加的功能
- 图片延迟加载（按需加载）；
- 图片显示方式，动态跳跃显示，类似忍者先快后慢入，先慢后快出；
- 以模块化开发的方式写；
- 重构JS代码逻辑

