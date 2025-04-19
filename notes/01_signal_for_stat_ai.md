# [01] Signal for Statistics & AI  
센서 신호, 통계, 그리고 인공지능을 연결하는 첫걸음

---

## 1. 왜 신호(signal)를 이해해야 할까?

센서에서 나오는 데이터는 단순한 숫자들의 나열이 아니라,  
시간의 흐름에 따라 변화하는 **신호(Signal)**다.

> 예: 연속적인 혈당 측정값, PPG, ECG, 압력 센서 데이터 등

통계나 AI 모델에 입력하기 전, **신호의 기본 구조와 특징**을 이해하면  
모델 설계와 데이터 전처리에 훨씬 유리하다.

---

## 2. 신호란 무엇인가?

- **정의**: 시간이나 공간에 따라 변하는 물리적 값 (아날로그 or 디지털)
- **종류**
  - 연속 신호 (Analog)
  - 이산 신호 (Digital)
- **예시**
  - ECG: 심전도 → 연속적 전압 변화
  - 센서 출력: 주기적으로 샘플링된 데이터

---

## 3. 센서 데이터의 주요 특징

| 특징 | 설명 |
|------|------|
| Sampling | 신호를 일정 시간 간격으로 채취 |
| Noise | 외부 요인으로 인한 불필요한 변동 |
| Windowing | 분석을 위한 구간화 처리 |
| Normalization | 센서 간 비교를 위한 정규화 |

---

## 4. Python 실습 예제

```python
import numpy as np
import matplotlib.pyplot as plt
# 예시: 노이즈 포함 신호 생성
t = np.linspace(0, 1, 1000)
signal = np.sin(2 * np.pi * 5 * t) + 0.3 * np.random.randn(1000)

plt.plot(t, signal)
plt.title("Noisy Signal")
plt.xlabel("Time (s)")
plt.ylabel("Amplitude")
plt.show()