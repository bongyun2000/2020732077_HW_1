# 2020732077_양봉윤_제어공학_HW1
---
# P2.7  
$\text{적분 증폭기 회로의 전달함수는 입력전압과 출력전압의 관계}$  

$\text{OPamp 특성을 이용하여 KCL 사용}$

$i_1(t) = \frac{V_0 - V_1(s)}{R}$  
$i_2(t) = - C \frac{d(V_2(s)-V_0)}{dt}$  

$i_1(t){와}i_2(t){라플라스 변환}$   
  
${\mathcal{L}}i_1(t) = I_1(s) = $  
${\mathcal{L}}i_2(t) = I_2(s) = -C \cdot s \cdot V_2(s)$  


$\frac{V_i(s)}{R} = -C \cdot s \cdot V_2(s)$

$V_2(s) = \frac{-V_i(s)}{R C s}$

$\text{전달함수} \quad H(s) = \frac{-V_2(s)}{V_i(s)} = \frac{1}{R C s}$

$R(s) = \frac{K}{s + 50} = Y(s)$

$\text{단계단 입력신호로 } r(t)\text{의 과도값 변화}$

$R(s) = \frac{1}{s} \quad \therefore \quad Y(s) = \frac{K}{s(s+50)}$

$\lim_{t \to \infty} y(t) = \lim_{s \to 0} Y(s) = \lim_{s \to 0} \frac{sK}{s(s + 50)} = \frac{K}{50}$

$m \ddot{x}(t) + b \dot{x}(t) + k x(t) = \delta(t)$

$s^2 X(s) + bs X(s) + \frac{k}{m} X(s) = \frac{1}{m}$

$X(s) = \frac{1}{ms^2 + bs + k}$

$x(t) = \mathcal{L}^{-1} \left( \frac{1}{ms^2 + bs + k} \right)$

