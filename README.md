# Tabuada
#include <stdio.h>


int A, B;

int
main ()
{

  printf ("Digite um nC:mero:");
  scanf ("%d", &A);
  printf ("Tabuada Do 1 ate %d\n", A);


  for (int x = 1; x <= A; x++)
    {
      for (int i = 1; i <= 10; i++)
	{
	  B = x * i;
	  printf ("%d x %d = %d\n", x, i, B);
	  if (i == 10)
	    {
	    }
	}
    }
  return 0;
}
