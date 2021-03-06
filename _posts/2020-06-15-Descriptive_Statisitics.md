

건물이나 시설 등의 정보를 설명하기 위해서는 '위치'와 '크기'를 전달하면 되듯이 데이터를 설명하기 위해서는 위치를 나타내는 대표값(representative value)과 크기(면적)에 해당하는 '산포(*dispersion*)'를 나타내는 대표값이 있다.

위치 모수(*location parameter*): 크기를 나타내는 대표값
 - 평균(mean 또는 average):
	 - 산술평균(arithmetic mean)
$$
\begin{aligned}
\bar{x}  &= \frac{x_1+x_2+\cdots+x_n}{n}\\ &= \frac{1}{n}\sum_{i=1}^{n}x_i
\end{aligned}
$$
	 - 가중평균(weighted mean 또는 weighted average)
$$
\begin{aligned}
\bar{x} &= \frac{\sum_{i=1}^{n}w_ix_i}{\sum_{_i=1}^{n}w_i}
\end{aligned}
$$


 - 중앙값(median)
	 - $n$이 홀수인 경우: $\frac{n+1}{2}$번째 값
$$
m_e=x_{\frac{n+1}{2}}
$$
	 - $n$이 짝수인 경우: $\frac{n}{2}$째 값과 $\frac{n+1}{2}$번째 값의 평균
$$
m_e=\frac{x_\frac{n}{2} + x_\frac{n+1}{2}}{2}
$$

 - 최빈값(mode): 도수(frequency)가 가장 높은 값
 - 최소값
 - 최대값

척도 모수(scale parameter): 산포를 나타내는 대표값
 - 분산(variation)
	 - 모분산(population variance): 모집단의 분산
$$
\sigma^2=\frac{1}{N}\sum_{i=1}^{N}(x_i-\mu)^2
$$
	 - 표본분산(sample variance): 표본의 분산
$$
s^2=\frac{1}{n-1}\sum_{i=1}^{n}(x_i-\bar{x})^2
$$

 - 표준편차(SD, standard deviation)
	 - 모표준편차(population standard deviation): 모집단의 표준편차
$$
\sigma=\sqrt{\frac{\sum_{i=1}^{N}(x_i-\mu)^2}{N}}
$$
	 - 표본표준편차(sample standard deviation): 표본의 표준편차
$$
s=\sqrt{\frac{\sum_{i=1}^{n}(x_i-\bar{x})^2}{n-1}}
$$
 
 - 변동 계수(CV, coefficient of variation): 분포의 산포 정도를 비교하기 위한 표준화(standardization)
$$
\nu=\frac{s}{\bar{x}}\times100(\%)
$$

 - 범위(range)
$$
x_{\text{max}}-x_{\text{min}}
$$

 - 사분위 범위(IR, interquartile range)

기타 척도
 - 표준오차(standard error): 데이터에서 산출(추정)된 각종 통계량의 오차
 - 왜도 또는 비대칭도(skewness): 데이터 분포의 비뚤어진 정도를 나타내는 통계량으로 분포의 대칭성을 나타낸다
$$
\begin{aligned}
g_1 &= \frac{\frac{1}{n}{\sum_{i=1}^n(x_i-\bar{x})^3}}{\Big(\frac{1}{n}\sum_{i=1}^n(x_i-\bar{x})^2\Big)^{3/2}} \\&=\frac{n}{(n-1)(n-2)}\sum_{i=1}^n\bigg(\frac{x_i-\bar{x}}{s}\bigg)^3
\end{aligned}
$$
 - 첨도(kurtosis): 데이터 분포의 뾰족한 정도를 나타내는 통계량으로 데이터 분포에서 봉우리가 얼마나 뾰족하게 솟아있는지를 가리킨다
$$
g_2 =  \frac{\frac{1}{n}{\sum_{i=1}^n(x_i-\bar{x})^4}}{\Big(\frac{1}{n}\sum_{i=1}^n(x_i-\bar{x})^2\Big)^{2}} -3
 - List item

$$

