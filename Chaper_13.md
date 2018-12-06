默认没有设置宽度：

    默认没有设置width，块元素都是根据父元素进行改变的，如果没有设置那么块元素根据浏览器
    的大小进行改变。
    



with  % :

     设置宽度:指定宽度，宽度就是这个盒子的大小，
           %: 百分比就是大盒子里面的小盒子不能超过大盒子，这个百分比就说根据大盒子来进行with来进行调整
           相当于边界,也可以设置超过但是不建议设置超过100%
           
 
max-widht min-with ：      
    
    理由：最大和最小宽度是用于解决大屏幕和小屏幕，
    例：max-width 800 px 那么最大范围是800px，里面大文字限制在这个距离内。
    
    min-width 300px 那么里面内容 p 到300px就成来固定，里面内容就是300px。
    
max-widht min-with ： 

     some max-width
    
    
display  转换元素 

        display inline , 
        inline:这个单词的意思就是显示在一行上，这就是内联元素
        block:就是把内联元素转换成块元素的性质。
        
        inline-block：就是像内联元素那样可以变成一行，而且又继承联块元素的独立占一个位置。
        none ：不显示，



default   = 直接一个单位颜色或距离那么 上、右、下、左 显示同样的效果。'
specified_direction = 单独设置要指定方向（ 'border'-top-'color'  right bottom left ）
argument = 第一个参数代表上下、第二个参数代表，左右

## border : 相框

style:
        
        border-style：就是相框的样式，boder
        
        
        border: 10px  solid red;  参数1、2、3 ，宽度、风格、颜色。
        也可单个显示，例:border: 1px solid  
        
        border：solid
        是可以单独设置但是前提是你要第一个把style指定才可以单独设置。
        
        
        
     

color:        
        
        相框的大小、颜色，各个相框如何调整。
        border-color:设置的二种方式：
        *   default
        *   specified_direction
        * specified_direction: border-color: red black pink yellow ; 
        * argument: border-color: red black 
       
     
border-width: 
   
        设置direction相框的粗细的方式：
        
        * default 例子：width:10px
        * specified_direction:  例子：border-top-width
        * 


## 相框内部：

padding ：

        设置相框内部内容，和相框的距离：
        
        * defalut padding: 10px;
        * specified_direction:    padding-top: 10px;
        * padding: 10px 20px 30px 40px; 顺时针
        * padding: 10px 200px ; argument

                   
##  相框外部

margin :

       设置相框之间的距离
       * default margin: 40px
       * specified_direction: margin-left: 40px;    
       * margin: 30px 200px 30px 10px; 这个是顺时针 上、右，下、左
       margin: 1px 2px; argument
               
        

       
补充：
    
    margin 0 auto  让元素居中
    
 
补充2：

    shadow:
        box-shadow: 10px 10px  13px black;  上下，左右、清晰度、颜色、
        box-shadow: 10px 10px  上下、左右
        
补充3

    border-radius:100px 200px 300px 500px：specified_direction
    border-radius: default
    

补充4

    border：可以根据border背景可以使用图片
    

补充5:

    溢出:overflow: scroll; 就是高度超过了如何处理，隐藏，还是变成滚动条。
    
补充6 

 visibility: hidden;