---
layout: single
title: '출력문'
---

[문제 상황] Q2     
IT 기업 호스팅.hd에서는 나만의 도메인을 만들도록 최적 가격 프로모션을 진행하고 있습니 다. 다음의 도메인 생성 규칙을 보고 인터넷 주소를 만드는 프로그램을 작성해 보시오. 

[도메인 생성]   
USER ID : bellflower 
기관 : co  or  ne  re  pe 국가명 : kr cn sg in  io 

[해결 조건]  
user id, 기관, 국가명을 변수로 만들고 각각의 값을 저장한다. 
print 문의 format 형식지정자를 이용하여 출력한다. 
프로그램의 실행으로 나타나는 주소는 출력 결과와 같다. 

~~~ptyhon

user="bellflower"
기관="or"
국가명="kr"
print('http//www.{}.{}.{}'.format(user, 기관, 국가명))

~~~
