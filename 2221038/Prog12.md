## ## Program 12: Write a program to illustrate the use of continue

```

include<stdio.h>

int main()

{

int i;

for (i = 0; i < 10; i++) {

  if (i == 4) {

    continue;

  }

  printf("%d\n", i);

}

return 0;

}

```

```output:

0

1

2

3

5

6

7

8

9

