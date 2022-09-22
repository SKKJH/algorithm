# Algorithm design & analysis
## 알고리즘(Algorithm)
> 문제 해결을 위한 일련의 순서적인 계산/풀이 절차/방법 을 의미한다.  
> 알고리즘을 표현하는 방법은 일상 언어(Language),흐름도(순서도), 프로그래밍 언어(PL) 등으로 다양하게 표현 가능하다.  
> 알고리즘은 입력 -> 시스템 -> 출력의 과정을 통해 원하는 결과(출력)를 도출해 내는 과정을 기술한 것이다.


### 알고리즘의 특징
*  Input : input을 받아야 한다. 
*  output : Output을 생산해야 한다.
*  Generality : 특정 입력값들만 아니라 요구되는 모든 입력에도 적용 가능해야 한다.  
*  Order of operations : 수행할 순서가 정확해야 한다.
*  Precision : 각 단계는 명확해야 하고 모호하지 않아야 한다.  
*  Finiteness : 한정된 수의 작업 후, 반드시 유한한 시간 내에 종료되어야 한다.
*  Correctness : 알고리즘을 통해 만들어진 결과는 정확해야 한다.

<br><br/>
### 알고리즘의 계산 복잡도(Computational Complexity of Algorithm)
 * 서로 다른 알고리즘을 비교하기 위해서는 `동일한 하드웨어`를 사용한 상태에서 알고리즘의 실행 시간을 측정해야 한다.  
 * 또한 사용하는 `소프트웨어의 환경`도 고려되어야 한다. (예를 들어 컴파일 언어(C언어)를 사용한 경우, 인터프리터 언어보다 실행 속도가 빠르다.)
 
 
> 알고리즘의 성능은 "얼마나 빨리게 실행되는가", "얼마나 적은 자원을 사용하는가" 에 따라 구분된다.  
> 1. **시간복잡도(Time Complexity)**  
* 시간복잡도는 알고리즘을 수행하는 데 이루어진 연산 횟수를 나타낸다. (연산 = [산술, 대입, 비교, 이동])  
* 연산의 개수를 입력한 데이터의 개수 N의 함수로 나타낸 것을 시간복잡도 함수 라고 부르며 수식으로는 `T(N)` 으로 표기한다.  

> 2. **공간복잡도(Space Complexity)**  
* 공간복잡도란 `프로그램을 실행시킨 후 완료하는데 필요로 하는 자원 공간의 양`을 의미한다.  
* 이 때 필요한 공간 `S(space) = 고정 공간(Constant) + 가변 공간` 으로 표기한다.  
> `고정 공간` : 입/출력 횟수나 크기와 상관없는 공간(코드 저장 공간, 단순 변수, 고정 변수, 상수)을 의미한다.  
> `가변 공간` : 함수가 순환 호출을 할 경우 요구되는 추가 공간으로 동적으로 필요한 공간을 의미한다.

* 시간과 공간은 반비례적인 경향을 가지고 있기 때문에, **일반적으로 시간복잡도를 기준**으로 알고리즘의 성능을 판단한다.


<br><br/>
### 점근적 표기법(Asymptotic Notations)  
* 어떤 함수의 증가 양상을 다른 함수와의 비교로 표현하는 수론과 해석학의 방법.  
* 알고리즘의 복잡도를 단순화할 때나 무한급수의 뒷부분을 간소화할 때 쓰인다. (상수 계수, 중요하지 않은 항은 제거)  
  * 점근적 표기법은 '빅오 표기법 O Notation', '오메가 표기법 Ω Notation', '세타 표기법 Θ Notation'으로 구분할 수 있다.  
  <p align="center">
  <img src="https://user-images.githubusercontent.com/96826443/191543096-12396fc7-1d6e-437a-8785-c96821632623.png" />

</p>

  #### 빅오 표기법 O Notation  
  > ![image](https://user-images.githubusercontent.com/96826443/191547609-5542dfcc-067f-44ba-9949-2571a1f5b290.png)
  
  #### 오메가 표기법 Ω Notation  
  > ![image](https://user-images.githubusercontent.com/96826443/191548762-cd9010a4-d721-4b9e-9222-d69f0a7f991b.png)

  
  #### 세타 표기법 Θ Notation  
  > ![image](https://user-images.githubusercontent.com/96826443/191548804-5afc0769-f72b-4df7-9120-67beef4575ae.png)

  
  
  ### 점근적 표기법의 필요성  
  > 
  
  
<br><br/>
## 정렬 알고리즘(Sorting Algorithm)  
 * [단순 정렬 알고리즘(simple sort algorithm)](https://github.com/soneg4rizzle/ALGORITHM-STUDY/blob/main/sorting%20algorithm/simple%20sort/README.md)  
 * [선택 정렬 알고리즘(selection sort algorithm)](https://github.com/soneg4rizzle/ALGORITHM-STUDY/tree/main/sorting%20algorithm/selection%20sort#readme)  
 * [삽입 정렬 알고리즘(insertion sort algorithm)](https://github.com/soneg4rizzle/ALGORITHM-STUDY/blob/main/sorting%20algorithm/insertion%20sort/README.md)  
 * [버블 정렬 알고리즘(bubble sort algorithm)](https://github.com/soneg4rizzle/ALGORITHM-STUDY/blob/main/sorting%20algorithm/bubble%20sort/README.md)  

## Graphs

## Greedy Algorithms 

## Divide and Conquer 

## Dynamic Programming 

## Network Flow

## Linear Programming
