15 

    什么块元素：就是占一行，就是独一无二等盒子。
    什么内元素：就是占div 里面移动，就是在盒子里面移动，img，em等
    
    

static(静态位置)：

      就是位置保持不变 = 没有设置。
      
 
relative ：
        
      就是水平移动位置, 使用margin，改变的时候，它原来的位置保持不变(占用的大小位置)。
     

absolute :

      没有位置的概念，我的理解就是，没有家的限制，这个位置不存在。
      
补充 fixed ：
    
    fix：固定的意思，就是在位置上不变，要结合 z-index使用。
    



以上是用 position 


float： 结合来 absolute和relative 和 inline-block类似。

    使用以下两个参数：
    righat: 向右看起
    left: 向做看起

    
    就向absolute一样移动，但是到来那个位置就变成来relation 占一个位置。
    注意 左 和 右。
    
    float: right,如果有三行 p1 p2 p3 那么，p1设置了（原来就在left） float：left,会保持原位。
    
    就像一排让站在一起，使用float 首先是 absolute， 然后后面的模块补上去，然后使用relation 进行水移动。
    
    

clear: left:
        
        就是去除float：注意方向。
                      
    
补充父元素错误问题：

         overflow: auto;
         width: 100%;
         
         用于解决父亲目录变成一条线，使用float的时候。
         
float 多列解决问题：
    
        要设置宽度，flaot的位置 margin 用于之间的距离         
     

        