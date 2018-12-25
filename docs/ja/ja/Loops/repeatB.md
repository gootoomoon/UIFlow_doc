# データ反復
__________________________

#### 機能説明

>データの反復処理では、リストから順番に一つずつ要素を取り出して変数に代入し、ブロックの中の処理を実行します。

>![Range](/image/Loops/Range.jpg)

>* __for each item i in list__
リストの内容をひとつずつ取り出して __i__ に代入する毎に、ブロック内の処理を実行します。

>* __count with i from a to b by c__
__a__ から __b__ まで値を __c__ ずつ増加させ、__i__ に代入する毎に、ブロック内の処理を実行します。

>* __break out of loop__
可以选择跳出整个循环，或跳出本次循环，当执行到该Block时执行跳出
繰り返しから抜けたり、関数から抜けたりすることができます。

#### 使用方法

>データ反復ブロックをエディタ領域に追加し、パラメータを設定後、繰り返し処理を実行します。例：LEDバーの明るさを0から100まで変更します。
>![Range_user](/image/Loops/Range_user.gif)