# accumulation

#include<stdio.h>

int main ()
{
	int i, sum = 0;
	
	for (i = 1;i <= 100;i++)
	if (i % 2 == 0)   sum =sum +i;
	
	printf("%d",sum);
	
	return 0;
	
}


i 错写成 1
i<=1与i++之间，应该是：   我却写成，   改了很久
sum=sum+i  不能写成sum++  这是两个意思
