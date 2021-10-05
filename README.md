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
int main()
{
	int i = 0;
	do
	
	{
		printf("%d ", i);
	    i++;
     }
	while (i <= 10);


	return 0;
}
int main()
{
	int i = 0;
	int n = 0;
	int ret = 1;
	scanf("%d", &n);
	for (i = 1; i <= n; i++)
	{
		ret = ret * i;
	}
	printf("%d\n", ret);
    return 0;
}
int main()
{
	int arr[] = { 1,2,3,4,5,6,7,8,9,10 };
	int i = 0;
	int sz = sizeof(arr) / sizeof(arr[0]);
	int left = 0;
	int right = sz - 1;
	int mid = (left + right) / 2;
	int k = 5;

	while(left<right)
		{ if (arr[mid] > k)
	{
		right = mid - 1;
	}
	else if (arr[mid] < k)
	{
		left = mid + 1;
	}
	else
		printf("找到了，下标是%d\n", mid);
	    break;
		}
	return 0;
}
int main()
{
	int arr[] = { 0,1,2,3,4,5,6,7,8,9 };
	int i = 0;
	int k = 16;
    int sz = sizeof(arr) / sizeof(arr[0]);
	for(i = 0; i < sz; i++)
	{
		if (k == arr[i])
		{
			printf("恭喜你，找到了，下标是：%d\n", i);
			break;
		}
		
	}
	if (i == sz)
		printf("找错了");

	return 0;
}
int main()
{
	char arr1[] = "welcome to bit !!!";
	char arr2[] = "##################";
	int left = 0;
	int right = strlen(arr1) - 1;
	while (left <= right)
	{
		arr2[left] = arr1[left];
		arr2[right] = arr1[right];
		printf("%s\n", arr2);
		Sleep(1000);
		system("cls");

		left++;
		right--;
	}
	printf("%s\n", arr2);
	
	return 0;
}
//cls清空屏幕
int main()
{
	int i = 0;
	char password[20] = { 0 };
	printf("钟棂献喜欢谁,欸嘿嘿\n");
	printf("提示：姓为钟\n");
	for (i = 0; i < 3; i++)
	{
		
		scanf("%s\n", password);
		if (strcmp(password, "钟离")==0)
		{
			printf("恭喜，回答正确");
			break;
		}
		else
		{
			printf("密码错误\n");
		}
	}
	if (i == 3)
		printf("很遗憾，闯关失败bushi\n");
	return 0;
}
int main()
{
	int a = 0;
	int b = 0;
	int c = 0;
	int max = 0;
	scanf("%d %d %d", &a, &b, &c);
	if (a < b)
	{
		int tmp = a;
		a = b;
		b = tmp;
	}
	if (a < c)
	{
		int tmp = a;
		a = c;
		c = tmp;
	}
	if (b < c)
	{
		int tmp = b;
		b = c;
		c = tmp;
	}
	
	printf("%d %d %d",a,b,c);
	return 0;
}
int main()
{
	int i = 0;
	for (i = 1; i < 101; i++)
	{
		if (i % 3 == 0)
		{
			printf("%d\n", i);
			
		}

	}
	return 0;
}
int main()
{
	int r = 0;
	int m = 57;
	int n = 18;
	while (r = m % n)
	{
		m = n;
		n = r;
	}
	printf("%d\n", n);
	return 0;
}
