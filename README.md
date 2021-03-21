# clear-console
Clear Console for Java

コンソールをクリアするためのユーティリティです。\\
c だと、こう書くんでしょうか。

``` C:clear.c
#include <stdio.h>

int main()
{
  printf("\033[2J");
  return 0;
}
```

## compile
$ ant

## clean
$ ant clean

## run
$ java -cp ./classes Main

<!-- 修正時刻: Sun Mar 21 13:26:32 2021 -->
