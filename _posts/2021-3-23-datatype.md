---
layout: single
title: '데이터형'
---

[문제 상황] 
마이크로스코프 연구실에서는 전염병 바이러스 백신을 개발하고 있습니다. 연구원 코난은 매 일 세균의 번식량을 조사하고 있습니다. 세균의 개체수가 증가함에 따라 정확한 계산이 어려 워서 금일의 측정한 개체수과 전일 측정한 개체수를 차이를 계산하여 번식량을 알려주는 프로 그램을 작성하려고 합니다. 

~~~python
x=float(input('전일 개채수: '))
y=float(input('금일 개채수: '))
a=int(y-x)
print('번식량: {}'.format(a))
~~~
