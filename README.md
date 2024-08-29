<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./webAppProj/css/reset.css">
    <link rel="stylesheet" href="./webAppProj/css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bxslider/4.2.17/jquery.bxslider.css" integrity="sha512-rV4fiystTwIvs71MLqeLbKbzosmgDS7VU5Xqk1IwFitAM+Aa9x/8Xil4CW+9DjOvVle2iqg4Ncagsbgu2MWxKQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100..900;1,100..900&display=swap');
    </style>    
</head>
<body>
    <header class="hd">
        <div class="topcontainer menuWrap">
            <h1 class="logo">넷마블문화재단</h1>
            <nav class="topnavbar">
                <ul>
                    <li><a href="#">재단소개</a></li>
                    <li><a href="#">재단활동</a></li>
                    <li><a href="#">재단소식</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="visual">
        <ul class="slide">
            <li class="item st1">
                <div class = "slidetextWrap">
                    <div class="textWrap">
                        <div class="slideTitle">견학프로그램</div>
                        <div class="slidetext">나의 게임산업 탐방기</div>
                    </div>
                </div>
            </li>
            <li class="item st2">
                <div class = "slidetextWrap">
                    <div class="textWrap">
                        <div class="slideTitle">견학프로그램</div>
                        <div class="slidetext">나의 게임산업 탐방기</div>
                    </div>
                </div>
            </li>
            <li class="item st3">
                <div class = "slidetextWrap">
                    <div class="textWrap">
                        <div class="slideTitle">견학프로그램</div>
                        <div class="slidetext">나의 게임산업 탐방기</div>
                    </div>
                </div>
            </li>
        </ul>
    </div>
    <div class="secondtabTitle">
        <div class="titleText">문화를 만들고 인재를 키우고<p>마음을 나눕니다</p></div>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js" integrity="sha512-v2CJ7UaYy4JwqLDIrZUI/4hqeoQieOmAZNXBeQyjo21dadnwR+8ZaIJVT8EE2iyI61OV8e6M8PP2/4hpQINQ/g==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/bxslider/4.2.17/jquery.bxslider.min.js" integrity="sha512-LaBO0tZh1+6Ebk+EnHt/WsGM0UnmkCXfQ1rfhGmpa5MXUdslNuSSELBRcteHKz4k4ny+Op10Ax2fPoTNq+VcUg==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <script>
        $(".slide").bxSlider({
        auto : true
    });
    </script>
</body>
</html>
