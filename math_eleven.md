# 11의 신비
- 11의 배수 찾기  
	홀수자리의 합과 짝수자리의 합이 같을 때  
- (10+1) (10^2-1) (10^3+1) (10^4-1) ...은 11의 배수
- 짝수자리 대칭수들은 전부 11의 배수!  
	*4자리 ABCD가 11의 배수임을 증명하는 과정*  
	= (A×10^3)+(B×10^2)+(C×10)+D = A×(10^3+1-1)+B×(10^2-1+1)+C×(10+1-1)+D  
	= A×(10^3+1)+B(10^2-1)+C(10+1)-(A-B+C-D)  
	-> (10^3+1), (10^2-1), (10+1)는 11의 배수이므로 (A-B+C-D)의 값이 11의 배수이거나 0이면 됨!  
	--> 4994 같은 경우,  4-9+9-4로 0이 되므로 11의 배수! 대칭수들은 전부 11의 배수!
