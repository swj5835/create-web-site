# create-web-site
create web site by python

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A-Tag</title>
</head>
<body>
    <a href="https://www.naver.com"target="_blank">네이버</a>
    <a href="https://www.daum.net"target="_self">다음</a><br
    <a href="https://www.google.com>">구글</a>
</body>
</html>




#베이식
<!DOCTYPE html>
<html lang="ko">
<head>
    <title> 제목 글자 </title>>
</head>

<body>
    <h1>제목 글자 h1</h1>
    <h2>제목 글자 h2</h2>
    <h3>제목 글자 h3</h3>
    <h4>제목 글자 h4</h4>
    <h5>제목 글자 h5</h5>
    <h6>제목 글자 h6</h6>
    <hr>
    <p>동해물과 백두산이<i/> 마르고&nbsp;&nbsp; 닳도록 <br/>
    하느님이 보우하사 우리나라만세<br/>
(<b>후렴<b/>)</b>대한민국 화이팅</p>
</body>
</html>


#스타일

<!DOCTYPE html>
<html>
    <head>
        <title>Style</title>
</head>
<body style="background-color: lemonchiffon;">
    <h1 style="background-color: lightblue;">목록 태그</h1>
    <p>나는 p태그 입니다.</p>
    <p style="color: rgb(255, 17, 0); text-align: right;" > 나는 p태그 빨강</p>
    <p style="color: blue">나는 p태그 파랑</p>
    <p style="font-size: 50px;">나는 p태그 큰 글씨</p>
    <p> <del>삭제문자</del></p>
    <p> 이건 <sub>서브스크립트</sub></p>
    <p> 이건 <sup>수퍼스크립트</sup></p>

    
</body>
</html>

##콘텐츠##

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta name="content" content="width=device-width, initial-scale=1.0">
    <h1 style="background-color: rgba(255, 8, 0, 0.486)"> rgb(255,8,0)</h1>
    <h1 style="background-color: rgb(238, 255, 0)"> rgb(238,255,0)</h1>
    <h1 style="background-color: rgb(0, 255, 115)"> rgb(255,8,0)</h1>
    <h1 style="background-color: rgb(195, 0, 255)"> rgb(255,8,0)</h1>
</head>
<body>
    
</body>
</html>



## 과일##

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>순서없는 목록</title>
</head>
<body>
    <h1>좋아하는 과일</h1>
    <ul>
        <li> 포도</li>
        <li> 사과</li>
        <li> 딸기</li>
        <li> 배</li>
    </ul>
    <h1>좋아하는 라면</h1>
    <u1 type="Square">
        <li> 신라면</li>
        <li> 짜파게티</li>
        <li> 비빔면</li>
        <li> 그냥라면</li>
    </u1>
    
</body>
</html>

## 순서 있는 목록

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>순서없는 목록</title>
</head>
<body>
    <h1>좋아하는 과일</h1>
    <ol type="A">
        <li> 포도</li>
        <li> 사과</li>
        <li> 딸기</li>
        <li> 배</li>
    </ol>
    <h1>좋아하는 라면</h1>
    <ol type="a">
        <li> 신라면</li>
        <li> 짜파게티</li>
        <li> 비빔면</li>
        <li> 그냥라면</li>
    </ol>
    
</body>
</html>


##테이블##

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>테이블</title>
    <style>
        table,th,td{
            border: 1px solid black;
            border-collapse: collapse;
        }
        th{
            background-color: #96d4d4;
            border: 1px dotted black;
            border-radius: 10px;
        }
        td{
            background-color: #96acd4;

        }
    </style>
</head>
<body>
    <h1>회사 테이블</h1>
    <table border="1"; border-collapse="border-collapse">
        <tr>
            <th>번호</th>
            <th>이름</th>
            <th>회사명</th>
        </tr>
        <tr>
            <td>1</td>
            <td>홍길동</td>
            <td>삼성전자</td>
        </tr>
        <tr>
            <td>2</td>
            <td>홍길동</td>
            <td>LG전자</td>
        </tr>

    </table>
</body>
</html>



##css class##

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS-Class</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body{background-color: antiquewhite;}
        h1{color: #0000ff;}
        p{color: #ff0000;}
    </style>
</head>
<body>
    <h1>아름다운 강산</h1>
    <p> 하늘은 파랗게 구름은 하얗게</p>
    <pre>하늘은 파랗게 구름은 하얗게
        실바람도 불어와 부품은 내마음
    </pre>


</body>
</html>


##이미지##

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image</title>
</head>
<body>
    <h1>이미지</h1>
    <img src="https://image.idus.com/image/files/da634c3f22414f21ac2bbb9f0b9fa318.jpg" alt="after glow" width="200" height="200"
</body>
</html>

    
    
    ###23-05-09##
    
  <!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        #header{width: 800px; margin:0 auto;
                background: red;}
        #wrap{width: 800px; margin: 0 auto;
              overflow: hidden;}
        #aside{width: 200px; float: left;
            background: green;}
        #content{width: 600px; float: left;
            background: blue;}
    </style>
