<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
  <body>
<h2>关于</h2>
<p>得益于博客园可以自定义页面CSS样式的功能，自己试着写了一个CSS，仿CSDN博客名曰 编程工作室 的博客园(cnblogs)主题。是基于cnblogs的BlackLowKey主题上定制的CSS。</p>
<h2>使用</h2>
1、先选上BlackLowKey主题。
2、将代码放到“页面定制CSS代码”处。
<h2>代码</h2>
<code>
*{
font-family:'microsoft yahei' !important;
}

a{
text-decoration: none !important;
-webkit-transition: .3s;
}

a:hover{
//border:1px solid  #c5c6c4;
color:#FD7B2F !important;
}

body{
 //background:url("http://ww2.sinaimg.cn/large/8b492815gw1dvbhg6ijgbj.jpg") top center repeat #fff; 
 background:url("http://static.blog.csdn.net/skin/skin-yellow/images/bg-yellow.png") top center repeat #fff; 
 font-size:15px !important;
}

#header{
background:url("http://static.blog.csdn.net/skin/skin-yellow/images/title-yellow.png") top center no-repeat #fff; 
background-position:50% 50%; 
background-size:90% 90%;
height:300px !important;
background-color:rgba(0,0,0,0);
}

#navigator{
margin-top:140px;
}

#home{
width:1245px;
}

#mainContent{
width:940px;
float:right;
}

#topics {
margin-top: 25px;
}

#sideBar{
width:270px;
margin-left: 0px !important;
padding: 0 5px 0 20px !important;
float:left;
}

.blogStats{
visibility:visible !important;
margin-right: 30px !important;
}

#blogTitle{
padding-left: 125px;
padding-top: 65px;
}

#MyLinks1_HomeLink{
visibility:hidden;
}

#main{
margin-top:25px;
}

#navList{
margin-left:-30px;
}

#footer{
color:#000;
}

.postTitle{
font-size:16px;
}

#navList a{
font-size:16px !important;
}

.logo{
text-align:center;
}

#profile_block{
//text-align:center;
}

#blog-calendar{
display:none !important;
}

::selection {
color: #FFF;
background: #FF6100;
}

.catListTitle {
color:#FF6100 !important;
border-bottom: 1px solid #ccc !important;
border-left: 0px !important;
border-right: 0px !important;
border-top: 0px !important;
background: #fff !important;
}

#widget_my_google{
display:none;
}

.catListLink ul li{
border-bottom: 1px dashed #ccc;
list-style: disc;
}

.catListComment ul li{
border-bottom: 1px dashed #ccc;
}

.catListPostCategory ul li{
border-bottom: 1px dashed #ccc;
list-style: disc;
}

.catListPostArchive ul li{
border-bottom: 1px dashed #ccc;
list-style: disc;
}

.catListView ul li{
border-bottom: 1px dashed #ccc;
list-style: disc;
}

.input_my_zzk{
border:1px solid #ccc !important;
height:30px !important;
width: 160px !important;
}

.btn_my_zzk{
width: 100px !important;
height: 30px !important;
background: #FF6100 !important;
color: #FFF !important;
height: 32px !important;
line-height: 30px !important;
text-align: center !important;
border:1px solid #FF6100 !important;
font-size: 15px !important;
}

input{
border-radius: 3px;
border: solid 1px #DDD;
}

textarea {
border-radius: 10px;
width: 900px!important;
height: 200px!important;
border: solid 1px #DDD;
}

#green_channel a {
display: inline-block !important;
padding: 3px 8px !important;
font-weight: bold !important;
cursor: pointer !important;
margin-right: 10px !important;
text-shadow: 0 0px 0px rgba(0,0,0,0) !important;
font-size: 13px !important;
-webkit-border-radius: 0px !important;
-moz-box-shadow: 0 1px 3px rgba(0,0,0,0) !important;
}

#comment_form{
padding:0 10px 0 10px !important;
}

//去绿色通道
#green_channel{
display:none !important;
border:0;
}

#bq{
display:none;
}

//去广告
#site_nav_under, #ad_under_post_holder, #comment_form_container,blog_news_kb,google_ad_c2, #comment_nav{
display:none !important;
}

#site_nav_under,#google_ad_c1,#under_post_news,#google_ad_c2,#under_post_kb{
display:none !important;
}
</code>
</body>
</html>