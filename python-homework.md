# Python Homework

## 1 day

1. string 길이를 리턴하는 함수 `strlen`을 생성하고, 호출하는 코드를 작성해주세요.  

2. 어떤 string의 substring(부분 문자열)을 찾고, substring이 시작하는 index를 찾는 함수를 작성해주세요.  
ex>
```
s = 'hello world'
s의 substring 'world'를 찾으면 w의 index 6을 리턴하는 함수를 작성하면 됩니다.
substring이 존재하지 않는다면 -1을 리턴합니다.
```

3. 위에서 만든 substring을 찾는 함수를 이용해서 `01-class/example.py` 파일에서 **print** 문자열을 찾고, 
**print** 문자열이 있는 경우, 파일의 line number를 출력하는 함수를 작성해주세요. 

## 2 day

**DataManager class 생성**

Push 메소드를 통해 string, int, array ... 모든 타입을 입력받고 순서대로 저장합니다.
Get 메소드는 index를 인자로 받고 특정 index에 데이터가 없을 경우 exception을 raise 합니다.
Pop 메소드는 인자는 없고 가장 최근에 추가된 값을 리턴합니다. 없으면 null을 리턴합니다.
GetAll 메소드는 저장된 모든 값을 리턴합니다.
