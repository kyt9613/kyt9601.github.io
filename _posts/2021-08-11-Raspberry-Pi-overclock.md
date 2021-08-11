---
title: "라즈베리파이 3 모델 B 오버클럭 / Raspberry Pi 3 Model B Overclock"
date: 2021-08-11 22:56:00 +0900
categories: Raspberry Pi 3 model b overclock
---
라즈베리파이 3 모델 B 오버클럭
```
# 화면에 검은 보더가 생길 경우
disable_overscan=1
# 활성화 하지 않으면 HDMI 를 뺐다 낄시 모니터 출력 불가
hdmi_blanking=1
# 오버클럭
arm_freq=1300
gpu_freq=500
core_freq=500
sdram_freq=500
sdram_schmoo=0x02000020
over_voltage=2
over_voltage_sdram=2
# SD카드가 Class 10 미만이면 84
dtparam=sd_overclock=100
```
