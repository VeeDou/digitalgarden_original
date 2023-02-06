---
{"dg-publish":true,"permalink":"/文章/index/","tags":["gardenEntry"]}
---


这是我的数字花园主页！
记录一些乱七八糟
<!-- 
Name：bppws
Author：kaygb
Version：20200708
-->
<!DOCTYPE html>
<html lang="">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>一泉温汤</title>
    <meta name="keywords" content="相对静止的个人主页,一日不多，十日聚多">
    <meta name="theme-color" content="#000">
    <link rel="shortcut icon" href="" type="image/x-icon">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/kaygb/Apage@master/pws20200708/style.css">
    <style>
            h1::before{
                content: 'KAYGB\'S HOME';
                position: absolute;
                color: #b2bec348;
                z-index: -1;
                left: 10px;
                top: 10px;
            }
    </style>
</head>
<body>
    <div class="zz">
        <img class="lazy-img" data-original="https://i.loli.net/2020/09/14/v4Si8BIupOVcwm6.jpg" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAEALAAAAAABAAEAAAICRAEAOw==" alt="" srcset="">
    </div>

    <div class="main">
        
        <div class="title">
            <h1>KAYGB'S HOME</h1>
        </div>
        <div class="content">
            <p>LIFE IS A STORY.</p>
            <p>So, enjoy life!</p>
            <p>Whatever you do, you hold on to that foolishly hopeful smile.</p>
            <p>You can catch me on my <a href="https://blog.kaygb.com/" target="_blank">blog</a> or read my <a href="https://wiki.eas1.cn/" target="_blank">wiki</a>.</p>
        </div>
        <div class="footer">
            <span>&copy; 一泉温汤</span>&nbsp;

            <span>Power by : <a href="https://github.com/oleeskild/obsidian-digital-garden" target="_blank">digital-garden</a></span>
            <br>
            
        </div>

    </div>

    <script src="https://cdn.staticfile.org/jquery/3.2.1/jquery.min.js"></script>
    <script src="https://cdn.staticfile.org/jquery_lazyload/1.9.7/jquery.lazyload.min.js"></script>
    <script>
        // lazyload
    window.onload = function() {
        $('.zz img').addClass('lazyload');
        $(function() {
            $("img.lazyload").lazyload({
                effect: 'fadeIn',
                // inverval: 3000
                effectspeed: 1000
            });
        });

        $(".zz img").lazyload({
            effect: 'fadeIn',
            // inverval: 3000
            effectspeed: 1000 
        });
    }
    console.log(" %c bppws %c https://github.com/kaygb/Apage/ ", "color: #000; background: pink; padding:5px;", "background: #fff; padding:5px;");
//初始化
    </script>
</body>
</html>

<html lang="en">
<head>
<meta charset="UTF-8">
<title>花的绽放</title>
<style type="text/css">
        .header {
        width: 800px;
        height: 800px;
        margin: 0 auto;
        position: relative;
        }
     .header div {
       height: 300px;
       width: 300px;
       background: blue;
       border-radius: 300px 0;
       position: absolute;
       bottom: 100px;
       left:200px;
       opacity:0.6;
       transform-origin:0 300px;
       transform:rotate(-45deg);
       transition:all 8s;
     }
.header:hover .header1{
transform:rotate(-23deg);
} 
.header:hover .header2{
transform:rotate(5deg);
}
.header:hover .header3{
transform:rotate(-68deg);
}
.header:hover .header4{
transform:rotate(-95deg);
} 
.header:hover .header5{
transform:rotate(30deg);
} 
.header:hover .header6{
transform:rotate(-120deg);
}  
.header:hover .header7{
transform:rotate(50deg);
}
.header:hover .header8{
transform:rotate(-140deg);
}  
</style>
</head>
<body>
<div class="header">
<div class="header1"></div>
<div class="header2"></div>
<div class="header3"></div>
<div class="header4"></div>
<div class="header5"></div>
<div class="header6"></div>
<div class="header7"></div>
        <div class="header8"></div>
<div class="header9"></div>


</div>
</body>
</html>