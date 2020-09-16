# Java基本程序设计结构

## 数据类型

#### 	基本数据类型：

​	    整形：int、short、long、byte、float、double、char、boolean

   **strictfp**关键字标记的方法必须使用严格的浮点计算来生成可再生的结果

 **StrictMath**类

#### 运算符优先级



第一优先级 **数组下标[]**，**圆括号( )**，**成员选择（对象）.** ，**成员选择（指针）->**

结合方向为左到右

![C语言运算符优先级和结合律大全](https://exp-picture.cdn.bcebos.com/05a320a23a42a07a847f8d80673834bb18efc1c1.jpg?x-bce-process=image%2Fresize%2Cm_lfit%2Cw_500%2Climit_1)

第二优先级 **负号运算符-，强制类型转换，自增运算符++，自减运算符--，取值运算符，取地址运算符&，逻辑非运算符！，按位取反运算符~，长度运算sizeof符，**结合方向为左到右

![C语言运算符优先级和结合律大全](https://exp-picture.cdn.bcebos.com/ed792abb19efa25f267bf3c859828689a0463bc6.jpg?x-bce-process=image%2Fresize%2Cm_lfit%2Cw_500%2Climit_1)



第三优选级 **除/，乘\*，余数%，**结合方向为左到右

![C语言运算符优先级和结合律大全](https://exp-picture.cdn.bcebos.com/c33acc828689a14698dedf4af4bd4c7c35b334c6.jpg?x-bce-process=image%2Fresize%2Cm_lfit%2Cw_500%2Climit_1)



第四优选级，**加+，减-**，结合方向为左到右

![C语言运算符优先级和结合律大全](https://exp-picture.cdn.bcebos.com/4d3d2ab33c4133bae52e32ce6a37c97623bc2fc6.jpg?x-bce-process=image%2Fresize%2Cm_lfit%2Cw_500%2Climit_1)



第五优选级，**左移<<，右移>>，**结合方向为左到右

![C语言运算符优先级和结合律大全](https://exp-picture.cdn.bcebos.com/c8373cbc7dc5cf671630e4f58e96b814f5d026c6.jpg?x-bce-process=image%2Fresize%2Cm_lfit%2Cw_500%2Climit_1)



第6优选级， **大于>，大于等于>=，小于<，小于等于<=，**结合方向为左到右



![C语言运算符优先级和结合律大全](https://exp-picture.cdn.bcebos.com/c99358fe474ec28374d00a5cbe4f50b8b53e1cc6.jpg?x-bce-process=image%2Fresize%2Cm_lfit%2Cw_500%2Climit_1)



第7优选级，**等于==，不等于**，结合方向为左到右

![C语言运算符优先级和结合律大全](https://exp-picture.cdn.bcebos.com/51f9aa3ea8db574ab45da22fa7f7dfb2dd1917c6.jpg?x-bce-process=image%2Fresize%2Cm_lfit%2Cw_500%2Climit_1)



各类运算级别如图所示，级别先后为，**按位与&，按位异或^，按位或| ，逻辑与&&，逻辑或|| 条件运算符?:**，注意得是条件运算结合方向为右到左

![C语言运算符优先级和结合律大全](https://exp-picture.cdn.bcebos.com/5a5a00def4dca0394b70ff5f58d96975f3c40dc6.jpg?x-bce-process=image%2Fresize%2Cm_lfit%2Cw_500%2Climit_1)



第14优选级，**赋值运算符=，除后赋值/=，乘后赋值\*=，取模后赋值%=，加后赋值+=，减后赋值-=，左移后赋值<<=，右移后赋值>>=，按位与后赋值&=，按位异或后赋值^=，按位或后赋值|=，**结合方向为右到左

![C语言运算符优先级和结合律大全](https://exp-picture.cdn.bcebos.com/d2987775f2c4ec99072c35b2c3fe1e425c6b07c6.jpg?x-bce-process=image%2Fresize%2Cm_lfit%2Cw_500%2Climit_1)



## 字符串	

  **substring(a,b)**子串a的位置开始b个数

String all =String.join("/","a","b","c");    a/b/c

String repeated = "java".repeat(3);    javajavajava      

boolean equals()

#### 构建字符串

String  不可变    操作少量数据时使用

StringBuilder()   可变   线程不安全，效率高    操作大量数据多线程操作时使用

StringBuffer()    可变   线程安全，效率低       操作大量数据单线程操作时



#### 输入输出

​		