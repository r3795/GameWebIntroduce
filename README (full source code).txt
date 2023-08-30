---------------------------------------------------------------------Main Page---------------------------------------------------------------------
1. 브라우저 오픈 시 자동으로 음악이 재생됩니다.  거슬리시면 오른쪽 상단에 오디오바를 설정해주세요! 
2. 소개 글 오른 쪽 사진 클릭 시 인 게임 정보가 팝업됩니다.
3. Today's Game 텍스트 클릭시 게임 로고가 출력됩니다.
4. 다른 페이지로 이동코자 하실 경우 메뉴바의 텍스트를 눌러주세요!!

---------------------------------------------------------------------Introduce Page---------------------------------------------------------------------
1. 브라우저 오픈 시 자동으로 음악이 재생됩니다.  거슬리시면 오른쪽 상단에 오디오바를 설정해주세요! 
2. 소개 글 오른 쪽 사진 클릭 시 인 게임 정보가 팝업됩니다.
3. Contents 박스안에 각 이미지 별로 클릭 시 링크 오픈, GIF 오픈 효과를 가지고 있습니다.
4. 다른 페이지로 이동코자 하실 경우 메뉴바의 텍스트를 눌러주세요!!

---------------------------------------------------------------------Character Page---------------------------------------------------------------------
1. 브라우저 오픈 시 자동으로 동영상이 팝업됩니다.  거슬리시면 닫기를 눌러주세요!! 
([오늘 하루 이창을 열지 않음] 체크 박스 클릭시 하루동안 열리지않습니다.)
2. 오른쪽 동영상 클릭 시 페이지내에서 재생이 가능합니다.
3. 각 직업 별 로고 클릭 시 직업 이미지 레이어 팝업 및 귀여운 사운드가 출력됩니다.
4. 레이어 상태에서 사진을 넘기고자 하실때는 사진에 오른쪽이나 왼쪽을 클릭해주세요.
5. 레이어 상태에서 사진을 종료코자 하실떄는 사진 밖 여백을 클릭해주세요.
4. 다른 페이지로 이동코자 하실 경우 메뉴바의 텍스트를 눌러주세요!!

---------------------------------------------------------------------Video Page---------------------------------------------------------------------
1. 브라우저 오픈 시 자동으로 음악이 재생됩니다.  거슬리시면 오른쪽 상단에 오디오바를 설정해주세요! 
2. 중앙 동영상 클릭 시 페이지내에서 재생이 가능합니다.
3. 게임 정보 이미지에 마우스를 가져가시면 이미지가 확대됩니다.
4. 다른 페이지로 이동코자 하실 경우 메뉴바의 텍스트를 눌러주세요!!



