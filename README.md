# php_Basic
>### 서버측 언어를 사용하는 이유
- CGI(Common Gateway Interface)

>### 숫자와 문자
- var_dump : 변수형을 출력해 주는 Fuc
- 문자 문자 연결 : .

>### 변수
```
<html>
  <body>
    <?php
      $a=1;
      echo $a+1; #2
      echo "<br />";
      $a=2;
      print $a+1; #3
    ?>
  </body>
</html>
```

>### 비교
- === vs == : ===는 좌항과 우항이 정확하게 같다는 의미다. ==와의 차이점은 ==이 형변환의 결과를 비교 하지만, ===는 양쪽 항이 데이터 형식까지 정확하게 동일해야 같은 것으로 인정한다는 점이다. 형변환이란 PHP가 코딩의 편의성을 위해서 맥락에 따라서 알아서 데이터의 형식을 변환해주는 것을 의미한다. 이에 대한 자세한 내용은 후속 수업을 통해서 살펴볼 예정이다. 아래의 예제를 보자.
```
echo "1 == '1' : ";
var_dump(1 == '1');
echo "<br />1 === '1' : ";
var_dump(1 === '1');
```

>### 입출력 그리고  폼과 HTTP
