* 원래는 통계 프로그래밍과 시각화를 목적으로 만들어졌다
* 다양한 패키지를 통해서 기능 확장이 용이합니다. -> 데이터 사이언스
* 무료이다

# 데이터 사이언스를 위한 채키지
* 데이터 베이스에 접속을 위한 패키지: RODBC 등.
* 시각화를 위한 패키지: ggplot2 등
* 머신러닝을 휘한 패키지: fpc, tree, randomForest, caret 등

ctrl + L 콘솔창 clear

변수에 대입하는 법

Files 파일확인
Plots 시각화


```r
> x <- 3
> y <- 5
> x + y
[1] 8
```

R의 가장 기본적인 객체는 Vector 입니다:

* 벡터는 동일한 기본 자료형을 원소로 합니다.
* 벡터 생성: 함수 c(0를 사용하여 원소를 연결할 수 있습니다.
* 서로 다른 자료형의 원소를 하나의 벡터로 묶으려 한다면, 자료형이 자동 변환 됩니다
* 자료형에 따라서 변환 가능 또는 불가능
* 벡터 사이에는 벡터 연산이 가능합니다.

Run 한줄씩 실행
Source 전체 실행(print부분만 실행)
