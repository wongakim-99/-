# 자료구조 & 알고리즘 :dart:

## :sparkles: 자료구조란? 

### 자료구조란 개발자가 데이터를 효율적으로 사용할 수 있도록 정리하는 방법을 말한다. 각각의 자료구조에는 장단점이 있으므로 어떤 자료구조가 최선일지는 해결하고자 하는 문제의 종류와 어떤 부분을 우선적으로 최적화할지에 따라 달라질 수 있다. 
### 자료구조는 데이터에 대한 접근 및 조작을 효율적으로 수행하기 위해 사용된다. 몇 가지 일반적인 자료구조에는 배열, 연결 리스트, 스택, 큐, 트리, 그래프 등이 있다.

<br/>

## 자료구조의 분류

### 자료구조는 크게, 구현과 형태 따라 나뉜다.

- #### 구현에 따른 자료구조
  |종류|설명|
  |:------:|:---:|
  |배열|가장 일반적인 구조이다. 메모리 상에 같은 타입의 자료가 연속적으로 저장된다. 자료값을 나타내는 가장 작은 단위가 자료를 다루는 단위이다.|
  |튜플|둘 이상의 자료형을 묶음으로 다루는 구조이다.|
  |연결 리스트	|노드를 단위로 한다. 노드는 자료와 다음 노드를 가리키는 참조값으로 구성되어 있다. 노드가 다음 노드로 아무것도 가리키지 않으면 리스트의 끝이다.|
  |원형 연결 리스트|각 노드는 다음 노드를 가리키고, 마지막 노드가 처음 노드를 가리키는 연결 리스트이다.|
  |이중 연결 리스트|각 노드는 이전 노드와 다음 노드를 가리키는 참조값으로 구성된다. 처음 노드의 이전 노드와 마지막 노드의 다음 노드는 없다.|
  |환형 이중 연결 리스트|처음 노드가 이전 노드로 마지막 노드를 가리키고, 마지막 노드가 다음 노드로 처음 노드를 가리키는 이중 연결 리스트이다.|
  |해시 테이블	|개체가 해시값에 따라 인덱싱된다.|

- #### 형태에 따른 자료구조
  |종류|구분|설명|
  |:------------:|:---:|:---:|
  |선형 구조|스택|스택 자료구조에 먼저 저장된 것이 꺼내어 쓸 때는 제일 나중에 나온다. 반대로, 가장 최근에 저장된 것이 꺼내어 쓸 때는 제일 먼저 나온다. 만약, 자료들의 나열 순서를 바꾸고 싶다면 스택에 집어 넣었다가 꺼내면 역순으로 바뀐다.|
  |선형 구조	|큐|스택과- 반대로 큐 자료구조에 먼저 저장된 것이 제일 먼저 나온다. 반대로, 가장 나중에 저장된 것이 꺼내어 쓸 때는 가장 나중에 나온다.|
  |선형 구조	|큐(환형 큐)|한정된 길이 안에서 부수적인 작업 없이 읽고 쓰기를 할 수 있는 큐이다.|
  |선형 구조|덱|양쪽에서 넣기와 빼기를 할 수 있는 일반화된 선형 구조이다.|
  |비선형 구조|그래프|꼭짓점과 꼭짓점을 잇는 변으로 구성된다.|
  |비선형 구조|그래프(유향 그래프,무향 그래프)|변이 방향성을 갖는지 갖지 않는지에 따른 그래프의 분류이다. 무향 그래프의 경우, 순환이 없는 연결 그래프를 뜻한다. 유향 그래프의 경우 변의 방향은 보통 부모를 가리키도록 구현된다.|
  |비선형 구조	|트리|뿌리와, 뿌리 또는 다른 꼭짓점을 단 하나의 부모로 갖는 꼭짓점들로 이루어진 구조. 부모 자식 관계는 변으로 표현된다.|
  |비선형 구조	|트리(이진트리)|자식이 최대 두 개인 트리|
  |비선형 구조	|트리(힙)|이진트리의 일종으로 이진트리에 어떤 특성을 부여한 것이라 할 수있다.|

  <br/><br/>

## :sparkles: 알고리즘이란? 

### 알고리즘을 공부한다는 것은 어떤 문제를 분석해서 컴퓨터가 알아들을 수 있는 형태로 해법을 설계하고 구현하는 과정을 익힌다는 의미이다. 알고리즘 학습은 단순히 문제 풀이 요령을 익히는 것이 아니다. 알고리즘 동작에 소요되는 메모리(공간)와 프로세싱 파워(시간)를 깊이 이해하고, 자원을 효율적으로 활용하면서도 고성능의 코드를 작성하는 방법을 익히는 것이다.
### 알고리즘은 주어진 문제의 특성에 따라 선택되며, 효율성과 정확성을 보장해야 한다. 정렬, 검색, 최단 경로 찾기 등 다양한 문제를 해결하는데 사용된다. 몇 가지 일반적인 알고리즘에는 이진 검색, 퀵 정렬, 다익스트라 알고리즘, 깊이 우선 탐색(DFS), 너비 우선 탐색(BFS) 등이 있다.

<br/>

## 알고리즘의 분류 
  |종류|설명|
  |:------:|:---:|
  |구현|재귀적 알고리즘, 연역적 알고리즘, 결정론적 알고리즘, 근사 알고리즘, 양자 알고리즘|
  |설계|무차별 대입 공격, 분할 정복 알고리즘, 그래프 순회, 분기 한정법, 확률적 알고리즘, 리덕션, 백트래킹|
  |최적화 문제|선형 계획법, 동적 계획법, 탐욕 알고리즘, 휴리스틱 함수|
  |이론적 분야|검색 알고리즘, 정렬 알고리즘, 수치 알고리즘, 그래프 알고리즘, 문자열 알고리즘, 암호학적 알고리즘, 기계 학습, 데이터 압축|

<br/><br/>

## 정리

### "자료구조"는 메모리를 어떻게 효율적으로 사용하며, 실행 속도를 빠르고, 정확하게 처리할 수 있을까를 궁극적인 목표로 두고 있다.
### "알고리즘"은 이러한 자료구조의 목표를 바탕으로 문제를 해결하기 위해 정해진 일련의 절차나 방법을 공식화한 형태로 표현하는 것이다.
### 자료구조와 알고리즘은 소프트웨어 개발에서 중요한 역할을 한다. 올바른 자료구조의 선택과 효율적인 알고리즘의 구현은 프로그램의 성능을 향상시키고, 코드의 가독성과 유지 보수성을 향상시킨다. 따라서 컴퓨터 과학 및 소프트웨어 엔지니어링 분야에서 자료구조와 알고리즘에 대한 이해는 매우 중요하다.

※언어는 파이썬을 이용할 예정입니다.※
