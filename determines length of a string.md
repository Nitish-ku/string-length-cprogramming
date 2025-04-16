# string-length-cprogramming
# learning length of string in c programming


#include <cs50.h>
#include <stdio.h>

int main(void)
{
  // prompt for user's name
  string name = get_string("Name: ");

  //count number of characters up until '\0' (aka NUL)
  int n=0;
  while (name[n] != '\0')
  {
    n++;
  }
  printf("%i\n", n);
}
