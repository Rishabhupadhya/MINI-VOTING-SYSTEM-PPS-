#include <stdio.h>
char
CTL (char i)
{
  i = i + 32;
  return i;
}
char LTC(char i)
{
    i=i-32;
    return i;
}
int main ()
{
  char i, a,b;
  printf ("Enter Alphabet\n");
  scanf ("%c", &i);
if(i>='a' && i<='z'){
   a= LTC(i);
    printf ("%c\n", a);
}
else if(i>='A' && i<='Z')
b=CTL(i);
printf ("%c\n", b);
return 0;}
