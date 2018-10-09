# matrix-multiplication
//creating universal matrix multiplication code

#include<stdio.h>

int main(void)
{
int a;
int b;
int c;
int d;



scanf("%d%d%d%d",&a,&b,&c,&d);

int A[a*b];
int B[c*d];

if(b==c)
{
for(int i=1;i<=a*b;i++)
{scanf("%d",&A[i-1]);}

for(int j=1;j<=c*d;j++)
{scanf("%d",&B[j-1]);}

}
else printf("%d\n",-1); 
}
