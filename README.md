#include<stdio.h>
int findlength(const char *ptr);
    int main() 
	{
	  char s1[]="jagruti";
	  int n=findlength(s1);
	  printf("n=%d",n);
	  return 0;
	}
	int findlength(const char *ptr)
	{
          int k;
	  int i=0;
	  while(ptr!='\0')
	  ptr++;
	  return ptr;
	}
