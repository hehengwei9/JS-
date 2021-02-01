# js语法
## 表达式
````
 var a = 1
 var b = 2
 var c = a + b
 console.log(c);
````
* 空格

  空格大部分没有实际意义，return后面不能加回车。

## 标识符
* 规则
  
  第一个字符可以是Unicode字母或$或_或中文，后面字符除了上面说的还可以有数字。

 * 变量名是标识符
  ````
  例如：
      var_=1
      var_ _=6
      var $=2
      var 你好='hello'
  ````

 ## 区块block

 ````
 {
     let a=1
     let b=2
 }
 常与语句合用
 ```` 

 ## 语句
 ```

 if 语句：
      if(表达式)
       {
          语句1
        }else
        {
          语句2
       }

 switch 语句：                   
      switch(fruit)
        ｛
         case:"banana"
         break;
         case:"banana"
         break;
         default:
        ｝
 
  while 循环:
        while(表达式)
        ｛
           语句
         ｝

  for 循环：
        for(语句;表达式;语句3) 
        {
          循环体
        }

  label 语句：
        foo:
        {
            console.log(1)
            break foo;
            console.log('本行不会输出');
        }
        console.log(2);
  
  问号冒号表达式:
        表达式1?表达式2:表达式3

 ```

 * && 逻辑与 ：A&&B&&C&&D 取第一个假值或D并不会取true/false

 * || 逻辑或 ：A||B||C||D 取第一个真值或D并不会取true/false
 * break和continue区别：
     
     1.break:退出所有循环
           
     2.continue：退出当前一次循环



 以上是我对JS基本语法的个人理解。 
