# crackme 0x01 ~ 0x03
## crackme 0x01

  * 1. call의 scanf에서 입력을 10진수로!! 
  
  <img src = "https://github.com/adakim3297/day1/blob/main/0x01%20-1.png?raw=true" width="500" height="150"/> 


  * 2. p/d를 통해 0x149의 값을 구한후 
  비번으로파악 
  
  <img src = "https://github.com/adakim3297/day1/blob/main/0x01%20-2.png?raw=true"
 width="200" height="100"/> 


  * 3. password : 5274
  
  <img src = "https://github.com/adakim3297/day1/blob/main/0x01%20-3.png?raw=true"
 width="400" height="100"/> 


 
 

## crackme 0x02

  * 1. call의 scanf에서 입력을 10진수로!! 주소 0xffffd6434 기억!!!
  
  <img src = "https://github.com/adakim3297/day1/blob/main/0x02-1.png?raw=true"
 width="450" height="100"/> 
<img src = "https://github.com/adakim3297/day1/blob/main/0x02%20-2.png?raw=true"
 width="450" height="100"/> 


  * 2. ebp -4주소 eax저장,,,
  
  <img src = "https://github.com/adakim3297/day1/blob/main/0x02%20-3.png?raw=true"
 width="400" height="60"/> 


  * 3. ebp - 0xc에 0x00052b24있음 p/d를 이용해 password 구함
  
  <img src = "https://github.com/adakim3297/day1/blob/main/0x02%20-4.png?raw=true"
 width="500" height="150"/> 


  * password : 338724 
  
  <img src = "https://github.com/adakim3297/day1/blob/main/0x02%20-5.png?raw=true"
 width="500" height="110"/> 





## crackme 0x03
  * 1. call의 scanf에서 입력을 10진수로!! 주소 0xffffd6434 기억!!!
  
  <img src = "https://github.com/adakim3297/day1/blob/main/0x03%20-1.png?raw=true"
 width="450" height="110"/> 
 <img src = "https://github.com/adakim3297/day1/blob/main/0x03%20-2.png?raw=true"
 width="450" height="110"/> 


   * 2. test 함수 파라미터 : 입력, 0x52b24, 0xf7ffd000, 0xf7e01e09 그래서 si를 이용해 test 함수 안으로 들어가본다!
  
  <img src = "https://github.com/adakim3297/day1/blob/main/0x03%20-3.png?raw=true"
 width="450" height="110"/> 
<img src = "https://github.com/adakim3297/day1/blob/main/0x03%20-4.png?raw=true"
 width="450" height="140"/> 

   * 3. password : 338724 
  
  <img src = "https://github.com/adakim3297/day1/blob/main/0x03%20-5.png?raw=true"
 width="500" height="160"/> 
 *** 100% 이해가 안됨...