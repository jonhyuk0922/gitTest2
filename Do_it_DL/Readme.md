박해선 저 Do it 딥러닝! 

1. 경사하강법 & 오차역전파법 : 경사하강법은 임의의 초기값을 지정한 후 변화율을 이용해 w,b를 업데이트하며 가장 잘 맞는 값을 찾아가는 방법이다. 
다만 두 가지 경우에서 한계가 있는데 첫번째는 예측값과 실제값의 차이가 너무 커서 오래 걸릴 경우 , 그리고 에측값인 y_hat이 작아지는 방향의 계산이 없다는 것이다.
이를 보완하는 방법이 오차역전파법으로, w,b를 최신화할 때 변화율에 오차값을 곱해준다.

2. 
