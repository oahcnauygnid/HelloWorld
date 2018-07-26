/* 

scanf("%lf", &e); 

scanf("%d", &x);

printf("%d", s); 

while (2 * f >= e){

for(i=0;i<n;i++){ 

for(j=0;j<n;j++){

for(k=0;k<n;k++){

*/ 

#include<stdio.h>

#include<string.h>

#include<ctype.h>

#include<stdlib.h>

#include<time.h>

#define N 1000

void printf_1234_0();

void printf_1234_1();

void printf_1234_2();

void printf_1234_3();

void printf_1234_4();

void printf_shouye();

void qingping();

void chaxun();

void chakan();

void jiance();

void tianjia();

void zhiling();

FILE  *in,*out;

char *a[N][2];

int i,j,k,n;

char *mouju,*buchong,c;

int main()

{

	int x;	if ((in=fopen("mingju.txt","a+"))==NULL)

	{

	    printf("Can't open ming.txt");

	    return -1;

	}

	for (i=0;i<N;i++){

	  a[i][0]=(char*)malloc(20*sizeof(char));

      a[i][1]=(char*)malloc(20*sizeof(char));

	}

	mouju=(char*)malloc(20*sizeof(char));

	while (1){

	    if (fscanf(in,"%s",a[n][0])==-1)

	        break;

	    if (fscanf(in,"%s",a[n][1])==-1)

	        break;

	    n++;

	}

	qingping();

	printf_shouye();

	while ((c=getchar())!='\n'
