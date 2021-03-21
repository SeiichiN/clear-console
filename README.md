# clear-console
Clear Console for Java

コンソールをクリアするためのユーティリティです。  
c だと、こう書くんでしょうか。

```C:clear.c
#include <stdio.h>

int main()
{
  printf("\033[2J");
  return 0;
}
```

Linux と Windows で動作します。  
Macは持ってないんで...(T_T)

## compile
$ ant

## clean
$ ant clean

## run
$ java -cp ./classes Main

<!-- 修正時刻: Sun Mar 21 13:31:18 2021 -->
