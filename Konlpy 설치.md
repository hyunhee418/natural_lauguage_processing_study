



# Konlpy 설치

## Java 설치

https://java.com/ko/download/

![1575944566931](./images/1575944566931.png)

## JDK 설치

1. 설치 사이트 singin and login

https://www.oracle.com/technetwork/java/javase/downloads/index.html

![1575944632979](./images/1575944632979.png)

2. Java SE Development Kit 8 Downloads 선택

![1575944831814](./images/1575944831814.png)

3. Accept License Agreement로 전환 후 맞는 Os 선택 후 다운

![1575944931780](./images/1575944931780.png)

![1575949389727](./images/1575949389727.png)

4. 다운 받은 파일을 작업할 폴더로 이동

5. Java 환경 설정

   cmd에서 jdk version 확인

   ![1575950307589](./images/1575950307589.png)

   시스템 환경
   ![1575949676791](./images/1575949676791.png)

   

   환경 변수 클릭

   

![1575949733211](./images/1575949733211.png)



​	시스템 변수 내 새로 만들기

![1575949776385](./images/1575949776385.png)

​	새 시스템의 변수 이름은 JAVA_HOME, 변수 값으로는 경로 
​	시스템의 변수 값에 C:\Program Files\Java\jdk{앞서 찾았던 version}

​	![1575950403488](./images/1575950403488.png)

​	다시 환경 변수 중 시스템 변수에서 Path를 선택

![1575950954532](./images/1575950954532.png)



​	Path에서 새로 만들기로 %JAVA_HOME%\bin을 추가 후 반드시 맨 위로 올리기

![1575951081697](./images/1575951081697.png)

​	다시 cmd에서 제대로 했는 지 version을 확인

​	![1575951246877](./images/1575951246877.png)


6. 작업 폴더로 가서 bash 열기

7. bash에서 아까 다운 받은 JPype 파일을 설치한다.
   

   ![1575951611224](./images/1575951611224.png)
   

8. 설치가 완료되었다면 konlpy를 설치

   ![1575951694337](./images/1575951694337.png)



9. 설치가 되었는 지 확인

   작업 폴더에 가상 환경 만들기


   ![1575951863542](./images/1575951863542.png)

   환경 내 jupyter 설치

   ![1575951973611](./images/1575951973611.png)

   jupyter notebook 실행

   ![1575952008588](./images/1575952008588.png)

   konlpy 내 있는 함수를 사용하며 설치가 되었는 지 확인

   ![1575952093213](./images/1575952093213.png)