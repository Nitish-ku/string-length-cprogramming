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

///// ALTERNATE METHOD (MORE EFFICIENT)

#include <cs50.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
  string s = get_string("Input: ");
  printf("output: ");
  for (int i=0, m = strlen(s); i < m; i++)
  {
    printf("%c", s[i]); 
  }
  printf("\n");
}



///// ALTERNATE METHOD (SEMI  EFFICIENT)

#include <cs50.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
  string s = get_string("Input: ");
  printf("output: ");
  int length = strlen(s);
  for (int i=0; i<length; i++)
  {
    printf("%c", s[i]);
  }
  printf("\n");
}
