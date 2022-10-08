#define _CRT_SECURE_NO_WARNINGS 1
#include <iostream>
#include <stdio.h>//system
 //不报错，对c语言库里有些会报错
using namespace std;

//std-标准 standard input output头文件

//1.输出 hello world
//int main()//主函数—程序的入口—main函数有且仅有一个
//{   //int是整形的意思
//    //main前面的int表示main函数调用返回的一个整型值
//
//	printf("hello world\n");
//	//在屏幕上输出hello world
//    //函数-print function - printf - 打印函数
//	//库函数 是c语言本身提供的一个函数
//	return 0;//返回 0
//}

//2.数据类型
////char 字符型
////short 短整型(short int) 
////int 整形 -
////long 长整型 -
////long long 更长的整型 -
////float 单精度幅度点 -
////double 双精度幅度点 -
////%d - 打印整型
////%c - 打印字符
////%f - 打印浮点数字 - 打小数
////%p - 以地址的形式打印
////%x - 打印16进制数字.......

//int main() {
//	char ch = 'A';//内存(字符类型)
//	printf(" % c\n", ch);//%c -- 打印字符格式的数据
//
//}
//int main() {
//	int age = 20;
//	printf("%d\n", age);//%d -- 打印整型十进制数据
//
//}
//int main() {
//	double f = 3.14;
//	printf("%lf\n", f);
//
//}

//3.计算空间大小
//int main() {
//	printf("%d\n", sizeof(char));//sizeof - 计算字符的所占空间
//	return 0;
//}

//4.变量：全部变量 局部变量
//int num2 = 20;//全局变量-定义在{}（代码块）之外的变量
//int main()
//{
//	int num1 = 10;//局部变量-定义在{}（代码块）之内的变量
//
//}
//局部变量和全局变量可以同时存在，走后定义的（局部变量优先）

//5.计算两个数的和
//int main() {
//	int num1 = 0;
//	int num2 = 0;
//	//输入函数—使用输入函数scanf
//	scanf("%d%d", &num1, &num2);//取地址符号&
//	int sum = 0;
//	sum = num1 + num2;
//	printf("sum = %d\n", sum);
//	return 0;
//}

