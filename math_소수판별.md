# 소수 판별법  
  - 소수 : 1과 자기자신만을 약수로 가지는 정수
  - 루트 X 이하의 수만 나눠보면 됨
  > X = M * N의 합성수라고 할 때,  
  > X가 소수라면 X = X * 1의 경우 밖에 없을 것이고  
  > X가 소수가 아니라면 X를 만드는 다른 정수 M 과 N이 존재할 것이다.  
  > 즉, M과 N은 X의 약수가 됨.  
  > 이 약수 set 중 큰 애를 M, 작은 애를 N이라하면  
  > M * M >= X(=M * N) >= N * N  
  > 따라서,  
  > M >= 루트X, 루트X >= N  
  > 약수 set는 작은애 하나만 알아도 큰애는 알아낼 수 있으므로 N만 구해보면 됨  
  > 따라서,  
  > 루트X 아래의 정수를 하나하나 나눠보면 N을 알아낼 수 있다!  
  > N이 구해지면 합성수, N이 없으면 (1제외) 소수~