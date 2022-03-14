# jsp_3 : 계산

![image](https://user-images.githubusercontent.com/37132897/158107784-8c741dc8-3626-4ae8-b2e9-43d27bad2ad9.png)

- 덧셈 : x(3) + y(5) = 8
- 뺄셈 : x(3) - y(5) = -2
- 나눗셈 : y(5) / x(3) = 1.666666666~
- 나머지 : y(5) % x(3) = 2
- 곱셈 : x(3) * y(5) = 15
- 제곱 : x(3)**y(5) 3의 5제곱 = 243
- x++; 로 1이 증가해서 x=3에서 4가 되고, y--; 로 1이 감소해서 y는 4가 된다. 그리고, x *= 3 = 4*3= 12 로, x=12, y=4 가 된다. 

     // 변수
     
     var x, y, z;
     
      x = 3;
      
      y = 5;
      
      z = 7;
      
     // 변수 이용한 연산 
     
      document.write(x + y);
      
      document.write("<br>");
      
      document.write(x - y);
      
      document.write("<br>");
      
      document.write(y / x);
      
      document.write("<br>");
      
      document.write(y % x);
      
      document.write("<br>"); 
           
      document.write(x * y);
      
      document.write("<br>");
      
      
      document.write(x ** y); // 제곱
      
      document.write("<br>");
      
      x++; // x 를 하나 증가, x = 4
      
      y--; // y 를 하나 감소, y = 4
      
      x *= 3; // x = x*3, 4*3 = 12

      document.write("x는 : ", x, "<br>y는 : ", y); // x = 12, y = 4 출력
      
      document.write("<br>");
