<h1 align="center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<p align="center">Лабораторная работа №7</p>
<p align="center">"CSS"</p>
<br>
<p align="right">Работу выполнила Чёо Эрика Ильинична</p>
<p align="right">Работу проверил Соболев Евгений Игоревич</p>

___

### **Цели и задачи:**
Повторить страницу по образцу, используя элементы из архива lab7.zip:
![Образец](Образец.png)

___

### **Код страницы:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css"> 
    <link href="https://fonts.googleapis.com/css2?family=Cookie&family=Lato&display=swap" rel="stylesheet"> 
    <title>Document</title>
</head>
<body style="margin: 0px; padding: 0px; background-image: url(lab7/wrapper-bg.png);">
    <div style="background-image: url(lab7/header-wrapper-bg.png);height:187px; text-align: center; ">
        <div style="margin: auto; padding-top: 35px; text-align: center; display: flex; align-items: center; justify-content: center;">
            <span class="name">
                Elysa4t
            </span> 
            <div id="left"></div>
            <div id="curr">
                <span style="float: left; width: 50px; height: 65px; color: white; font-size: 17px; padding-top: 10px; cursor: pointer; ">
                    Home
                </span>
            </div>
            <span id="right"></span> 
            <span class="but">
                Archives
            </span>  
            <span class="but">
                Gallery
            </span> 
            <span class="but">
                About
            </span> 
            <span class="but">
                Contact
            </span></div>
    </div>

    <div style="background-image: url(lab7/banner-wrapper-bg.png); height: 350px">
        <div style="width: 718px; margin: auto; padding-top: 30px; padding-right: 95px;">
            <img src="lab7/banner-image.jpg" alt="" style="position: absolute; width: 868px;"> 
                <div style="background: url(lab7/footer-content-bg-02.png); width: 868px; height: 80px; margin-top: 210px; border-radius: 8px; position: absolute; 
                color: white; text-align: center;">
                    <p style="margin: 0px; padding-top: 20px; font-size: 35px; font-family: 'Cookie'; "><b>Magna sed phasellus consequat lorem ipsum dolor</b></p>
                </div>
        </div>
    </div>

    <div style="background-image: url(lab7/page-wrapper-bg.png); height: 540px; text-align: center; display: flex; 
    align-items: center; justify-content: center;">
        <div style="margin-bottom: 10px; margin-top: 20px;">
            <div style="float: left; width: 545px; height: 503px; background-color: white; border-radius: 2px; margin-left: 70px; margin-right: 30px;">
                <div>
                    <img id="post" src="lab7/post-posted-bg.png" alt="">
                    <p id="posttext">Posted by <span style="text-decoration: underline;">Someone</span> on April 14, 2012</p>
                </div>
                <br>
                <span id="lorem">Lorem ipsum sed veroeros amet</span>
                <img id="postbig" src="lab7/pics01.jpg">
                <br>
                <p id="posttext2">Nam vestibulum hendrerit orci, sed pharetra elit elementum in. 
                    Donec in eros sed odio varius tempus. 
                    Vestibulum quis quam et velit rutrum ornare nec a massa. 
                    Curabitur malesuada ullamcorper nunc in suscipit. 
                    Donec semper venenatis dui sed facilisis. 
                    Morbi congue facilisis ante in feugiat. 
                    Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. 
                    aecenas semper massa ac odio ornare sodales. 
                    Nunc rhoncus vulputate nisi sed malesuada. 
                    Fusce ac mauris dui, id luctus ligula. 
                    Integer hendrerit.
                </p>
                <div id="lastpost">
                    <span id="lasttext">Posted in <span id="lasttext_style1">News</span>, 
                        <span id="lasttext_style1">Design</span>, <span id="lasttext_style1">Other</span></span> 
                        <span id="lasttext_style2">235 Comments</span>
                </div>
            </div>

            <div style="float: left; width:350px; height: 503px; border-radius: 5px; margin-bottom: 10px;">
                <div style="background-image: url(lab7/sidebar-bg-01.png); background-repeat: no-repeat; height: 15px;"> </div>
                <div style="background-image: url(lab7/sidebar-bg-02.png); background-repeat: repeat-y; height: 473px;">
                        <div style="height: 135px;">
                            <img id="sbpost" src="lab7/sidebar-title-bg.png" alt="" style="margin-top: 10px;">
                            <p id="posttext" style="margin-top: 15px;"><b>About Elysa4t</b></p>
                            <p id="sba">Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet.
                                Maecenas semper massa amet et odio mauris dui, id luctus amet ligula.</p>
                        </div>
                        <div style="height: 190px;">
                            <img id="sbpost" src="lab7/sidebar-title-bg.png" alt="" style="margin-top: 10px;">
                            <p id="posttext" style="margin-top: 15px;"><b>Recent Post</b></p>
                            <p id="rec" style="margin-top: 50px; font-size: 13px;"><b>Hendrerit orci sed pharetra elit</b></p>
                            <hr id="line" color="#301c16">
                            <p id="rec" style="margin-top: 78px; font-size: 13px;"><b>Donec in eros odio varius tempus</b></p>
                            <hr id="line" color="#301c16" style="margin-top: 98px;">
                            <p id="rec" style="margin-top: 106px; font-size: 13px;"><b>Vestibulum quis quam et velit</b></p>
                            <hr id="line" color="#301c16" style="margin-top: 126px;">
                            <p id="rec" style="margin-top: 134px; font-size: 13px;"><b>Rutrum ornare nec sed curabitur</b></p>
                            <hr id="line" color="#301c16" style="margin-top: 154px;">
                            <p id="rec" style="margin-top: 162px; font-size: 13px;"><b>Malesuada ullamcorper nunc</b></p>
                        </div>
                        <div>
                            <img id="sbpost" src="lab7/sidebar-title-bg.png" alt="" style="margin-top: 10px;">
                            <p id="posttext" style="margin-top: 15px;"><b>Something Else</b></p>
                            <p id="sba" style="margin-top: 55px;">Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. 
                                Maecenas semper massa amet et odio mauris dui, id luctus amet ligula.</p>
                        </div>
                </div>
                <div style="background-image: url(lab7/sidebar-bg-03.png); background-repeat: no-repeat; height: 15px;"></div>
            </div>
        </div>
    </div>
    
    <div style="background-image: url(lab7/footer-content-bg-02.png); height: 255px;">
        <div style="width: 895px; margin: auto; color: #ceaba4; margin-left: 464px;">
            <div style="width: 273px; float: left; margin-right: 30px;">
                <div id="top"></div>
                <div id="middle">
					<h4 style="color: white; margin-top: 5px;">Just another widget</h4>
					<p style="font-size: 13px; line-height: 20px;">Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. 
                        Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
                </div>
                <div id="bottom"></div>
			</div>
            <div style="width: 273px; float: left; margin-right: 30px;">
                <div id="top"></div>
                <div id="middle">
					<h4 style="color: white; margin-top: 5px;">Just another widget</h4>
					<p style="font-size: 13px; line-height: 20px;">Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. 
                        Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
                </div>
                <div id="bottom"></div>
			</div>
            <div style="width: 273px; float: left;">
                <div id="top"></div>
                <div id="middle">
					<h4 style="color: white; margin-top: 5px;">Just another widget</h4>
					<p style="font-size: 13px; line-height: 20px;">Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. 
                        Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
                </div>
                <div id="bottom"></div>
			</div>
        </div>
    </div>

    <div style="background-image: url(lab7/footer-bg.png); height: 120px;">
        <br>
        <p style="text-align: center; font-size: 15px; color: rgba(170, 112, 73, 0.486);"> &copy Your website Name | Elysa4t by <span style="text-decoration: underline; cursor: pointer;">4Templates</span> 
            | Photos by <span style="text-decoration: underline; cursor: pointer;">Fotogrph</span></p>
    </div>
</body>
</html>
```

___

### **Вывод:**
После выполнения данной лабораторной работы я повысила свои навыки работы с HTML и CSS
