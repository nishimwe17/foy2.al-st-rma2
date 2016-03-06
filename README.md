#include <stdio.h>
#include <stdio.h>

int main(void) 
{
  int c;

  for( ; ; )
  {
   c = getchar();
   
     if (c == EOF) break;
     if (isupper(c))
    
       c = tolower(c);
  putchar(c);
  }
return 0;
}
