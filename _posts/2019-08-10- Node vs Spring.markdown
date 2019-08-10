---
layout: post
title:  "Node.js vs Spring Framework"
date:   2019-08-10 15:10:18
comments: true
---

<br/>

현재 가장 많이 주목받고 있는 프레임워크 Node.js와 Spring

![node](https://user-images.githubusercontent.com/49789734/62819120-ab484800-bb8b-11e9-9eba-e48524448fe1.jpg)![Spring_Framework](https://user-images.githubusercontent.com/49789734/62819121-ab484800-bb8b-11e9-8383-8898fb2ec2e3.png)

강력한 프레임워크를 간단하면서도 쉽게 비교해보자!!

<br/>
<h4>Node.js란? Spring Framework이란?</h4>

<strong>Node.js</strong>

노드는 정의하면 `자바스크립트 프레임워크`이다. 자바스크립트는 프론트엔드 분야에서 주로 활용됐다. 그런데 `노드JS(Node JS)`가 등장하면서 그 용도가 전혀 달라졌다. 노드JS라는 프레임워크 덕분에 자바스크립트로 서버단 기술까지 제어할 수 있게 된 것이다. 2009년 혜성같이 등장한 노드JS는 웹 개발자에게 많은 관심을 받고 있으며, 최근 재단까지 설립되며 기술 개발이 활발히 이뤄지고 있다.
그 밖에 `비동기 프로그램`이라는 장점을 가지고 있고 Express, 여러가지 내장/외장 모듈으로 쉽게 개발할 수 있다.

<strong>Spring Framework</strong>

`자바 플랫폼`을 위한 오픈 소스 애플리케이션 프레임워크로서 간단히 스프링(spring)이라고 한다. 동적인 웹 사이트 개발을 위한 여러 가지 서비스를 제공한다. EJB 기반으로 개발을 하지 않고 POJO(Plain Old Java Object) 기반으로 개발을 하더라도 가볍고, 제어가 가능한 상호 관련이 적은, `AOP(Aspect Oriented Programming. 관점지향 프로그래밍)`을 지원하고, 컨테이너를 통해 라이프사이클을 관리하고, XML 기반으로 컴포넌트를 개발할 수 있도록 지원해주는 프레임워크를 말한다.



<br/>
<br/>

<h4>여러가지 측면의 두언어의 비교</h4>


<strong>접근성</strong>


처음 서버를 공부할때 체감은 비교적 노드가 쉬울것이다. 자바스크립트라는 언어의 특성일 수 도있고 MVC라는 특수한 패턴을 지향하지 않아도 된다는점, Express의 편한 개발환경 등 개발자에게는 더 편하게 다가온다.    

<strong>언어</strong>

두 프레임워크의 가장 큰차이는 결국 `'자바냐? 자바스크립트냐?'`의 차이를 볼 수 있다. 스프링은 자바의 객체지향적 특징인 클래스, 인터페이스를 이용하여 재활용 및 확장성을 높이고 스프링만의 관점지향적 특징도 가지고 있다.
반면에 노드는 스크립트 언어로 비교적 변수선언과 데이터를 다루기 간단하다. 그리고 다른개념이긴 하지만 ECMA7 부터 클래스를 지향하고 있다.   

<strong>장단점</strong>



<table style="border:1px solid black;border-collapse: collapse;">
            <tr>
                <th style ="background:rgb(100, 114, 150); color: #ffffff; border:1px solid black;border-collapse: collapse;">Node</th>
               <th style ="background:rgb(100, 114, 150); color: #ffffff; border:1px solid black;border-collapse: collapse;">Spring</th> 
                <th style ="background:rgb(100, 114, 150); color: #ffffff; border:1px solid black;border-collapse: collapse;">비고</th>   
            </tr>
            <tr>
                <td style=" border:1px solid black;border-collapse: collapse;">Express</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">Springboot</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">쉽게 개발할 수 있도록 제공해주는 환경</td>    
            </tr>
            <tr>
                <td style=" border:1px solid black;border-collapse: collapse;">모듈(npm)</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">메이븐(mvn)</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">라이브러리같은 개념 만들어 놓은 코드를 가지고 쉽게 쓸수 있음</td>    
            </tr>
                <tr>
                <td style=" border:1px solid black;border-collapse: collapse;">V8엔진 비동기처리 스프링보다 빠르다.</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">복잡한 어플리케이션 구조를 구성 및 설계 가능</td>  
                <td style=" border:1px solid black;border-collapse: collapse;"></td>    
            </tr>
             </tr>
                <tr>
                <td style=" border:1px solid black;border-collapse: collapse;">생산성이 높다.</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">확장성, 재활용성 등의 장점을 가진다.</td>  
                <td style=" border:1px solid black;border-collapse: collapse;"></td>    
            </tr>
             <tr>
                <td style=" border:1px solid black;border-collapse: collapse;">싱글스레드 기반</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">멀티스레드 기반.</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">노드의 가장 큰 단점</td>    
            </tr>
             <tr>
                <td style=" border:1px solid black;border-collapse: collapse;">진입 장벽 낮음</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">설정이 복잡함</td>  
                <td style=" border:1px solid black;border-collapse: collapse;"></td>    
            </tr>
              <tr>
                <td style=" border:1px solid black;border-collapse: collapse;">ECMA기반의 자바스크립트</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">자바의 유료화(?)</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">코틀린으로 대체 가능</td>    
            </tr>
             <tr>
                <td style=" border:1px solid black;border-collapse: collapse;">MVC 패턴, ORM(JPA)</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">sequalize 모듈</td>  
                <td style=" border:1px solid black;border-collapse: collapse;">자바스크립트도 sequalize모듈을 이용해서 MVC패턴을 낼 수 있다.</td>    
            </tr>
         
         
</table>

<br/>
<br/>

<strong>마무리</strong>

http://www.techempower.com/benchmarks/


노드는 성능은 스프링보다 3배이상의 성능을 보여주고 있다. 하지만 싱글스레드라는 단점때문에 노드는 대규모 프로젝트나 게임서버 보다는 Restful-Api, 채팅, Push서버에 적합하다. 그리고 노드의 단일스레드의 문제인지는 모르지만 한국은 많은 회사에서 스프링을 쓰는 것 같다. 실제로 대한민국 전자정부 표준 프레임워크의 기반 기술이다.
그래도 모바일 게임회사에서도 노드를 쓰는곳도 있고 MSA를 사용해서 서비스별 다른 프레임워크를 사용하고 있기 때문에 당연한 말이지만 목적에 맞게 사용하는것이 중요한 것 같다. 



