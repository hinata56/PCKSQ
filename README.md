# PCKSQ

dataset : https://www.usgs.gov/core-science-systems/ngp/board-on-geographic-names/download-gnis-data

- RTree.py
  * IPM1, IPM2 : Pruning 방법을 적용하지 않은 탐색법
  * IPM3 : Approximation algorithm (def appro)를 적용한 탐색법
  * IPM4 : Approximation + MBR List pruning

- 수행 방법
  * (IR2Tree.py의 line 10, 변수 num에 추출할 데이터 셋의 크기를 설정한다.최대 200만개까지 설정할 수 있다.)
  * (IR2Tree.py의 line 49, 변수 k에 찾고싶은 키워드의 개수를 설정한다. 최대 62개까지 설정할 수 있다.)
  * python3.6 IR2Tree.py
