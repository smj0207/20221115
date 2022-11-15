# 산업기사 백신프로그램 

## 실행화면

![image](https://user-images.githubusercontent.com/97486300/201839772-4f903a1a-ddfc-4ff7-86b5-153202bb5096.png)

유효성검사가 걸려있어 텍스트 박스안에 값이 들어가지 않으면 해당 메세지가 표시된다

![image](https://user-images.githubusercontent.com/97486300/201839950-2ddc1d88-b36e-4d54-9cc7-819f294b97cd.png)

## 아래는 유효성검사에 필요한 코드이다

![image](https://user-images.githubusercontent.com/97486300/201840917-62af0a00-75d1-441b-ae70-da39e2879b46.png)

## 이제 예약을 했다면 예약 리스트를 확인해보도록 하자

실행화면이다

![image](https://user-images.githubusercontent.com/97486300/201841225-233756e9-147f-4a32-b238-cd42cbf1e714.png)

스트링 형식의 문자열을 생성하여 받아준다


![image](https://user-images.githubusercontent.com/97486300/201841675-e157aaf7-145d-47d6-a3ee-f330d17e7a3e.png)


다음은 쿼리문입니다 외부조인으로 필요한 회원정보를 테이블 가져와주는 쿼리문입니다


![image](https://user-images.githubusercontent.com/97486300/201842895-37a45239-65b5-4995-9ed5-ef98a49975b9.png)

또한 아래 코드로 받아온 회원정보 보여줍니다 

![image](https://user-images.githubusercontent.com/97486300/201843491-b3cd5464-721e-4bfb-bcde-2f7c2813ca21.png)

if문은 번호를 입력받은후 출력시켜줍니다<br>
그리고 else문을 사용해 테이블에 있는 정보와 일치하지 않는 번호는 걸러냅니다
