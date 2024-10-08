#include <stdio.h>

void main() {
int n = 29, i;
for(i = 2; i <= n / 2; i++) 
{
  if(n % i == 0) {
  printf("This is not a prime number\n");
  return;
  }
}
printf("This is a prime number\n");
}
