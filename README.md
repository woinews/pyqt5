# pyqt5
运用pyqt5进行界面设计

1、 	create_ini_file：  
因为项目中会生成很多窗口，如何保存这些窗口中的数据，因为目前所做的项目窗口数据量很小，故采用ini配置文件来保存。ini文件的百科解释https://baike.baidu.com/item/ini%E6%96%87%E4%BB%B6/9718973?fr=aladdin ，是一种以键值对保存的配置文件，通过键可以很容易实现配置参数的问题。  
更新0314：使用try--except来处理未读取文件时的异常，在主程序中加入app.aboutToQuit.connect(app.deleteLater) 来解决程序第二次运行时产生【Python已停止运行】的异常
