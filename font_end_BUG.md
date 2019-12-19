# 前端BUG汇总

### admin: 图书流通-书籍信息修改

 ![image-20191218201011330](C:\Users\71959\AppData\Roaming\Typora\typora-user-images\image-20191218201011330.png)

点击完Delete前端所有书籍都消失

![image-20191218201026079](C:\Users\71959\AppData\Roaming\Typora\typora-user-images\image-20191218201026079.png)



![image-20191218145441792](C:\Users\71959\AppData\Roaming\Typora\typora-user-images\image-20191218145441792.png)

代表什么意思 需要传回pagesize？处理逻辑不应该是前端给page数据后端按要求返回吗

### 获取用户信息

![image-20191218150942696](C:\Users\71959\AppData\Roaming\Typora\typora-user-images\image-20191218150942696.png)

只给出了url， 但是没有给应返回的数据格式





### borrowingRecord

修改canBorrowTime为deadline（日期数据格式）

日期数据格式为年月日，而不是

<img src="C:\Users\71959\AppData\Roaming\Typora\typora-user-images\image-20191219133959304.png" alt="image-20191219133959304" style="zoom: 50%;" />

此页面排序还未完成 

学号写死，不能修改



### 新书采购