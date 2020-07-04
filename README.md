#include<stdio.h>
int findlength(const char*);
	

int main() 
	{
	  char s1[10]="jagruti";
	  int n=findlength(s1);
	  printf("n=%d",n);
	  return 0;
	}
	int findlength(const char *ptr)
	{
          int k;
	  int i=0;
	  while(ptr[i]!='\0')
	  i++;
	  return i;
	}
