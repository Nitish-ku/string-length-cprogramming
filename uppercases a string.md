#include <cs50.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
  string s = get_string("Before: ");
  printf("After:  ");
  for (int i=0, n = strlen(s); i < n; i++)
  {
    if (s[i] >= 'a' && s[i] <= 'z')
    {
      printf("%c", s[i] - 32);
    }
    else
    {
      printf("%C", s[i]);
    }
  }
    printf("\n");
}


//// ALTERNATE 

#include <cs50.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
  string s = get_string("Before: ");
  printf("After:  ");
  for( int i = 0, n = strlen(s); i < n; i++)
  {
    if (s[i] >= 'a' && s[i] <= 'z')
    {
      printf("%c", s[i] - ('a' - 'A'));
    }
    else
      {
      printf("%c", s[i]);
      }
  }
    print("\n");
}
