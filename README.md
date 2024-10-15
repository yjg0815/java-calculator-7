# java-calculator-precourse

`long` 범위  : -**9223372036854775808 ~ 9223372036854775807**

** 

“문자열에서 숫자를 추출” 하여 더하는 계산기를 구현하라고 하였으므로, long 넘어가는 연산은 예외처리 

**

1. enterInput : 유저 인풋 받기 
2. splitString : 유저 인풋에서 구분자 분리 
    a. hasCustomSpliter : 지정 구분자 있는지 체크
    b. isValidSpliter :  정해지지 않은 구분자 있는지 체크 
3. changeStringToNumber : 숫자 변환
    a. isNegativeNumber :  음수 입력 있는지 체크 
    b. isBigInteger : long type 넘어가는 입력 체크 
4. sumNumber : 숫자 더하기 
5. ouputResult : 결과 출력하기 
