# 笔记

## div样式添加高度没有显示出来

原因：html给了高度，body没有给高度，这样body中的div元素无论给什么高度样式都无法显示出来

~~~！

<html>
    <head>
        <meta charset="utf-8">
        <title>11</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
            }
        /*body要给高度才能显示*/
        html{
            height: 100%;
            color: white;
        }
        #container {
                width: 100%;
                margin: 0 auto;
                height: 10%;
                background: blanchedalmond;
        }
        </style>
    </head>
    <body>
        <div id="container">
        </div>
    </body>
</html>
~~~

![](div不显示.png)
![](div显示.png)