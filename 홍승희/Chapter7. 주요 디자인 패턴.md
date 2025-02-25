# Chapter7. 주요 디자인 패턴

> 1. 디자인 패턴이란?     
> 2. 전략(Strategy) 패턴         

</br>

## 목차   

1. [디자인 패턴](#1-디자인-패턴)   
2. [전략 패턴](#2-전략-패턴)    

</br> 

## 1. 디자인 패턴  
- [*디자인 패턴이란*](https://ko.wikipedia.org/wiki/%EB%94%94%EC%9E%90%EC%9D%B8_%ED%8C%A8%ED%84%B4)  

</br>

- 프로그램 개발에서 자주 나타나는 `문제를 해결하기 위한 방법` 중 하나.  
- 유용한 소프트웨어 설계를 `패턴으로 정립`한 것.    
- 자주 사용하는 설계 형태를 정형화해서, 유형별로 `설계 템플릿`을 만들어둔 것.  
                   
</br>

➡️ 재설계를 최소화하면서 요구 사항의 변화를 수용할 수 있는 소프트웨어 설계 패턴.   
             
</br>             
</br>

## 2. 전략 패턴     

### 1) OCP(Open-Closed Principle)  
- 기능을 변경하거나 확장할 수 있으면서,    
- 그 기능을 사용하는 코드는 수정하지 않는다.  
 
</br>

### 2) 전략 패턴

- `OCP를 준수하기 위한` 디자인 패턴.  
            
```text 
"객체들이 할 수 있는 `행위`에 대해 `전략` 클래스를 생성하고,    
유사한 행위들을 캡슐화하는 인터페이스를 정의하여,   
객체의 행위를 동적으로 바꾸고 싶은 경우, 직접 행위를 수정하지 않고 전략을 바꿔주기만 함으로써   
행위를 유연하게 확장하는 방법."   
       
[https://victorydntmd.tistory.com/292]
``` 

</br>

- 다이어그램  
  
- 소스  
C:\Users\20105seunghui\source\study\StrategyPatternTest\StrategyPatternTest   
  
 





            
            
            
