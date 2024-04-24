#include <stdio.h>

int main(void) {
  int c, nl, b, t, total;

  nl = 0;
  b = 0;
  t = 0;
  
  while ((c = getchar()) != EOF) {
    if (c == '\n') {
      ++nl;
    }
    if (c == ' ') {
      ++b;
    }
    if (c == '\t') {
      ++t;
    }

  }

    total = nl + b + t;
    
    printf("New Lines: %d\n", nl);
    printf("Blank Spaces: %d\n", b);
    printf("Tabs: %d\n", t);
    printf("Total: %d\n", total);
      
      return 0;
}
