# Queue 란?
### 큐(Queue)는 한쪽 끝에서만 삽입이 이루어지고, 다른 한쪽 끝에서는 삭제 연산만 이루어지는 유한 순서 리스트이다.
### First in First Out (FIFO) 선입선출이라고 생각하면 쉽다.
### 먼저들어온것이 먼저 나가는 형식이다.
### 즉, 제일 처음에 들어온 데이터가 먼저 삭제가 된다.
# Queue(주요동작)
### enQueue() : 큐에 데이터를 넣는다.
### deQueue() : 큐에서 데이터를 빼낸다.
### isEmpty() : 큐가 비어있는지 확인한다.
### isFull() : 큐가 꽉 차 있는지 확인한다.
### peek() : 앞에있는 원소를 삭제하지 않고 반환한다.
# Queue(문제점)
### 큐(Queue)를 구현하고 사용할때 큐에서 데이터를 빼내는 deQueue()함수를 쓰게되면,
### 맨 앞에있던 값이 빠져나가게 되는데 이때 front가 한칸씩 뒤로 밀려나게 되면서 큐의 가용범위가 줄어들면서,
### 큐의 재사용 또한 불가능하게 됩니다.
### 만약에, 억지로 큐의 재사용을 하기위해서 front를 출력하고,
### front뒤의 인덱스를 하나씩 앞당긴다고 하더라도 불필요한 연산이 너무 많아진다.
# Queue 자바 코드
![화면 캡처 2023-03-22 141932](https://user-images.githubusercontent.com/127116197/226808967-1eaaf35d-4add-48f3-919d-ea459188b4f3.png)

# 선입선출(FIFO) 이란?
### 선입 선출(先入先出, first in, first out, 줄여서 FIFO)은 시간과 우선 순위와 관련된 데이터를 정리하고 이용하는 방식을 줄여 말하는 것이다.
### 이러한 표현은 선입선처리 행위에 따라 순서대로 처리함으로써,
### 기술을 처리하거나 수요 충돌을 관리하는 대기의 원칙을 말한다.
### 다시 말해, 먼저 온 것은 먼저 처리되고, 처리가 끝날 때까지 다음 것은 대기 상태에 놓이게 된다.
### 선입선출법을 사용하여 재고자산의 개별원가를 계산하게 되면,
### 기말에 장부상으로 남아있는 재고자산이 장부 마감 시점의 시가와 비슷하게 평가된다.
### 기말에 남아있는 재고자산 개수×최근 구매가 로 기말재고자산 가액을 쉽게 계산할 수 있다.

# Deque 란?
### 선형 정렬에서 지정된 형식의 요소를 정렬하고 벡터처럼 모든 요소에 대한 빠른 임의 액세스와 컨테이너 뒤쪽에서 효율적인 삽입 및 삭제를 가능하게 합니다.
### 그러나 벡터와 달리 deque 클래스는 컨테이너 앞에서 효율적인 삽입 및 삭제를 지원합니다.
![deque](https://user-images.githubusercontent.com/127116197/226812096-3d5f7e4c-10a8-4e64-ac52-5b3954840e69.jpg)

