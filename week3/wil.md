# Image Classification

### 이미지 데이터 구조

- Pixel
- Channel
- Resolution

이미지 데이터를 다루는 방식 :
모든 이미지를 같은 크기로 조정한 후 1차원 벡터로 변환함.
이후 각 픽셀 단위로 벡터 간 거리를 계산하여 이미지간 유사도를 판단함.

### FNN

- 구조

1. 입력층
2. 은닉층
3. 출력층

두줄 요약 : 각 층의 모든 뉴런이 다음 층의 모든 뉴런과 연결된 구조. 다양한 문제에 적용할 수 있으나, 입력 데이터의 시-공간적 정보의 손실이 발생할 수 있어 그러한 문제는 효과적으로 처리하기 어려움.

### CNN

- 구조

1. 입력층
2. 합성곱 층
3. 활성화 함수
4. 풀링 층
5. 완전 연결 층

두줄 요약 : 합성곱 층, 풀링 층, 완전 연결 층으로 구성되어 이미지 데이터의 특징을 추출하는데 적합한 구조. 구조가 복잡하며, 대규모 데이터에 대해서는 연산량이 많아질 수 있음.