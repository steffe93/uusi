# uusi
#include <stdio.h>
#define PI 3.1415

int main ()
{
	float area, radius;
	
	printf("ole hyvä, anna säde:  ");
	scanf("%f", &radius);
	
	area = PI * radius * radius;
	
	printf("pinta-ala on %f\n", area);
	
	return 0;
	}
