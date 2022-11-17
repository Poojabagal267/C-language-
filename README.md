# C-language-
//String Palindrome or not palindrome 
#include<stdio.h>
#include<string.h>
void main(){
  int i,j;  
  char s1[50];
  char s2[50];
  printf("Enter the string:\n");
  gets(s1);
  int len=strlen(s1);
  i=0;
  for(j=len-1;j>=0;j--){
     s2[i]=s1[j];
     i++;
  }
 int cmp=strcmp(s1,s2);
 if(cmp==0){
    printf("String is palindrome.");
  }
  else{
    printf("String is not palindrome.");
  }  
}
