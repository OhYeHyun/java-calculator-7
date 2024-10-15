# java-calculator-precourse
### 프리코스 1주차 [오예현]
# 🔆 문자열 덧셈 계산기
입력한 문자열에서 숫자를 추출하여 더하는 계산기를 구현한다.

## ✅ 기능 요구사항
- `,`와 `:`을 구분자로 하여 문자열 전달한다.  
    > `"1,2:3" => 6`

- `//`과 `\n` 사이 `커스텀 구분자` 사용할 수 있다.   
    > `"//;\n1;2;3" => 6` : `;`가 커스텀 구분자로 사용  

- 사용자가 잘못된 값을 입력할 경우 `IllegalArgumentException`을 발생 후 종료된다.  

## ✅ 입출력 요구사항

- 입력 : `구분자`와 `양수`로 구성된 문자열  


- 출력 : `덧셈 결과`


- 실행 결과

    ```
    덧셈할 문자열을 입력해 주세요.
    1,2:3
    결과 : 6
    ```

## ☑️ 구현할 기능 목록

- [ ] 사용자 입력 받는 함수
- [ ] 유효한 입력인지 확인하는 함수
- [ ] 커스텀 구분자가 있는지 확인하는 함수
- [ ] 구분자로 분리하여 숫자 추출하는 함수
- [ ] 출력 형식대로 출력하는 함수

### 학습 정리
10.15 : 깃 커밋 메시지 컨벤션, tdd 개발 방식