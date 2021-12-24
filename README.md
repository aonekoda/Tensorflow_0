# Tensorflow

### 텐서플로를 활용한 딥러닝의 원리와 구현 

* YGL, 2021.12.20 35시간
* YGL, 2021.11.15 35시간
* 영우 글로벌 러닝 2021.05.24 ~ 05.28 35시간
* 영우 글로벌 러닝 
* 2020.12.21 ~ 2020.12.24 4일 28시간
* Tensorflow 2.3

---

* 삼성 디스플레이 VDI 환경 
< GPU 사용과 관련하여 - 다음 중 하나의 설정을 수행해 주세요 >  
1. GPU disable
```
  import os
  os.environ['cuda_visible_devices'] = '-1'
```
2. GPU 설정 변경
```
  gpus = tf.config.experimental.list_physical_devices('GPU')
  if gpus :
      tf.config.experimental.set_memory_growth(gpus[0], True)
```
3. GPU 환경변수 설정
```
  import os
  os.eviron['TF_FORCE_GPU_ALLOW_GROWTH'] = 'true'
```



* SDC - Power user 과정(2020.11.20~2020.11.26) 32시간
* Tensorflow 2.1.0

---

* SWFC - 머신러닝/딥러닝 과정(2020.08.10~2020.08.21)
* Tensorflow 2.3.0
