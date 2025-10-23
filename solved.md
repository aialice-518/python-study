# 문제 제목: 합

## 문제 정보
- **출처:** 
- **난이도: Medium

## 문제 설명
n이 주어졌을 때, 1부터 n까지 합을 구하는 프로그램을 작성하시오

## 해결 과정
입력값을 넣어야 하고 1부터 n까지 합을 구하는 코드 알아야함

### 접근 방법
input 을 사용하되 input은 문자열만 취급하니 int로 숫자열 만들고
for반복문, range로 더하가

## 코드

n = int(input())
print(sum(range(1, n + 1)))

n = int(input())
total = 0
for i in range(1, n + 1):
    total += i
print(total)
