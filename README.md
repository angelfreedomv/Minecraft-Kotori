## Minecraft-Kotori Ghost Theme 1.0.1 release

#### Install  
1. please modify `/post.hbs`   `disqus_shortname = ''` content for your disqus ID  
2. modify `partials/header.hbs` `partials/menu2.hbs` `partials/footer.hbs` links to yours.  
3. delete few javascript file and no adaptive menu.
4. remove CDN links in deafult.md.
5. improve page response speed.
6. a lot of places is already modify.

#### Bug
logo image no suitable

#### Thanks helper
thanks to [JclMiku](https://github.com/JclMiku)

#### reference
Change Social Link 
  Replace #0 to your social link (in header.hbs) 
```html
 <ul>
			<!-- inser more links here -->
			<li class="weibo">
			    <a href="http://weibo.com/2092860157"><!-- 请修改为自己的url -->
			        <span class="fa-stack fa-lg">
                        <i class="fa fa-circle fa-stack-2x"></i>
                        <i class="fa fa-weibo fa-stack-1x fa-inverse"></i>
                    </span>
			    </a>
		    </li>

		    <li class="twitter">
			    <a href="https://twitter.com/moonlikesd">
			        <span class="fa-stack fa-lg">
                        <i class="fa fa-circle fa-stack-2x"></i>
                        <i class="fa fa-twitter fa-stack-1x fa-inverse"></i>
                    </span>
			    </a>
		    </li>

		    <li class="googleplus">
			    <a href="https://plus.google.com/u/1/113126898607169220997">
			        <span class="fa-stack fa-lg">
                        <i class="fa fa-circle fa-stack-2x"></i>
                        <i class="fa fa-google-plus fa-stack-1x fa-inverse"></i>
                    </span>
			    </a>
		    </li>

		   <li class="rss">
			    <a href="http://node.freedom.moe/rss/">
			        <span class="fa-stack fa-lg">
                        <i class="fa fa-circle fa-stack-2x"></i>
                        <i class="fa fa-rss fa-stack-1x fa-inverse"></i>
                    </span>
			    </a>
		    </li>
	</ul>
```
Change Menu Link 
  Replace  to your menu link (in navigation.hbs)
```html
       {{#foreach navigation}}
<li><a href="{{url absolute="true"}}" >{{label}}</a></li>
     {{/foreach}}
```
### Demo image:
![1](/assets/img/1.png)
![2](/assets/img/2.png)
![3](/assets/img/3.png)

## Minecraft-Kotori主题 1.0.1正式版

#### 中文说明
1. 去掉一些js和不能自适应页面的的菜单。
2. 去掉部分CDN文件。
3. 提高页面响应速度。
4. 添加底部版权
5. 修改菜单栏
6. 移除侧边栏
7. 修改文章标题样式

#### 鸣谢
感谢JclMiku帮忙 [JclMiku](https://github.com/JclMiku)

#### 存在的Bug
logo image图片不能自适应

#### 下一步添加min.css框架，去掉原有的css,需要一些时间。


####  Angel-Lite Ghost Theme 0.1 beta 中文说明
1. 修改  `/post.hbs` 文件的  `disqus_shortname = ''`  引号内,内容为 你的disqus ID.
2. 修改文件 `partials/header.hbs` `partials/menu.hbs` `partials/menu2.hbs` `partials/footer.hbs`的links变为你自己的.
3. 修改 `/deafult.hbs`里面的javascript CDN，换成你自己的。
example：  

```html
           <!--[if lt IE 9]>
           <script src="{{asset "js/selectivizr-min.js"}}"></script>
           <script src="{{asset "js/html5.js"}}"></script>
        <![endif]-->
```
####演示地址：
[Live Demo](http://www.moecloud.org)

#### Bug修复
无
#### 存在已知Bug
main.js的$不能为read
## 欢迎大家push fix，有很多不足的地方，请多多指教。

### 历史版本
1. Angel-Lite Ghost Theme 0.1 beta
2. Angel-Lite Ghost Theme 0.2 release
3. Minecraft-Kotori Ghost Theme 1.0 release

##此主题基于Kular框架上添加，去掉不能自适应的菜单。

=====

Modern Ghost Theme

##Kular | Modern Ghost Theme

###Download: [Kular](https://github.com/tuanphongtruong/Kular/archive/master.zip)
###Behance: [Kular](https://www.behance.net/tuanphongtruong)
###Preview: [Kular](https://kular-tuanphongtruong-1.c9.io) (you must load unsafe script)

1. Introduce
Kular, the modern & responsive theme for Ghost Blog. It is designed to focus content, it
suitable for blog, mini news page,...
  * Masonry Layout.
  * Responsive.
  * Infinite scrolling.
  * Clean & focus content.
  * And more...
2. Contact me
  * Facebook: [Tuấn Phong Trương](facebook.com/tuanphongtruong98)
  * Email: tuanphongtruong@protonmail.ch or tuanphongtruong@hotmail.com
