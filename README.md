# Terraform을 이용한 ncloud 서버 생성방법(가이드)
-------------------------------------------

1. 네이버클라우드 회원가입 및 무료 크레딧 등록<br>
- 네이버클라우드 : <https://www.ncloud.com/><br>
- 무료크레딧등록 : <https://blog.naver.com/n_cloudplatform/222803782884><br><br><br>


2. 네이버클라우드 인증키 생성<br>
- 로그인 후 마이페이지 -> 인증키 관리 : <https://www.ncloud.com/mypage/manage/authkey><br>
- 신규 API 인증키 생성<br>
- Access Key ID 와 Secret Key 메모장 에 기억 해두기<br><br><br>

3. ncloud.tf 파일 만들기<br>
- vscode로 새로운 폴더를 만든후 테라폼 파일인 ncloud.tf파일을 만들어 줍니다 <br>
- github 에 올라와있는 ncloud.tf 코드부분을 복사해 붙여넣습니다.<br>
- ncloud.tf 코드부분에서  Access Key ID 와 Secret Key를  전에 메모해둔 코드로 변경해줍니다.<br><br><br>

4. 리눅스 우분투 wsl 설치 <br>
- vscode에서 (ctrl + `)키를 눌러 터미널 창을 띄웁니다<br>
- 리눅스 우분투 wsl 설치 : https://tech.cloud.nongshim.co.kr/2023/11/14/windows%EC%97%90%EC%84%9C-wsllinux-%EA%B0%9C%EB%B0%9C-%ED%99%98%EA%B2%BD-%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0/<br><br><br>
  

5. terraform 실행
- vscode 에서 터미널 창을 띄운후 bash를 입력합니다
- 테라폼 파일을 만든 경로로 들어가 줍니다 ex) root@DESKTOP:/mnt/c/terraform
-  terraform init 명령어를 실행해줍니다
-  terraform plan 명령어를 실행해 줍니다
-  terraform apply 명령어를 실행해줍니다
