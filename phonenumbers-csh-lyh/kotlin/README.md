## 1. 이해

- 접두어: 다른 번호의 시작이 되는 것. prefix.
- 접두어보단 길거나 같다(전화번호 중복에 대한 예외는 없음.)
- 배열의 한 전화번호가 다른 전화번호의 접두어가 될 경우 false.
- startsWith를 쓰자.

## 2. 계획

1. 대상 번호를 접두어로 쓰는 번호는 당연히 접두어보다 같거나 길기 때문에
우선 배열을 정렬한다.
2. 그러면 첫번째 요소부터 순차적으로 T.startsWith(첫번째요소) 로 순차탐색하여
단 하나라도 나오면 즉시 false 반환.
3. 모든 요소를 탐색해도 없으면 true.

## 3. 실행

## 4. 반성