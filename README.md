# 2020732077_양봉윤_제어공학_HW1
---
# P2.7  
$\text{적분 증폭기 회로의 전달함수H(s)는 입력전압과 출력전압의 관계}$  

$\text{* OPamp 특성을 이용하여 KCL 사용}$

$i_1(t) = \frac{V_0 - V_1(s)}{R}\ \ , \ \ \  i_2(t) =  C  \ \frac{d(V_2(s)-V_0)}{dt}$  
    
${\mathcal{L}\} \ i_1(t) \quad \Rightarrow \quad I_1(s) = \frac{-V_1(s)}{R}$  
${\mathcal{L}\} \ i_2(t) \quad \Rightarrow \quad I_2(s) = C \cdot s \cdot V_2(s)$  

$\frac{-V_1(s)}{R} =  C \cdot s \cdot V_2(s)$  
$\therefore H(s) = \frac{V_2(s)}{V_i(s)} = \frac{-1}{R \cdot C \cdot s} $  

---
# P2.12

$R(s) \cdot k \cdot \frac{1}{s + 50} = Y(s)$

$\lim_{t \to \infty} y(t) = \lim_{s \to 0}S \cdot Y(s) = \lim_{s \to 0} \frac{s \cdot K}{s(s + 50)} = 1$  

$\therefore k = 50$

---
# P2.15

$\text{주어진 스프링-질량 시스템의 운동방정식은 다음과 같다.}$  
$m \cdot \frac{d^2 x(t)}{dt^2} + b \cdot \frac{d x(t)}{dt} + k \cdot x(t) = \delta(t)$

$\text{운동 방정식을 라플라스 변환}$      
$m \cdot s^2 \cdot X(s) + b \cdot s \cdot X(s) + k \cdot X(s) = 1$

$X(s) = \frac{1}{m\cdot s^2 + b\cdot s + k}$

$\text{라플라스 역변환으로 시스템 응답 x(t)}$  
$x(t) = \mathcal{L}^{-1} \left( \frac{1}{ms^2 + bs + k} \right)$  
$x(t) = ? $  

---
# P2.26

