# drone
#include <stdio.h>
#include <stdlib.h>

int main()
{
    float x, y;
    printf (" digite as coordenadas do drone x e y:");
    scanf ("%f %f" , &x, &y);
    if ( (x >= 2 && x <= 6 && y >= 2 && y<=5 ) || (x >= 8 && x <= 12 && y >= 1
	&& y <=6)) { 
		printf (" pode aterrissar\n");
	} else { 
		printf (" nao pode aterrissar\n");
	}
    
    return 0;
}
