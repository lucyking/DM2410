# DM2410
ARM9嵌入式实验


- 0 哈哈哈    
- 1 嘻嘻嘻 
- [douban](wwww.douban.com)
- 


##2 一个miniGUI简例   
- 用IAR打开miniGUI工程项目:         
 ![菜单项](http://img3.douban.com/view/photo/large/public/p2239691074.jpg)       

 ![选择](http://img5.douban.com/view/photo/large/public/p2239691076.jpg)        
          
          
- 选中工程，右键展开菜单，点选**option**项       

 ![option](http://img5.douban.com/view/photo/large/public/p2239694336.jpg)       

- 选中左侧**Linker**项，勾选Override default,将文件替换成本工程.icf文件    
 ![icf](http://img3.douban.com/view/photo/large/public/p2239694340.jpg)   

- icf文件路径:  
  ![icf_path](http://img3.douban.com/view/photo/large/public/p2239694341.jpg)     

- 点击icf路径栏下的**Edit**项 选择第三个**Stack/Heap Size**选项卡 将最后**Heap**项参数改为0xf0000  
  ![stack](http://img5.douban.com/view/photo/large/public/p2239702549.jpg)

- 点击IAR左侧菜单栏中**make** 和**Download and Debug**按钮编译和刷写
  ![make](http://img3.douban.com/view/photo/large/public/p2239702970.jpg)
  ![b&b](http://img3.douban.com/view/photo/large/public/p2239702974.jpg)

- 将开发板LCD右下侧的开关推至off   
  ![off](http://img3.douban.com/view/photo/large/public/p2239701181.jpg)
