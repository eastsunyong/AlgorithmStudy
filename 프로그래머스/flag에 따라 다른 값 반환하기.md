### 문제 설명

- 두 정수 `a`, `b`와 boolean 변수 `flag`가 매개변수로 주어질 때, `flag`가 true면 `a` + `b`를 false면 `a` - `b`를 return 하는 solution 함수를 작성해 주세요.

### 제한사항

- -1,000 ≤ `a`, `b` ≤ 1,000

### 입출력 예

| a | b | flag | result |
| --- | --- | --- | --- |
| -4 | 7 | true | 3 |
| -4 | 7 | false | -11 |

### 초기 코드

```jsx
function solution(a, b, flag) {
    var answer = 0;
    return answer;
}
```

### 풀이 코드

```jsx
const solution = (a,b,flag) =>{
    return flag ? a+b : a-b
}
```