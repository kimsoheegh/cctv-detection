# CCTV Detection
![image](https://github.com/kimsoheegh/cctv-detection/assets/91236577/b6abc81b-4161-43d6-a9f2-ae6bbe651f04)
<br>
## :mag: 목적
현재 개발된 번호판을 이용한 차량 추적 모델은 빠르게 달리는 자동차에서 번호판의 작은 숫자를 인식하기가 매우 어렵다는 문제점이 있고 그 이유 때문에 모델 개발에 들어가는 인력과, 시간 등의 비용이 상당하는 단점이 있다. 따라서 차량을 번호판이 아닌 차체 그 자체로 인식하여 추적한다면 이와 같은 문제점이 해결될 것이라고 우리 팀은 생각했다. 뿐만 아니라 수많은 차종을 전부 다른 차종으로 인식한다는 건 거의 불가능에 가까우나 차량을 소형, 중형, 대형으로 클래스 별로 나눠 차종을 인식할 수 있는 모델을 개발한다는 건 그 자체만으로도 충분히 의미가 있는 모델이 될 수 있다.
<br><br>
## :mag: 개발 과정
1. 차량의 360도 회전 모습을 찍힌 이미지 데이터셋 확보
2. labelImg를 사용하여 차량을 'small', 'medium', 'large'로 클래스를 나누어 커스텀 데이터셋 구축
![image](https://github.com/kimsoheegh/cctv-detection/assets/91236577/bc9cd06e-2ea3-4a80-a2c2-84d85b8061bc)
![image](https://github.com/kimsoheegh/cctv-detection/assets/91236577/fa45c860-d042-4c19-b771-6eda408c37e5)
