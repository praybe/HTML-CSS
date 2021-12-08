```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>홀리그램2</title>

        <style>
            * {
                color: #000000;
            }
            #wrap {
                width: 500px;
                background-color: #ffea71;
                border: 2px solid #9795ff;
                text-align: center;
                overflow: hidden;   /*집 나간 토끼를 불러온(밖에 있는 거를 무조건 불러오는 것)*/
            }
            #content {
                width: 300px;
                border: 1px solid rgb(70, 20, 20);
                float: left;
            }
            #side_banner {
                border: 1px solid rgb(70, 20, 20);
                float: right;
            }

            #footer{
                clear: both; 
                width: 500px;
                background-color: #ffb6b6;
                border: 3px solid #5f3232;
                text-align: center;
            }

            .menu1{
                color: #7fe765;
                font-weight: bold;
            }
            .menu2,.menu3,.menu5{
                color: #000000;
                font-weight: bold;

            }
            ul li.menu{
                color: #97467c;
                font-weight: bold;
                font-size: 30px;
            }
        </style>

    </head>

    <body>
        <div id="wrap">
            <div id="header">
                <h1>Header</h1>
            </div>
        </div>
        <div id="wrap">
            <div id="content">

                <h1>CONTENT</h1>
                <ul>
                    <li class="menu1">메뉴1</li>
                    <li class="menu2">메뉴2</li>
                    <li class="menu3">메뉴3</li>
                    <li class="menu4">메뉴4</li>
                    <li class="menu5">메뉴5</li>

                    <ul>
                        <li class="menu">menu1</li>
                        <li>menu2</li>
                        <li class="menu">menu3</li>
                        <li>menu4</li>
                        <li class="menu">menu5</li>
                    </ul>
                    <ol>
                        <li class="menu">menu1</li>
                        <li>menu2</li>
                        <li class="menu">menu3</li>
                        <li>menu4</li>
                        <li class="menu">menu5</li>
                    </ol>
                </ul>
            </div>

            
            
            
            <div id="side_banner">

                <h1>BANNER</h1>
                <ul>
                    <a href="http://www.sba.seoul.kr" target="_blank"><img src="http://www.sba.seoul.kr/kr/images/footer/f_logo.png"></a>

                </ul>
            </div>

        </div>
        <div id="footer">
            <h1>FOTTER</h1>

        </div>

    </body>

</html>
```
