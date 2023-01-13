# Notepad
메모장 프로그램입니다.

# 로직

1. 메뉴 출력
  - 메뉴에 없는 번호 입력시 예외처리
  
2. 메모 파일 생성
  - 사용자로부터 파일 이름 입력받기 
  - 메모 내용 작성
  - 빈 줄 엔터 시 작성 종료
  
3. 메모 읽기
  - 경로/파일 이름.txt로 검색
  
4. 종료

# 구현 결과

```
"C:\Program Files\Java\jdk-11.0.16.1\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.1\lib\idea_rt.jar=57965:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.1\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\catsp\Downloads\Memopad\out\production\Notepade Notepade
원하는 작업 번호를 입력해주세요.
1. 메모 읽기
2. 새 메모
3. 종료
2
저장할 메모 파일 명을 입력하세요.
memo01.txt
메모할 문자열을 입력하세요.
종료 : 빈 줄에서 엔터 입력
안녕하세요. 메모장 프로그램입니다.

원하는 작업 번호를 입력해주세요.
1. 메모 읽기
2. 새 메모
3. 종료
1
메모 파일명을 입력하세요.
memo01.txt
memo01.txt의 내용을 출력합니다.
안녕하세요. 메모장 프로그램입니다.


원하는 작업 번호를 입력해주세요.
1. 메모 읽기
2. 새 메모
3. 종료
3
프로그램을 종료합니다.

Process finished with exit code 0
