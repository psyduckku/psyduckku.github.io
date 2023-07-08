---
published: false
---
---
layout: single
title: "오늘의 정리"
---

#오늘의 정리
#2 thymeleaf   
1. thymeleaf
[thymeleaf 위치]   
resources/templates/여기에.html   
- html파일 상단에 thymeleaf 주소 입력   
- <html xmlns:th="http://www.thymeleaf.org">   
변수명 : ${variable}   
  syntax : <p th:text=" '안녕하시오. 나는 '+{name}+'이라고 하오' ">여긴그냥안보임.다만 값없을때나옴</p> 

#2 깃블로그   
  
#2 @ResponseBody   
  ResponseBody는 html 태그 없이 request요청시 body에 있는 내용을 그대로 뷰에 전달함.   
  그래서 뷰 내용에 보면 html태그 뼈대 없이 data만 표시됨.   
  return "<html> ~~ name~~ </html>" 해서 리턴해줄 수 있겠지만   
  언젠간 쓸 일이 있겠지?   
  
  