# Baekjoon 
## 단계별 문제

### 1. 빠른 문자열 받기
##### no.15552
```
import sys
a, b, c = map(int, sys.stdin.readline().split())
```
> map() : 리스트의 요소를 지정된 함수로 처리해주는 함수 
> > int형으로 형변환
> input 대신 sys.stdin.readline 사용 가능 (한 줄 단위의 입력 -> 개행(\n) 문자 포함)
> > sys.stdin.readline.rstrip() or int(sys.stdin.readline())
> > 정해진 개수의 정수를 한줄에 입력 sys.stdin.readline().split()

