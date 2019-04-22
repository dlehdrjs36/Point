# Point

# ![WebApp](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_1.png)


<br><br>
## 프로젝트 주제

포인트 관리 사이트


<br><br>
## 프로젝트 선정 배경

* 많은 소규모 점포에서 현재 종이 쿠폰 발행 시스템을 이용
    - 고객들의 쿠폰 분실 및 관리의 어려움이 발생합니다.
    <br><br>
* 점주들의 효율적인 고객 관리 및 마케팅 부재
    - 기존의 종이 쿠폰 시스템으로는 어떤 연령대의 고객들이 어느 시간대에 자주 가게에 방문하는지 파악할 수 없습니다.


> **본 프로젝트는 위의 기존의 종이 쿠폰 발행 시스템의 한계를 극복을 위한 회원 가입 및 포인트 적립 시스템 구축 프로젝트입니다.**



<br><br>
## 개발 환경

<table>
<tr><td rowspan="5">S/W</td><td>OS</td><td>Windows 7 Home Premium K</td></tr>  
<tr>                        <td>서버</td><td>Apache Tomcat 8.5.32</td></tr>
<tr>                        <td>개발언어</td><td>JAVA 1.8, HTML5, CSS3, JavaScript, Jsp</td></tr>
<tr>                        <td>데이터베이스</td><td>Oracle Database Express Edition 11g Release 2</td></tr>
<tr>                        <td>IDE</td><td>Eclipse Oxygen.3a Release (4.7.3a), SQL Developer</td></tr>
<tr><td rowspan="3">H/W</td><td>프로세스</td><td>Intel(R) Core i5-2500 CPU 3.30GHz</td></tr>  
<tr>                        <td>메모리</td><td>8192MB RAM</td></tr>
<tr>                        <td>보조 기억장치</td><td>HDD 368GB</td></tr>
</table>


<br><br>
## 데모

~~[Link]()~~

<br><br>
## 웹 화면 구성 및 관리자 UI(User Interface) 기능

      - 관리자 로그인 모드를 구성하여, 포인트사이트 관리자 계정으로 접속할 시 사용자들의 포인트 이용 내역을 확인, 포인트 적립, 포인트 사용 할 수 있도록 일반 사용자들과 기능을 분할하여 구성하였다.

      - 회원들의 포인트 사용 이력을 확인 할 수 있도록 포인트 사용관리 페이지를 구성하였고, 사용 이력들을 엑셀파일로 받아 볼 수도 있다.
      
      - 포인트 사용관리 페이지에서는 방대한 회원정보를 쉽게 검색 할 수 있도록 단어 검색을 적용 하여, 관리자의 검색 시간을 줄이고 업무 처리량을 줄였다.

<br><br>
***
### 회원가입
회원가입 화면

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_2.png)


<br><br>
***
### 회원 로그인화면
***
회원 로그인된 화면

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_3.png)


<br><br>
#### 공지사항
관리자가 작성한 공지사항을 확인할 수 있는 화면

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_8.png)


<br><br>
#### 게시글 상세화면
게시글의 구체적인 내용을 확인할 수 있는 화면

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_10.png)


<br><br>
***
### 관리자 로그인화면
***
관리자 로그인된 화면

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_4.png)


<br><br>
#### 포인트 적립
회원의 포인트를 적립시켜주는 화면

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_5.png)


<br><br>
#### 포인트 사용
회원의 포인트를 사용하는 화면

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_6.png)


<br><br>
#### 회원 포인트 확인
회원들의 포인트 보유현황을 확인하는 화면

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_7.png)


<br><br>
#### 회원 포인트 사용이력
회원들의 포인트 사용 이력을 확인하는 화면

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_9.png)


<br><br>
#### 공지사항
관리자는 일반유저와 다르게 공지사항을 작성할 수 있다.

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_11.png)


<br><br>
#### 게시글 상세화면
관리자는 일반유저와 다르게 게시글을 수정,삭제할 수 있다.

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_12.png)


<br><br>
#### 글작성
관리자는 공지사항을 작성할 수 있다.

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_13.png)


<br><br>
***
### 답글달기
***
관리자와 일반유저는 공지사항에 답글을 달 수 있다.

![](https://github.com/dlehdrjs36/Point/blob/master/DemoImage/point_14.png)

<br><br>

## 사용 API

- [주소 검색](https://github.com/daumPostcode/QnA) - 다음 주소 검색
- [WYSIWYG Editor](http://naver.github.io/smarteditor2/) - 네이버 스마트 에디터 2

<br><br>
## 기대효과

회원 관리 적립금 시스템을 도입함으로써 종이 쿠폰의 불편함을 없애고 효율적인 고객 관리 및 마케팅이 가능해집니다. 또한 장기적으로 고객의 재방문율을 높일 수 있을 것으로 기대됩니다.
<br><br>
## 향후 발전 방향

현재는 포인트를 직접 입력하여 사용 및 적립을 시키는 방식이나 향후에는 포스기와 연동하여 제품별로 포인트 퍼센티지를 지정할 수 있도록 할 예정이며 계산시 전화번호를 넣으면 자동으로 적립되도록 기능 개선을 할 예정입니다. 또한 고객이 여러 가게에서 적립한 내역을 한번에 볼 수 있도록 안드로이드 및 IOS 어플리케이션 모바일 웹을 추가할 예정입니다.

<br><br>
## Team

[![오상민](https://dlehdrjs36.github.io/SupportForMe/DemoImages/대체이미지.jpg)](https://github.com/)  | [![박준형](https://dlehdrjs36.github.io/SupportForMe/DemoImages/대체이미지.jpg)](https://github.com/)  | [![이동건](https://dlehdrjs36.github.io/SupportForMe/DemoImages/대체이미지.jpg)](https://github.com/dlehdrjs36)  
---|---|---
[오상민](https://github.com/) |[박준형](https://github.com/) |[이동건](https://github.com/dlehdrjs36) 

<br><br>
## [License](https://github.com/dlehdrjs36/Point/blob/master/LICENSE.md)

MIT ©[dlehdrjs36](https://github.com/dlehdrjs36)
