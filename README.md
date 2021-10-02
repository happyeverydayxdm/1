# 1
zhe first day
#define _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>
#include<string.h>
int main()
{
	int age = 20;
	if (age < 18)
		printf("yse");
	else 
		printf("no");
	return 0;
}
int main()
{
	int age = 10;
	if (age < 18)
		printf("未成年");
	else if (age >= 18 && age < 28)
		printf("青年");
	else if (age >= 28 && age < 50)
		printf("中年");
	else
		printf("老年");
	return 0;
}
int main()
{
	int age = 120;
	if (age < 18)
		{printf("未成年");
    printf("不能。。。。。。。")；
  }  
	else
	{
		if (age >= 18 && age < 28)
			printf("青年");
		else if (age >= 28 && age < 50)
			printf("中年");
		else
			printf("老年");
	}
	return 0;
}
int main()
{
	int a = 0;
	int b = 2;
	if (a == 1)
	{
		if (b == 2)
			printf("hehe\n");
	}
		else
			printf("haha\n");
	
	return 0;

}
//else就近
int main()
{
	int num = 4;
	//if (num = 5)错误形式
	if(5 == num)
	{
		printf("hehe\n");
	}
	return 0;

}
//为什么能打出hehe,=是赋值，==是判断相等
int main()
{
	int i = 1;
	while (i <= 100)
	{
		if (i % 2 != 0)
			printf("%d ", i);
		i++;
	}
	return 0;
}
int main()
{
	int i = 1;
	while (i <= 100)
	{
		printf("%d ", i);
		i += 2;
	}
	return 0;
}
int main()
{ 
	int day = 0;
	scanf("%d", &day);
	switch(day)
	{
		case 1:
			printf("星期1");
			break;
			
		case 2:
			printf("星期2");
			break;

		case 3:
			printf("星期3");
			break;

		case 4:
			printf("星期4");
			break;

		case 5:
			printf("星期5");
			break;

		case 6:
			printf("星期6");
			break;

		case 7:
			printf("星期7");
			break;

	}
	return 0;
}
