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
int main()
{
	int a = 1;
	for(a = 1;a< 100; a++ ;)
	if (a % 2 = 1)
		printf("%d\n", a);
	else
		return a;
  	return 0;
}

int main()
{ 
	int day = 0;
	scanf("%d", &day);
	switch(day)
	{
		case 1:
			
		case 2:
			

		case 3:
			
		case 4:
			
		case 5:
			printf("工作日");
			break;

		case 6:
			
		case 7:
			printf("休息日");
			break;
		default :
			printf("哪有什么星期八");

	}
	return 0;
}
int main()
{
	int n = 1;
	int m = 2;

	switch (n)
	{
	case 1:n++;
	case 2:m++;
	case 3:
		switch (n)
		{

		case 1:m++;
		case 2:m++; n++; break;
		}
	case 4 :m++;
		break;
	default:
		break;
}
printf("m = %d,n = %d", m, n);
	return 0;
}
int main()
{
	int i = 0;
	
	while (i <= 10)
	{
		if (i == 5)
			break;
		printf("%d", i);
		i++;
	}
	return 0;
}
int main()
{
	int ch = getchar();
	putchar(ch);
	return 0;
}
int main()
{
	int ch = 0;
	while ((ch = getchar()) != EOF)//EOF   end   of    file
	{
		putchar(ch);
	}

	return 0;
}
int main()
{
	int ch = 0;
	while ((ch = getchar()) != EOF)
	{
		putchar(ch);
	}
	return 0;
}
int main()
{
int ch = 0;
	while ((ch = getchar()) != EOF)
	{
		putchar(ch);
	}
	return 0;

}
int main()
{
	
	int ch = 0;
	int ret = 0;
	char password[20] = { 0 };
	printf("请输入密码");
	scanf("%s", password);

	while ((ch = getchar()) != '\n')
	{
		;
	}
	printf("请确认(Y/N)");
	ret = getchar();

	if (ret = 'Y')
		printf("确认成功");
	else
		printf("确认失败");
	return 0;
}
int main()
{
	int ch = 0;
	while ((ch = getchar()) != EOF)
	{
		if (ch <= '0' || ch >= '9')
			continue;
		putchar(ch);
	}
	return 0;
}
int main()
{
	int i = 0;
	for ( i = 1; i <= 10; i++)
	{
		printf("%d\n", i); 
	}
	return 0;
}
int main()
{
	int i = 0;
	for (i = 1; i <= 10; i++)
	{
		if (i == 5)
			break;
		printf("%d\n", i);
	}
	return 0;
}
//不可在for内部修改变量，防止for失去控制；
//建议for语句循环变量取值采用前开后闭的用法
