---
layout: post
title:  "Elastic Search는 무엇인가??"
date:   2019-06-15 14:22:22
comments: true
---

<br/>

수 많은 정보들을 효율적으로 검색할 수 있는, 
Stackoverflow, Github에서도 사용되고 있는 

<strong>엘라스틱서치(Elastic Search)</strong>에 대해 알아보자!!



<br/>
<h4>엘라스틱서치(Elastic Search)란?</h4>


데이터과학이 발전하면서 함께 성장하고 있는 기술이 있었으니, 바로 오픈소스 기술이다. 엘라스틱서치는 `루씬(Lucene)을 기반으로 한 오픈소스 검색 엔진`으로 자바를 이용하여 개발되었으며, RESTful API를 제공하는 것이 특징이다. 또한 검색 분야에서 큰 주목을 받고 있으며, 최근 들어 오픈소스 스타트업으로서 성과도 내고 있어 영향력이 커지고 있다.




![ela](https://user-images.githubusercontent.com/49789734/62819513-36780c80-bb91-11e9-92dd-dd332db0735e.png)

<br/>
<h4>왜 엘라스틱서치(Elastic Search)을 쓰는가??</h4>

엘라스틱서치의 가장 큰 장점은 바로, ES 기반 머신러닝 + 딥러닝 

<br/>

<strong>자세히 들어가보면</strong> !! 

<br/>

<strong>첫번째 구조적 특징</strong> 
RDMS와 다른 NOSQL의 구조로 확장성이 매우 좋다. 노드라고 불리는 프로세스 단위로 구성되어 있는데, 확장이 필요하다면 그저 새 노드를 실행하고 기존의 노드와 연결하여 scale-out이 매우 간단하다.

<strong>두번째 안전성</strong> 
하드웨어 오류에 대비한 네트워크 분리, ES는 발생 가능한 오류를 감지하여 클러스터와 기업 데이터를 안전하게 보호한다.

<strong>세번째 간단한 환경설정 </strong> 
엘라스틱서치는 오픈소스이면서 설치 방법과 사용도 간단하다

<strong>네번째 검색 과정</strong> 
데이터를 저장한 뒤 검색하기 위해 재실행과 같은 과정이 필요없음, 인덱싱만 끝나면 검색이 가능


<strong>다섯번째 Restful</strong> 
Restful API를 제공하는 것이 특징이다. 입출력에 JSON을 사용하여 이용이 편리하다.


<br/>
 <h4>관련 추천 블로그</h4>

 한국어로 되어있는 블로그 중 가장 잘 정리되었다고 생각한다.

 여러가지 예시로 쉽게쉽게 정보를 얻을 수 있는 블로그.

 [https://blog.naver.com/sundooedu/221503687297](https://blog.naver.com/sundooedu/221503687297)

윈도우 기반의 엘라스틱 서치 실습과정이 잘나온 블로그.

[https://blog.naver.com/rickman2/221479453221](https://blog.naver.com/rickman2/221479453221)
