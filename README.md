# 如何做一道浙大C程理论考题

>   若变量已正确定义，表达式` (j=3, j++) `的值是_____ 。(2000)
> 
> A、3          
> 
> B、4           
> 
> C、5            
> 
> D、0

 正解：A  
 **对于逗号表达式，其整个表达式的值为最后一个表达式的值**，所以` (j=3, j++) `表达式的值最后就是j++的值。后置自增在表达式执行结束后生效。

>已知字符 ‘a’ 的ASCII码为 97 ，执行下列语句的输出是_____。(2000)
> 
> `printf ("%d, %c", ’b’, ’b’+1 ) ;`
> 
> A、98, b        
> 
> B、语句不合法    
> 
> C、98, 99      
> 
> D、98, c

正解：D

格式控制字符串用于指定输出格式。%d输出字符常量'b'的ASCII码（比'a'大1即98），%c输出ASCII码对应字符常量（ASCII码比'b'大1即C）。

