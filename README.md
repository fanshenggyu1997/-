# -
my frist c
#include <stdio.h>
#include <math.h>



int main(void)
{
	 int a=1;//分别对abc赋值
	 int b=4;//分别对abc赋值
	 int c=6;//分别对abc赋值

	double dalte;//定义dalte函数
	double x1;
	double x2; 
	   
	 dalte=b*b-4*a*c; //规定dalte的算法
	  
	 if   (dalte>0)
	 {
		 x1=(-b)+sqrt(dalte)/(2*a);
	     x2=(-b)-sqrt(dalte)/(2*a);
		 
		 printf("方程的解为：x1 = %f,x2 = %f\n",x1,x2);
		  


	 }
	 else if (dalte==0)
	    {  x1=(-b)/(2*a);
	        x1=x2;
	 printf("方程的解为：x1 = x2 = %f\n",x1);


	 }
	 else  {
		  printf("此方程无解");

	 }
      getch(); //程序运行后暂停

	return 0;
}
