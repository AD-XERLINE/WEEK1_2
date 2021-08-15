# -1_2
Week 1.2

#include<stdio.h>
#include<math.h>
int main () {
	double W ;
	double H ;
	
	printf("Enter your weight(kg.): ");
	scanf("%lf", &W);
	printf("Enter your hight(cm.): ");
	scanf("%lf", &H);
	
	double HH = pow(H,2);
	double bmi = (W/HH)*10000 ;
	printf("%.2lf\n",bmi);
	printf("----------------------------------\n");
    printf("       Body Mass Index\n");
    printf("   >18.5   = under the threshold\n");
    printf(" 18.5-22.9 =        slim\n");
    printf(" 23.0-24.9 =      overweight\n");
    printf(" 25.0-29.9 =       obesity\n");
    printf("   >30.0   =   Dangerous obesity\n");
    printf("----------------------------------\n");

return 0;
}
