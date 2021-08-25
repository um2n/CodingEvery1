# DB (Data Base)
_use mySQL_
<br>
<br>

***
<br>

##  <b>[설치]</b>
### - bitnami wamp
<br>
cmd -> C:\Bitnami\wampstack -7.4.22-0\mysql\bin <br>
my sql -uroot -p <br>
password : _______ <br><br>


하면 된다는데 현재는 bitnami wamp가 mysql이 아닌 mariadb가 자동으로 깔려서 ariadb로 연결된다. mysql이랑 똑같아서 그냥 하면 된다는데 괜히 찜찜해서 따로 mysql 다운 받아서 하고 있는데... <font color="red" ><b>Access denied for user 'root'@'localhost' (using password: YES)</font></b> 이딴 오류가 난다.
<br><br>

_검색해보면 비번이 틀려서 그렇다는데,, 메모장 bin에 있는 자동으로 만들어진 비번을 쳐도 저런다. 나는 애초에 비번을 설정한 적이 없는데.._
<br><br>
_그리고 내가 bitnami를 깔았던 적이 있나봐.. apache 할 때 깔았나.. 노트북에 뭐가 깔려있는게 엄청 많은데 다음에 쓸지 안 쓸지를 몰라서 지우지도 못하는 중_


    # mysql 설치 방법

     1. https://dev.mysql.com/downloads/mysql/ 에서 community server 설치 후 압축 해제
     2. 관리자 모드로 cmd 켜서 zip파일 있는 폴더 경로로 이동 (복붙)
     3. cd bin
     4. ~bin > mysqld --initialize
     5. 'data' 폴더 생긴거 확인
     6. ~bin > mysql --install
     7. mysqld start
     8. 'data' 폴더에 '컴퓨터명.err' 파일 생긴거 확인
     9. 파일 들어가서 비번 복사
     10. ~bin> mysql -u root -p
     11. 비번 붙여넣기

_하면 돼야하는데 나는 에러가 뜬다고... 낮에 이거 하다가 머리 깨질 것 같아서 한 숨 잤다. 어제는 깃허브 branch가 master에서 main으로 바뀌는 바람에 엉키고 엉켜서 그거 해결한다고 쩔쩔매다가 머리 아팠고..._
