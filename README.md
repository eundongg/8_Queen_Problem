# 8_Queen_Problem
![image](https://user-images.githubusercontent.com/114046224/233767896-b3b9dae4-4fb9-48d1-9999-4a9ad5df1746.png)

출처: https://namu.wiki/jump/ICBobk6UPZyiBWMDLQVcXmzIhSUzDMVWVNJHdglOe%2Fwu6Khd2T%2FuK%2FFwTEXaqZSwwm%2BxUBB%2FaFEh8kS066SzuEgtK50CygyTut9A7lbGWOc%3D

</br>
</br>

## - how to?
#### 유전 알고리즘(Genetic Algorithm)을 이용하여 8개의 여왕말을 8x8체스판에 서로 위협하지 않도록 배치하는 문제 해결 방식
#### 공격 포인트는 상하, 대각선 (한 행에 하나의 queen만 존재할 수 있음)
#### 적합도 값으로 서로 공격하지 않는 queen쌍의 개수를 사용(만약 모든 queen들이 서로를 공격하지 않는다면 28)
#### 따라서 적합도 함수는 28-'공격하는 위치에 있는 queen의 개수'
