Sass css预处理器

1.变量：$xxx

2.嵌套 ：可以使用&符号来引用父选择器。

3.mixin：例子：

@mixin alert{

color：red；

background-color：green；

a{

color:yellow;

}

}

.alert-warnng{

@include alert;

}

4.继承：extend：@extend .xxx;

5.引入scss文件：@import "xx";，部分scss文件采用下换线”_“开头，则不会被编译。

6.type-of：判断类型

7.大写函数：to-upper-case，小写函数：to-lower-case，开始的索引值：str-index，插入函数：str-insert

8.颜色：rgb（r，g，b）函数，rgba（r，g，b，a）函数（a是透明度），hsl（色相，饱和度，明度），修改透明度：opacity（增加），transparentize（减少）

9.list：列表

10.length（）：列表长度