---------------------------------------------------------------------Full Source code---------------------------------------------------------------------
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>201812633</title>
    <link rel="stylesheet" href="lightbox.min.css">
    <style>
        * 
        { 
            margin: 0; padding: 0; 
        }
        .container
        {
            margin: 0 auto;
            width: 1080px;
            margin-bottom: 8px;
            overflow: hidden;
        }
        .container > audio
        {
            float: right;
        }
        body
        {
            background-image: url("2.jpg");
            background-position: center;
            background-size: cover;
            height: 110vh;
            max-width: 100%;
        }
        #top
        {
            position: relative;
            border-radius: 10px;
            width: 1080px;
            height: 500px;
            overflow: hidden;
        }
        #top > #img
        {
            position: absolute;
            bottom: 50px;
            right: 15px;
            width: 500px;
            height: 250px;
            background-repeat: no-repeat;
            background-image: url("1.gif");
            background-size: cover;
            background-position: center;
            border-radius: 10px;
            z-index: 10;
        }
        #menu
        {
            position: absolute;
            left: 20px;
            bottom: 50px;
            width: 450px;
            background: rgba(0, 0, 0, 0.596);
            text-align: center;
            z-index: 10;
            border-radius: 10px;
            padding-left: 20px;
            border: 1px solid white;
        }
        #menu > a > li
        {
            
            padding: 8px 10px;
            float: left;
            list-style-type: none;
            padding-left: 0px;
            font-size: 200%;
            font-family: fantasy;
            text-align: center;
            color: white;
            
        }
        #menu > a > li:hover
        {
            color: rgba(185, 167, 167, 0.733);
        }
        #middle
        {
            overflow: hidden;
            padding-bottom: 50px;
        }
        #left
        {
            float: left; 
            height: 300px; 
            width:  529px; 
            background: rgba(255, 255, 255, 0.514);
            background-size: cover;
            border-radius: 10px;
            margin-right: 10px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #left .example-image-link
        {
            float: right;
            margin-top: 35px;
            margin-right: 30px;
            background-size: cover;
            border-radius: 10px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #left p
        {
            margin-top: 15px;
            margin-left: 20px;
            font-size: 150%;
            font-family: fantasy;
            text-align: left;
            color: white;
            filter: drop-shadow(4px 4px 4px #000);
            
        }
        #right
        {
            float: right; 
            position: relative;
            height: 300px; 
            width:  529px; 
            background: rgba(255, 255, 255, 0.514);
            border-radius: 10px;
            margin-left: 10px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #right p
        {
            position: absolute;
            top: 30%;
            left: 20%;
            font-size: 300%;
            font-family: fantasy;
            text-align: center;
            color: white;
            filter: drop-shadow(4px 4px 4px #000);
        }
        @media screen and (max-width: 1000px)
        {
            .container { width: 767px;}
            audio { display: none; }
            #menu { left: 160px; bottom: 3px;}
            #top > #img { left: 150px; top: 150px; }
            #left { float: none; margin: 20px 130px; }
            #right { float: none; margin: 0 130px; }
        }
        @media screen and (max-width: 800px)
        {
            .container { width: 600px;}
            audio { display: none; }
            #menu { left: 80px; bottom: 3px;}
            #top > #img { left: 70px; top: 150px; }
            #left { float: none; margin: 20px 50px; }
            #right { float: none; margin: 0 50px; }
        }
        @media screen and (max-width: 650px)
        {
            .container { width: 400px;}
            audio { display: none; }
            #menu { left: 25px; bottom: 3px; font-size: 60%; width: 330px;}
            #top > #img { left: 15px; top: 150px; width: 370px; }
            #left { float: none; margin: 20px 10px; width: 380px; }
            #right { float: none; margin: 0 10px; width: 380px; }
            #left p { margin-top: 8px; }
            #right p { left: 10%; }
        }
    </style>
    <script>
        function change()
        {
            var p = document.getElementById("cl");
            p.innerHTML="<img src='lostark.png'>";
        }
    </script>
</head>
<body>
    <div class="container">
        <audio controls loop autoplay preload= "auto">
            <source src="bgm.mp3" type="audio/mp3">
        </audio>
        <div id="top">
            <div id="img"></div>
            <ul id="menu">
                <a href="index.html">
                    <li>Main</li>
                </a>
                <a href="introduce.html">
                    <li>Introduce</li>
                </a>
                <a href="character.html">  
                    <li>Character</li>
                </a>
                <a href="video.html">  
                    <li>Video</li>
                </a>
            </ul>
            </div>
        </div>
    <div class="container">
        <div id="middle">
            <div id="left">
                <a class="example-image-link" href="character_info.png" data-lightbox="example-set" data-title="게임 정보"><img class="example-image" src="me.jpg" alt="image-1" /></a>
                <p>Major <br>Computer Engineering</p>
                <p>Class of <br>201812633</p>
                <p>Name <br>Jongwon Choi</p>
                <p>Genre <br>Game</p>
            </div>
            <div id="right">
                <p id="cl" onclick="change()">Today's Game?<p>
            </div>
        </div>
    </div>
    <script src="lightbox-plus-jquery.min.js"></script>
</body>
</html>
------------------------------------------------------------------------------------------------------------------------------------------
introduce.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>201812633</title>
    <style>
        * 
        { 
            margin: 0; padding: 0; 
        }
        .container
        {
            margin: 0 auto;
            width: 1080px;
            margin-bottom: 8px;
            overflow: hidden;
        }
        .container > audio
        {
            float: right;
        }
        body
        {
            background-image: url("4.jpg");
            background-position: center;
            background-size: cover;
            height: 110vh;
            max-width: 100%;
        }
        #top
        {
            position: relative;
            border-radius: 10px;
            width: 1080px;
            height: 500px;
            overflow: hidden;
        }
        #top > #img
        {
            position: absolute;
            bottom: 50px;
            right: 15px;
            width: 500px;
            height: 250px;
            background-repeat: no-repeat;
            background-image: url("pinyata.gif");
            background-size: cover;
            background-position: center;
            border-radius: 50px;
            z-index: 10;
        }
        #menu
        {
            position: absolute;
            left: 20px;
            bottom: 50px;
            width: 450px;
            background: rgba(255, 255, 255, 0.589);
            text-align: center;
            z-index: 10;
            border-radius: 10px;
            padding-left: 20px;
            border: 1px solid white;
        }
        #menu > a > li
        {
            
            padding: 8px 10px;
            float: left;
            list-style-type: none;
            padding-left: 0px;
            font-size: 200%;
            font-family: fantasy;
            text-align: center;
            color: rgba(0, 0, 0, 0.822);
            
        }
        #menu > a > li:hover
        {
            color: rgba(185, 167, 167, 0.733);
        }
        #middle
        {
            overflow: hidden;
            padding-bottom: 50px;
        }
        #left
        {
            float: left; 
            height: 300px; 
            width:  529px; 
            background: rgba(255, 255, 255, 0.514);
            background-size: cover;
            border-radius: 10px;
            margin-right: 10px;
            filter: drop-shadow(4px 4px 4px rgb(250, 218, 218));
        }
        #left p:first-child
        {
            text-align: center;
            font-family: fantasy;
            color: white;
            font-size: 200%;
            margin: 10px;
            font-weight: 1500;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #left p
        {
            font-family: fantasy;
            color: rgba(0, 0, 0, 0.822);
            font-size: 150%;
            margin: 10px;
            font-weight: bold;
            filter: drop-shadow(4px 4px 4px rgb(255, 255, 255));
            margin-top: 30px;
            margin-left: 30px;
        }
        #left #icon
        {
            float: right;
            width: 120px;
            height: 130px;
            margin-top: 30px;
            margin-right: 45px;
            background-size: cover;
            background-image: url(loa_icon.jpg);
            border-radius: 60px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #right
        {
            float: right; 
            height: 300px; 
            width:  529px; 
            background: rgba(255, 255, 255, 0.514);
            border-radius: 10px;
            margin-left: 10px;
            filter: drop-shadow(4px 4px 4px rgb(250, 218, 218));
        }
        #right > p
        {
            filter: drop-shadow(4px 4px 4px #000);
            font-family: fantasy;
            color: white;
            font-size: 200%;
            margin-top: 20px;
            margin-left: 20px;
        }
        #right a
        {
            text-decoration: none;
        }
        #right a span
        {
            margin-left: 10px;
            filter: drop-shadow(4px 4px 4px #000);
            font-family: fantasy;
            color: white;
            font-size: 160%;
            text-decoration: none;
        }
        #right #map
        {
            display: inline-block;
            background-image: url("map.png");
            background-size: cover;
            width: 100px;
            height: 80px;
            filter: drop-shadow(4px 4px 4px #000);
            border-radius: 10px;
            margin-top: 50px;
            margin-left: 10px;
        }
        #right #raid
        {
            display: inline-block;
            background-image: url("baltan.jpg");
            background-size: cover;
            width: 100px;
            height: 80px;
            filter: drop-shadow(4px 4px 4px #000);
            border-radius: 10px;
            margin-top: 50px;
            margin-left: 10px;
        }
        #right #life
        {
            display: inline-block;
            background-image: url("mokoko.gif");
            background-size: cover;
            width: 100px;
            height: 80px;
            filter: drop-shadow(4px 4px 4px #000);
            border-radius: 10px;
            margin-top: 50px;
            margin-left: 10px;
        }
        @media screen and (max-width: 1000px)
        {
            .container { width: 767px;}
            audio { display: none; }
            #menu { left: 160px; bottom: 3px;}
            #top > #img { left: 150px; top: 150px; }
            #left { float: none; margin: 20px 130px; }
            #right { float: none; margin: 0 130px; }
        }
        @media screen and (max-width: 800px)
        {
            .container { width: 600px;}
            audio { display: none; }
            #menu { left: 80px; bottom: 3px;}
            #top > #img { left: 70px; top: 150px; }
            #left { float: none; margin: 20px 50px; }
            #right { float: none; margin: 0 50px; }
        }
        @media screen and (max-width: 650px)
        {
            .container { width: 400px;}
            audio { display: none; }
            #menu { left: 25px; bottom: 3px; font-size: 60%; width: 330px;}
            #top > #img { left: 15px; top: 150px; width: 370px; }
            #left { float: none; margin: 20px 10px; width: 380px; }
            #right { float: none; margin: 0 10px; width: 380px; height: 350px;}
            #left p { font-size: 120%; margin-top: 20px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <audio controls loop autoplay preload= "auto">
            <source src="mokoko_village.mp3" type="audio/mp3">
        </audio>
        <div id="top">
            <div id="img"></div>
            <ul id="menu">
                <a href="index.html">
                    <li>Main</li>
                </a>
                <a href="introduce.html">
                    <li>Introduce</li>
                </a>
                <a href="character.html">  
                    <li>Character</li>
                </a>
                <a href="video.html">  
                    <li>Video</li>
                </a>
            </ul>
            </div>
        </div>
    <div class="container">
        <div id="middle">
            <div id="left">
                <p>Welcome to LostArk</p>
                <a href="https://lostark.game.onstove.com/WorldView"><div id="icon"></div></a>
                <p>Game Name : LostArk</p>
                <p>Game Genre : MMORPG</p>
                <p>Game View : Quarter View</p>
                <p>Release : 2019 / 12 / 04</p>
            </div>
            <div id="right">
                <p>Contents</p>
                <a href="https://lostark.game.onstove.com/WorldMap"><div id="map"></div><span>Map</span></a>
                <a href="baltan.gif"><div id="raid"></div><span>Raid</span></a>
                <a href="life.gif"><div id="life"></div><span>Life</span></a>
            </div>
        </div>
    </div>
</body>
</html>
------------------------------------------------------------------------------------------------------------------------------------------
character.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>201812633</title>
    <link rel="stylesheet" href="lightbox.min.css">
    <style>
        * 
        { 
            margin: 0; padding: 0; 
        }
        .container
        {
            margin: 0 auto;
            width: 1080px;
            margin-bottom: 8px;
            overflow: hidden;
        }
        .container > audio
        {
            float: right;
        }
        body
        {
            background-image: url("3.jpg");
            background-position: center;
            background-size: cover;
            height: 110vh;
            max-width: 100%;
        }
        #top
        {
            position: relative;
            border-radius: 10px;
            width: 1080px;
            height: 500px;
            overflow: hidden;
        }
        #top > iframe
        {
            position: absolute;
            bottom: 50px;
            right: 15px;
            width: 500px;
            height: 250px;
            border-radius: 10px;
            z-index: 10;
        }
        #menu
        {
            position: absolute;
            left: 20px;
            bottom: 50px;
            width: 450px;
            background: rgba(0, 0, 0, 0.596);
            text-align: center;
            z-index: 10;
            border-radius: 10px;
            padding-left: 20px;
            border: 1px solid white;
        }
        #menu > a > li
        {
            
            padding: 8px 10px;
            float: left;
            list-style-type: none;
            padding-left: 0px;
            font-size: 200%;
            font-family: fantasy;
            text-align: center;
            color: white;
            
        }
        #menu > a > li:hover
        {
            color: rgba(185, 167, 167, 0.733);
        }
        #middle
        {
            overflow: hidden;
            padding-bottom: 50px;
        }
        #left
        {
            float: left; 
            height: 400px; 
            width:  529px; 
            background: rgba(255, 255, 255, 0.514);
            background-size: cover;
            border-radius: 10px;
            margin-right: 10px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #left a:first-child
        {
            display: block;
            background-position: center;
            margin-bottom: 30px;
            margin-top: 20px;
            
        }
        #left a:first-child .example-image
        {
            margin-left: 210px;
            background: rgba(0, 0, 0, 0.274);
            border-radius: 10px;
        }
        #left .example-image
        {
            margin-left: 25px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #left p
        {
            margin-left: 185px;
            font-size: 300%;
            font-family: fantasy;
            color: white;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #right
        {
            float: right; 
            height: 400px; 
            width:  529px; 
            background: rgba(255, 255, 255, 0.514);
            border-radius: 10px;
            margin-left: 10px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #right a:first-child
        {
            display: block;
            background-position: center;
            margin-bottom: 30px;
            margin-top: 20px;
            
        }
        #right a:first-child .example-image
        {
            margin-left: 210px;
            background: rgba(0, 0, 0, 0.274);
            border-radius: 10px;
        }
        #right .example-image
        {
            margin-left: 25px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #right p
        {
            margin-left: 185px;
            font-size: 300%;
            font-family: fantasy;
            color: white;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #middle2
        {
            overflow: hidden;
            padding-bottom: 50px;
        }
        #left2
        {
            float: left; 
            height: 400px; 
            width:  529px; 
            background: rgba(255, 255, 255, 0.514);
            background-size: cover;
            border-radius: 10px;
            margin-right: 10px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #left2 a:first-child
        {
            display: block;
            background-position: center;
            margin-bottom: 30px;
            margin-top: 20px;
            
        }
        #left2 a:first-child .example-image
        {
            margin-left: 210px;
            background: rgba(0, 0, 0, 0.274);
            border-radius: 10px;
        }
        #left2 .example-image
        {
            margin-left: 25px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #left2 p
        {
            margin-left: 185px;
            font-size: 300%;
            font-family: fantasy;
            color: white;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #right2
        {
            float: right; 
            height: 400px; 
            width:  529px; 
            background: rgba(255, 255, 255, 0.514);
            border-radius: 10px;
            margin-left: 10px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #right2 a:first-child
        {
            display: block;
            background-position: center;
            margin-bottom: 30px;
            margin-top: 20px;
            
        }
        #right2 a:first-child .example-image
        {
            margin-left: 210px;
            background: rgba(0, 0, 0, 0.274);
            border-radius: 10px;
        }
        #right2 .example-image
        {
            margin-left: 25px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #right2 p
        {
            margin-left: 185px;
            font-size: 300%;
            font-family: fantasy;
            color: white;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #middle3
        {
            overflow: hidden;
            padding-bottom: 50px;
        }
        #left3
        {
            float: left; 
            height: 400px; 
            width:  529px; 
            background: rgba(255, 255, 255, 0.514);
            background-size: cover;
            border-radius: 10px;
            margin-right: 10px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #left3 a:first-child
        {
            display: block;
            background-position: center;
            margin-bottom: 30px;
            margin-top: 20px;
            
        }
        #left3 a:first-child .example-image
        {
            margin-left: 210px;
            background: rgba(0, 0, 0, 0.274);
            border-radius: 10px;
        }
        #left3 .example-image
        {
            margin-left: 25px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #left3 p
        {
            margin-left: 185px;
            font-size: 300%;
            font-family: fantasy;
            color: white;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #right3
        {
            float: right; 
            height: 400px; 
            width:  529px; 
            background: rgba(255, 255, 255, 0.514);
            border-radius: 10px;
            margin-left: 10px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #right3 a:first-child
        {
            display: block;
            background-position: center;
            margin-bottom: 30px;
            margin-top: 20px;
            
        }
        #right3 a:first-child .example-image
        {
            margin-left: 210px;
            background: rgba(0, 0, 0, 0.274);
            border-radius: 10px;
        }
        #right3 .example-image
        {
            margin-left: 25px;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #right3 p:first-child
        {
            text-align: center;
            font-family: fantasy;
            color: white;
            font-size: 250%;
            margin: 30px;
            font-weight: 1500;
            filter: drop-shadow(4px 4px 4px #000);
        }
        #right3 p
        {
            margin-top: 15px;
            margin-left: 20px;
            font-size: 200%;
            font-family: fantasy;
            text-align: left;
            margin-top: 20px;
            color: white;
            filter: drop-shadow(4px 4px 4px #000);
            
        }
        @media screen and (max-width: 1000px)
        {
            .container { width: 767px;}
            audio { display: none; }
            #menu { left: 160px; bottom: 3px;}
            #top > iframe { left: 150px; top: 150px; }
            #left { float: none; margin: 20px 130px; }
            #right { float: none; margin: 0 130px; }
            #left2 { float: none; margin: 20px 130px; }
            #right2 { float: none; margin: 0 130px; }
            #left3 { float: none; margin: 20px 130px; }
            #right3 { float: none; margin: 0 130px; }
        }
        @media screen and (max-width: 800px)
        {
            .container { width: 600px;}
            audio { display: none; }
            #menu { left: 80px; bottom: 3px;}
            #top > iframe { left: 70px; top: 150px; }
            #left { float: none; margin: 20px 50px; }
            #right { float: none; margin: 0 50px; }
            #left2 { float: none; margin: 20px 50px; }
            #right2 { float: none; margin: 0 50px; }
            #left3{ float: none; margin: 20px 50px; }
            #right3 { float: none; margin: 0 50px; }
        }
        @media screen and (max-width: 650px)
        {
            .container { width: 400px;}
            audio { display: none; }
            #menu { left: 25px; bottom: 3px; font-size: 60%; width: 330px;}
            #top > iframe { left: 15px; top: 150px; width: 370px; }
            #left { float: none; margin: 20px 10px; width: 380px; }
            #right { float: none; margin: 0 10px; width: 380px; }
            #middle a:first-child .example-image { margin-left: 140px; }
            #middle p { margin-left: 120px; }
            #left2 { float: none; margin: 20px 10px; width: 380px; }
            #right2 { float: none; margin: 0 10px; width: 380px; }
            #middle2 a:first-child .example-image { margin-left: 140px; }
            #middle2 p { margin-left: 120px; }
            #left3 { float: none; margin: 20px 10px; width: 380px; }
            #right3 { float: none; margin: 0 10px; width: 380px; }
            #middle3 a:first-child .example-image { margin-left: 140px; }
            #middle3 p { margin-left: 120px; }
            #divpop iframe { width: 300px; }
            #divpop table { width: 300px;}
            #right3 p { font-size: 150%; margin-left: 20px; }
        }
    </style>
    <!-- Layer popup start --> 
    <script language="JavaScript"> 
    function setCookie( name, value, expiredays ) 
    { 
        var todayDate = new Date(); 
        todayDate.setDate( todayDate.getDate() + expiredays ); 
        document.cookie = name + "=" + escape( value ) + "; path=/; expires=" + todayDate.toGMTString() + ";" 
    }
    function closeWin() 
    { 
        if ( document.notice_form.chkbox.checked )
        { setCookie( "maindiv", "done" , 1 ); 
    } 
    document.all['divpop'].style.visibility = "hidden"; } 
    function play()
    {
        var audio = document.getElementById("audio");
        audio.play();
    }
    </script> 
</head>
<body>
    <div class="container">
        <div id="top">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/O3xBRCqB3LE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            <ul id="menu">
                <a href="index.html">
                    <li>Main</li>
                </a>
                <a href="introduce.html">
                    <li>Introduce</li>
                </a>
                <a href="character.html">  
                    <li>Character</li>
                </a>
                <a href="video.html">  
                    <li>Video</li>
                </a>
            </ul>
            </div>
        </div>
    <div class="container">
        <div id="middle">
            <div id="left">
                <p>Worrior</p>
                <div>
                    <a class="example-image-link" href="job/worrior.jpg" data-lightbox="example-set1" data-title="전사"><img class="example-image" value="PLAY" onclick="play()" src="job/01-1.png" alt="image-1" /><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/destroyer.jpg" data-lightbox="example-set1" data-title="디스트로이어"><img class="example-image" value="PLAY" onclick="play()" src="job/01-2.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/warlord.jpg" data-lightbox="example-set1" data-title="워로드"><img class="example-image" value="PLAY" onclick="play()" src="job/01-3.png" alt="image-1" /><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/berserker.jpg" data-lightbox="example-set1" data-title="버서커"><img class="example-image" value="PLAY" onclick="play()" src="job/01-4.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/holyknight.jpg" data-lightbox="example-set1" data-title="홀리나이트"><img class="example-image" value="PLAY" onclick="play()" src="job/01-5.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                </div>
            </div>
            <div id="right">
                <p>Fighter</p>
                <div>
                    <a class="example-image-link" href="job/fighter.jpg" data-lightbox="example-set2" data-title="무도가"><img class="example-image" value="PLAY" onclick="play()" src="job/02-1.png" alt="image-1" /><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/battlemaster.jpg" data-lightbox="example-set2" data-title="배틀마스터"><img class="example-image" value="PLAY" onclick="play()" src="job/02-2.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/infighter.jpg" data-lightbox="example-set2" data-title="인파이터"><img class="example-image" value="PLAY" onclick="play()" src="job/02-3.png" alt="image-1" /><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/soulmaster.jpg" data-lightbox="example-set2" data-title="기공사"><img class="example-image" value="PLAY" onclick="play()" src="job/02-4.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/lancemaster.png" data-lightbox="example-set2" data-title="창술사"><img class="example-image" value="PLAY" onclick="play()" src="job/02-5.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/striker.jpg" data-lightbox="example-set2" data-title="스트라이커"><img class="example-image" value="PLAY" onclick="play()" src="job/02-6.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                </div>
            </div>
        </div>
        <div id="middle2">
            <div id="left2">
                <p>Hunter</p>
                <div>
                    <a class="example-image-link" href="job/hunter.jpg" data-lightbox="example-set3" data-title="헌터"><img class="example-image" value="PLAY" onclick="play()" src="job/03-1.png" alt="image-1" /><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/devilhunter.jpg" data-lightbox="example-set3" data-title="데빌헌터"><img class="example-image" value="PLAY" onclick="play()" src="job/03-2.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/blaster.jpg" data-lightbox="example-set3" data-title="블래스터"><img class="example-image" value="PLAY" onclick="play()" src="job/03-3.png" alt="image-1" /><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/hawkeye.jpg" data-lightbox="example-set3" data-title="호크아이"><img class="example-image" value="PLAY" onclick="play()" src="job/03-4.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/scouter.jpg" data-lightbox="example-set3" data-title="스카우터"><img class="example-image" value="PLAY" onclick="play()" src="job/03-5.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/gunslinger.jpg" data-lightbox="example-set3" data-title="건슬링어"><img class="example-image" value="PLAY" onclick="play()" src="job/03-6.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                </div>
            </div>
            <div id="right2">
                <p>Magician</p>
                <div>
                    <a class="example-image-link" href="job/magician.jpg" data-lightbox="example-set4" data-title="마법사"><img class="example-image" value="PLAY" onclick="play()" src="job/04-1.png" alt="image-1" /><audio id="audio" src="mokoko.mp3"><audio id="audio" src="mokoko.mp3"></audio></audio></a>
                    <a class="example-image-link" href="job/bard.jpg" data-lightbox="example-set4" data-title="바드"><img class="example-image" value="PLAY" onclick="play()" src="job/04-2.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"><audio id="audio" src="mokoko.mp3"></audio></audio></a>
                    <a class="example-image-link" href="job/summoner.jpg" data-lightbox="example-set4" data-title="서머너"><img class="example-image" value="PLAY" onclick="play()" src="job/04-3.png" alt="image-1" /><audio id="audio" src="mokoko.mp3"><audio id="audio" src="mokoko.mp3"></audio></audio></a>
                    <a class="example-image-link" href="job/arcana.jpg" data-lightbox="example-set4" data-title="아르카나"><img class="example-image" value="PLAY" onclick="play()" src="job/04-4.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"><audio id="audio" src="mokoko.mp3"></audio></audio></a>
                </div>
            </div>
        </div>
        <div id="middle3">
            <div id="left3">
                <p>Assassin</p>
                <div>
                    <a class="example-image-link" href="job/assassin.jpg" data-lightbox="example-set5" data-title="암살자"><img class="example-image" value="PLAY" onclick="play()" src="job/05-1.png" alt="image-1" /><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/demonic.jpg" data-lightbox="example-set5" data-title="데모닉"><img class="example-image" value="PLAY" onclick="play()" src="job/05-2.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/blade.jpg" data-lightbox="example-set5" data-title="블레이드"><img class="example-image" value="PLAY" onclick="play()" src="job/05-3.png" alt="image-1" /><audio id="audio" src="mokoko.mp3"></audio></a>
                    <a class="example-image-link" href="job/reaper.jpg" data-lightbox="example-set5" data-title="리퍼"><img class="example-image" value="PLAY" onclick="play()" src="job/05-4.png" alt="image-1"/><audio id="audio" src="mokoko.mp3"></audio></a>
                </div>
            </div>
            <div id="right3">
                <p>Job Classification<p>
                <p>Large Classification : 5Job Series</p>
                <p>Small Classification : 20Jobs</p>
                <p>Ingame Classification : <br>Support or Dealer</p>
                <p>Latest Release Job : Striker</p>
            </div>
        </div>
    </div>
    <div id="divpop" style="position:absolute;left:100px;top:150px;z-index:200;visibility:hidden;">
        <table width=570px height=340px cellpadding=0 cellspacing=0>
            <tr>
                <td style="border:1px #666666 solid" height=auto align=center bgcolor=black>
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/R5iQ32XxRKo" title="YouTube video player" 
                    frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </td> 
            </tr> 
            <tr> 
                <form name="notice_form"> 
                    <td height=25 align=right bgcolor="#000000" valign=middle> 
                        <input type="checkbox" name="chkbox" value="checkbox"> 
                        <font color=#eeeeee>오늘 하루 이 창을 열지 않음 </font>
                        <a href="javascript:closeWin();"> 
                            <font color=#eeeeee> <B>[닫기]</B> </font>
                        </a> 
                    </td> 
                </form> 
            </tr> 
        </table> 
    </div>
    <script language="Javascript"> 
        cookiedata = document.cookie; 
        if ( cookiedata.indexOf("maindiv=done") < 0 ){ document.all['divpop'].style.visibility = "visible"; } 
        else { document.all['divpop'].style.visibility = "hidden"; } 
    </script>
    <script src="lightbox-plus-jquery.min.js"></script>
</body>
</html>
------------------------------------------------------------------------------------------------------------------------------------------
video.html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>201812633</title>
    <style>
        * 
        { 
            margin: 0; padding: 0; 
        }
        .container
        {
            margin: 0 auto;
            width: 1080px;
            margin-bottom: 8px;
            overflow: hidden;
        }
        .container > audio
        {
            float: right;
        }
        body
        {
            background-image: url("backmokoko.gif");
            width: 100%;
            background-repeat: repeat;
            animation: body 5.2s linear infinite;
        }
        @keyframes body
        {
            100% {background-position: 360px -360px;}
        }
        #top
        {
            position: relative;
            border-radius: 10px;
            width: 1080px;
            height: 500px;
            overflow: hidden;
        }
        #top > iframe
        {
            position: absolute;
            bottom: 50px;
            right: 25%;
            width: 500px;
            height: 250px;
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            border-radius: 10px;
            z-index: 10;
        }
        #menu
        {
            position: absolute;
            left: 20px;
            top: 50px;
            width: 1000px;
            background: rgba(0, 0, 0, 0.596);
            text-align: center;
            z-index: 10;
            border-radius: 10px;
            padding-left: 20px;
            border: 1px solid white;
        }
        #menu > a > li
        {
            
            padding: 8px 10px;
            float: left;
            list-style-type: none;
            padding-left: 115px;
            font-size: 200%;
            font-family: fantasy;
            text-align: center;
            color: white;
            
        }
        #menu > a > li:hover
        {
            color: rgba(185, 167, 167, 0.733);
        }
        #middle
        {
            overflow: hidden;
            padding-bottom: 50px;
        }
        #left
        {
            float: left; 
            height: 300px; 
            width:  529px; 
            background: rgba(255, 255, 255, 0.514);
            background-size: cover;
            border-radius: 10px;
            margin-right: 10px;
            filter: drop-shadow(4px 4px 4px rgba(127, 224, 16, 0.534));
        }
        #left p
        {
            margin-top: 15px;
            margin-left: 20px;
            font-size: 170%;
            font-family: fantasy;
            text-align: left;
            margin-top: 20px;
            color: white;
            filter: drop-shadow(4px 4px 4px #000);
            
        }
        #right
        {
            float: right; 
            height: 300px; 
            width:  529px; 
            background: rgba(255, 255, 255, 0.514);
            border-radius: 10px;
            margin-left: 10px;
            filter: drop-shadow(4px 4px 4px #000);
            z-index: 0;
        }
        #right #info
        {
            margin-left: 15px;
            margin-top: 10px;
            
            background-size: cover;
            width: 490px;
            height: 280px;
            border-radius: 10px;
            filter: drop-shadow(4px 4px 4px #000);
            z-index: 1;
        }
        .zoom {
			display:inline-block;
			position: relative;
		}
        @media screen and (max-width: 1000px)
        {
            .container { width: 767px;}
            audio { display: none; }
            #menu { left: 90px; bottom: 3px; width: 580px; height: 60px; }
            #menu > a > li{ padding-left: 25px; }
            #top > iframe { left: 150px; top: 150px; }
            #left { float: none; margin: 20px 130px; }
            #right { float: none; margin: 0 130px; }
        }
        @media screen and (max-width: 800px)
        {
            .container { width: 600px;}
            audio { display: none; }
            #menu { left: 60px; bottom: 3px; width: 490px; height: 60px; }
            #menu > a > li{ padding-left: 8px; }
            #top > iframe { left: 70px; top: 250px; }
            #left { float: none; margin: 20px 50px; }
            #right { float: none; margin: 0 50px; }
        }
        @media screen and (max-width: 650px)
        {
            .container { width: 400px;}
            audio { display: none; }
            #menu { left: 25px; bottom: 3px; font-size: 60%; width: 330px; height: 40px;}
            #top > iframe { left: 15px; top: 250px; width: 370px; }
            #left { float: none; margin: 20px 10px; width: 380px; font-size: 86%; }
            #right { float: none; margin: 0 10px; width: 380px; }
            #right #info { width: 350px; }
        }
    </style>
    <script src="http://code.jquery.com/jquery-latest.min.js"></script>
    <script src="jquery.zoom.js"></script>
    <script>
        $(document).ready(function(){
			$('#info').zoom();
        });
    </script>
</head>
<body>
    <div class="container">
        <audio controls loop autoplay preload= "auto">
            <source src="mokoko_village.mp3" type="audio/mp3">
        </audio>
        <div id="top">
            <ul id="menu">
                <a href="index.html">
                    <li>Main</li>
                </a>
                <a href="introduce.html">
                    <li>Introduce</li>
                </a>
                <a href="character.html">  
                    <li>Character</li>
                </a>
                <a href="video.html">  
                    <li>Video</li>
                </a>
            </ul>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/7PZdsIcETqg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
        </div>
    <div class="container">
        <div id="middle">
            <div id="left">
                <p>로스트아크는 MMORPG의 재미를 느껴보고 싶으신 분께 딱 알맞는 게임입니다!!</p>
                <p>기회가 되시면 올려둔 가이드영상 참고하셔서 시작해보시길 바랍니다.</p>
                <p>인 게임 정보도 올려놨으니 함께 즐겨요!!</p>
            </div>
            <div id="right">
                <div id="info" class="zoom">
                    <img src="character_info.png" width="490" height="350">
                </div>
            </div>
        </div>
    </div>
</body>
</html>