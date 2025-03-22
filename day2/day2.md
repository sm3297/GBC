Buffer Overflow
# bof1
gets 함수나 strcpy함수는 입력받은 값을 버퍼에 저장할때 데이터 길이와 상관없이 stack에 복사한다.

## Buffer Overflow 예시
<img src=https://www.imperva.com/learn/wp-content/uploads/sites/13/2018/01/buffer-overflow.png width ="400" height="120"/>


#bof1.c의 코드 내용

* 코드내의 innocent와 key의 값 중점
* key값이 0x61616161
* call에서 gets 함수를 찾는다


<과정 1>
1. 코드를 보고 분석한다
![img](https://github.com/adakim3297/bof1/blob/main/bof1.c%20%EC%BD%94%EB%93%9C%20%EB%82%B4%EC%9A%A9.png?raw=true)


<과정 2>

<img src= "https://github.com/adakim3297/day2/blob/main/bof1%20-3.png?raw=true" width ="500" height="500"/>

<img src= "https://github.com/adakim3297/day2/blob/main/bof1-%204.png?raw=true" width ="500" height="450"/>

<img src= "https://github.com/adakim3297/day2/blob/main/bof1-6.png?raw=true" width ="400" height="120"/>

2. buf & innocent의 거리를 gdb를 통해서 알아내고 bof1인경우에는 innocent의 주소가 rbp-0x4임을 알 수 있으므로 140으로 비번을 구한다.
<img src= "https://github.com/adakim3297/day2/blob/main/bof1-7.png?raw=true" width ="400" height="120"/>


# bof2
1. 코드를 보고 분석한다
<img src= "https://github.com/adakim3297/day2/blob/main/bof2-1.png?raw=true" width ="400" height="500"/>

2. bof1와 같이 strcpy와 get에 초점으로 gdb를 실핸한후 비번을 구한다.
<img src= "https://github.com/adakim3297/day2/blob/main/bof2-2.png?raw=true" width ="400" height="120"/>


# bof3
1. 코드를 보고 분석한다
<img src= "https://github.com/adakim3297/day2/blob/main/bof3-1.png?raw=true" width ="400" height="500"/>

2. bof1와 같이 strcpy와 get에 초점으로 gdb를 실핸한후 비번을 구한다.
<img src= "https://github.com/adakim3297/day2/blob/main/bof3-2.png?raw=true" width ="400" height="120"/>

# bof 4
1. 코드를 보고 분석한다
<img src= "https://github.com/adakim3297/day2/blob/main/bof4-1.png?raw=true" width ="400" height="500"/>

2. bof1와 같이 strcpy와 get에 초점으로 gdb를 실핸한후 비번을 구한다.
<img src= "https://github.com/adakim3297/day2/blob/main/bof4-2.png?raw=true" width ="400" height="120"/>






** 아직 100% 이해를 못함...**