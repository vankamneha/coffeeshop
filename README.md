#include<stdio.h> 
#include<math.h>
int main() 
{
float c,d;
scanf("%f %f",&c,&d);
float n,r;
int res=0; 
while(c!=0) 
{ 
r=d/100*c;
n=floor(c-r); 
res=res+c;
c=n;
}
printf("%d\n",res); 
}
