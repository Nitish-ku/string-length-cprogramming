#include <cs50.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
  string s = get_string("Input: ");
  printf("output: ");
  for (int i=0; i < strlen(s); i++)
  {
    printf("%C", s[i]);
  }
  printf("\n");
}