</head>
<body>
    <div id="header">
        <h1> #header</h1>
    </div>
    <div id="wrap">
        <div id="aside">
            <h1>#aside</h1>
        </div>
        <div id="content">
            <h1>#content</h1>
        </div>
    </div>


</body>
</html>
    
    
 ##좋아하는 과일 색깔 덮기##
    
 <!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .select{color:red;}
    </style>
</head>
<body>
    <h1> 좋아하는 과일</h1>
    <ul>
        <li class=" select"> 사과</li> 
        <li> 포도</li>
        <li class=" select"> 바나나</li>
        <li> 딸기</li>
    
    </ul>
    
</body>
</html>
    결과값::
    ![image](https://user-images.githubusercontent.com/107772468/237007394-96ec7987-c99b-4bbd-be97-267593029581.png)
    
    
 ##2탄##
    
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .select{color:red;}
        .item{ color: blue;}
        .header{ background: yellow;}
        .select2{color: green;}
    </style>
</head>
<body>
    <h1 class="header item"> 과일</h1>
    <ul>
        <li class=" select2"> 사과</li> 
        <li> 포도</li>
        <li class=" select"> 바나나</li>
        <li> 딸기</li>
    
    </ul>
    
</body>
</html>
    
    결과값:
    ![image](https://user-images.githubusercontent.com/107772468/237008051-431e25c5-e749-418c-b4b9-8adbb6c35778.png)
    
### 박스 만들기###
    
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        div{ width: 200px; height: 200px;
        background: red;
        border: 20px solid black;
        margin: 20px;
        padding: 30px;}
    </style>
    <div>
    <h1> 글자 </h1>
    </div>
    
</head>
<body>
    
</body>
</html>
    
결과값:
    ![image](https://user-images.githubusercontent.com/107772468/237022875-d9df87ba-c1b8-4298-b0f0-553aa33b5524.png)

    
    
###박스 안 이름###
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        div{ width: 200px; 
            height: 200px;
            background: red;
            border: 20px solid black;
        margin: 0 auto;
        padding: 30px;
        text-align: center;}
        .box{ 
        Border-width: thick; 
        Border-style: dashed;
        border-color: blue;
        border-radius: 30px 30px 0px 0px;
        text-align: center;
        } 
        </style>
    
    
</head>
<body>
    <div class="box">
        <h1> 장성우 </h1>
        </div>
</body>
</html>

    결과값:![image](https://user-images.githubusercontent.com/107772468/237025562-3d2104b8-5c0d-4415-89bc-c4e5131fc8bd.png)
    
  #### 글자 사이즈 바꾸는 법!!###
    
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
      .a{font-size: 4em;}
      .b{font-size: 32px;}
      .c{font-size: 300%;}
      .d{font-size: large/small;}

        </style>
    
    
</head>
<body>
        <h1> Lorem Ipsam </h1>
        <p class="a"> 글자 </p>
        <p class="b"> 글자 </p>
        <p class="c"> 글자 </p>
        <p class="d"> 글자 </p>
        </div>
</body>
</html>

결과값:![image](https://user-images.githubusercontent.com/107772468/237026938-ca4ed71c-6892-4347-9ca0-9f95c2b9faba.png)


### 사이트 들어가기###
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .f_bold {font-weight: bold;}
        .f_italic{font-style: italic;}
        .f_big{font-size: 2em;}
        .f_center{text-align: center;}
        .bottom{width: 160px; height: 80px;
            background-color: yellow;
            border: 10px solid black;
            border-radius: 30px;
            box-shadow: 5px 5px 5px #a9a9a9;
        }
        .button>a{ display: block;
        line-height: 80px;}
    </style>
</head>
<body>
    <div class="button f_bold f_italic f_big f_center">
        <a href="https://github.com/swj5835/create-web-site/blob/main/README.md"> click</a>
    </div>
      
</body>
</html>

###박스???###

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .box{ width: 200px; height: 200px; background-color: red; margin: 10px; padding:10px; float:left; font-size: 3em;}
    </style>
</head>
<body>
    <div class="box">1</div>
    <div class="box">2</div>

    
</body>
</html>

결과값:![image](https://user-images.githubusercontent.com/107772468/237033169-1811dab6-a05c-4dc8-a92f-6702023d9557.png)



