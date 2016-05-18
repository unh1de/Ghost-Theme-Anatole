# Anatole Ghost Theme

> Anatole 是由 [hi-caicai][1] 制作的一款 Farbox 主题，非常简洁漂亮，原地址在： https://github.com/hi-caicai/farbox-theme-Anatole
然后由 [YJK][2] 植到了 Ghost [地址] ([https://github.com/ygbhf/anatole-ghost-theme][3]) ,但是非完美移植，缺少点东西，我稍作修改了下

### 添加修改了
1.  Tag 添加
2.  代码高亮
3.  多说样式调整
4.  Archive 页面还原
5.  About 页面还原
6.  社交信息 页面还原
7.  其它细节
	 
### 说明
1. 由于Ghost限制问题，部分页面是使用 Ghost API 实现的，需要在 `ghost后台 -> 实验功能 -> 开放 API` 勾选此选项。
2. 关于页面，需要在Ghost后台添加一个独立页面，并设置url为 `about` 方可启用。
3. 归档页面，需要在Ghost后台添加一个独立页面，并设置url为 `archived`方可启用。
4. 如使用多说留言 请在 `ghost后台 -> 插入代码 -> 页脚` 加入下面代码，请添加自己的多说ID。
```
<script type="text/javascript">
     var duoshuoQuery = {short_name:"你的多说ID"};//替换为您的多说ID
     (function() {
        var ds = document.createElement('script');
        ds.type = 'text/javascript';ds.async = true;
        ds.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') + '//static.duoshuo.com/embed.js';
        ds.charset = 'UTF-8';
        (document.getElementsByTagName('head')[0]
         || document.getElementsByTagName('body')[0]).appendChild(ds);
     })();
</script>
```


### 效果
预览地址： http://jorb.me/

Mac下的预览：
![](http://cdn.jorb.me/image/5/83/40abc89fcd9fa6561ae75ca64e91e.png)


[1]:	https://github.com/hi-caicai
[2]:	https://github.com/ygbhf
[3]:	https://github.com/ygbhf/anatole-ghost-theme

[image-1]:	http://cdn.jorb.me/image/5/83/40abc89fcd9fa6561ae75ca64e91e.png

