# NodeJs Test

## 목적

다음 상황에서의 성능차이를 비교해 보기 위한 repo입니다.

- worker threads vs node clster mode
- 논리 core 수보다 많은 worker threads가 생성된 환경에서의 성능 변화 
- 논리 core 수보다 많은 process가 생성된 환경에서의 성능 변화

## 환경

- OS : window
- CPU : intel i5-8256U (4 cores)
- Node ver : 18.16.0 (LTS)
