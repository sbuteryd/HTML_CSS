
块元素：就是每个元素占一行
内元素：元素都在一行内


默认宽度

     理由：默认宽度就是浏览器的宽度不需要指定宽度，
     事实:比如：p 块元素，那么文字的宽度就是根据浏览器的宽度进行调整的。
     结论：浏览器 = p 的宽度如果没有指定宽度。
  
width，height
    
    理由：如果要设置宽度度就要用width 
    事实：width 指定宽度
    结论：通过指定width(宽度)来控制块里面内容度显示范围，

max-width min-width

    理由：如果没有指定mix-width 那么小屏幕屏幕显示宽度还是根据大屏幕大宽度，max-width 
    如果没有指定max-width 那么小屏幕大显示 到了大屏幕还是以为在小屏幕。
    事实： 通过指定max-width min-width 控制 屏幕大小显示
    结论： 同 max min 解决大小屏幕显示问题。
    
 
max-height min-height  同上

overflow: scroll hidden;

    理由：如果内容超出来 height
    事实：内容会显示显示到其它行会溢出
    结论：溢出如何处理，可以不显示或者有滚动条


display black element
 
    理由: 想让块元素显示在一行上，或者内联元素当成块使用
    事实: 块元素默认占显示一行，内联元素默认在一行
    结论：通过display black 转换成块元素 ，inline 转换成内联元素 ， 
    inline-block：有块当独立，又有内联元素的显示在一行。
    

border:

     
     理由:我的理解border 就想一个相框，通过相框来指定边界，同border 才可以用 padding martin 等。
     事实: 要设置相框的 大小、颜色、
     结论：通过以下命令进行设置你的相框     
     border: 10px; 
     border-style: solid;
     border-color: #b4005a; 
     
border-radius:

     理由：我的理解，不同的让喜欢的相框不一样，
     事实：通过border-radius来改变你喜欢的相框，圆的
     结论：border-radius 设置你的相册棱角



margin：
    
    理由：多个相框放在一起没有没有办法产生美感，而且看起来一坨
    事实：为来让相框，之间有距离
    结论：通过设置Marin 来来进行里面上下左右调整。
   
   
padding ：

    理由：相框里面的照片和相框太近
    事实：要让相框(border）和里面的内容或照片和相框要有距离
    结论：通过padding 来进行里面上下左右调整。
    
    

box-shadow: 1px 2px 3px black;
    
     理由：我的理解让静态的相框有3d的感觉
     事实：可以在底部设置阴影，让相框感觉悬浮
     结论：box-shadow 让 相框3d，悬浮。
     
     
