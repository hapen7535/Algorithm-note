# Python 입력
  
  
### input() 사용  
- 내장함수
- 입력받은 내용의 개행 문자(newline)를 제거 후, 문자열로 변환하고 return

### sys.stdin 사용
- File Object
- 사용자 입력 Buffer 생성 후, Buffer에서 입력을 읽어낸다
- 개행 문자가 제거되지 않는다

##### sys.stdin.readline()
- File Object의 메소드 중 하나
- 입력을 읽을 때 한 번에 한 줄을 읽는다
- 개행 문자(/n)가 포함된다

##### sys.stdin.readlines()
- File Object의 메소드 중 하나
- 입력을 읽을 때 파일 전체를 읽어, 리스트로 만들어준다
- 개행 문자가 역시 포함된다

##### sys.stdin.read()
- File Object의 메소드 중 하나
- 파일 전체를 하나의 문자열로 만들어준다
  
