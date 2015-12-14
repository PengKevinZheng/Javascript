# Javascript  
##javascript语法
1.javascript语句向浏览器发出命令，告诉浏览器该做什么  
2.分号:语句之间的分割是分号。可用也可不用。  
3.javascript按照编写顺序依次执行  
4.javascript标识符必须以字母，下划线或美元符号开始。  
5.javascript对大小写敏感  
6.javascript会忽略多余的空格
7.单行注释：//   多行注释：/**/  

##变量  
        全局变量和局部变量：  
            <script>
            var a=10; //全局变量
            function(){
             var b= 20; //局部变量
                x=30;  //全局变量
            }
            </script>  
##DOM对象：  
        JavaScript可以改变所有的HTML元素，HTML属性，CSS样式。  
        1.在操作HTML元素时，绝度不要在文档加载完之后使用document.write(...)，这会覆盖文档内容。  
        2.通过id找到HTML元素：document.getElementById("id")  
          通过标签名找到HTML元素：document.getElementByTagName("tag")  
        3.改变HTML内容:  
          使用属性：innerHTML  
        4.改变属性：document.getElementById("id").attribute = "..."; 此处的attribute代表属性名。
