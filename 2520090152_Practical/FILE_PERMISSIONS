#include <stdio.h> 
int main() 
{ 
FILE *fp; 
fp = fopen("sample.txt", "w"); 
if (fp == NULL) 
{ 
printf("Cannot open file\n"); 
return 1; 
} 
fprintf(fp, "Hello, this is a test file.\n"); 
fclose(fp); 
printf("File created successfully.\n"); 
return 0; 
}
