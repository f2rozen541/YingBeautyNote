hello Test edited by wangkun
# YingBeautyNote

一款类似印象笔记的App，随时记录您的生活点滴，但时目前功能还没达到印象笔记那样，但是本人后期将通过版本迭代的方式来逐渐完善该App达到印象笔记的全部功能，欢迎大家follow，star与fork。

#v2.1.0
##功能特色：相对v2.0版本主要增加以下几个功能：
草稿保存：当用户新添加一条笔记，但没点击保存按钮，直接按返回时会提醒用户是否保存为草稿  
字体大小设置：在用户编辑一条笔记时，提供字体大小设置功能，让用户选择字体大小  
闹钟提醒功能：用户可以将待办事项添加闹钟提醒，当到达指定日期指定时间闹钟会响铃提醒且会弹出待办事项的详情，如：待办事项为：给女朋友买礼物，待办日期为：2016/9/15 20：00，那么当达到2016/9/15 20：00时，用户手机闹钟会响铃提醒且会弹出待办事项的详情：给女朋友买礼物  
添加到桌面：可以将一些重要信息直接添加到桌面快捷方式，便于直接打开浏览  
分享笔记：可以将自己的一些比较好的笔记直接通过微信，短信等方式分享  


##可扫码直接下载  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/%E6%89%AB%E7%A0%81%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%9B%B4%E6%8E%A5%E4%B8%8B%E8%BD%BD.jpg)  

##应用截图
保存草稿界面  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2.1.0/S60915-121625.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2.1.0/S60915-120911.jpg)  
设置字体大小界面  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2.1.0/S60915-120955.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2.1.0/S60915-121004.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2.1.0/S60915-121012.jpg)
设置闹钟提醒界面  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2.1.0/S60915-121025.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2.1.0/S60915-124953.jpg)  
添加记录至桌面与分享笔记界面    
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2.1.0/S60915-121128.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot/S60812-214133.jpg)  

#Dependence
Butter Knife  
CircleImageView  
Universal-Image-Loader   
EventBus  
Bomb  
okHttp  
clans:fab  



#V2.0
##功能特色：相对v1版本增加以下几个功能  
和印象笔记一样采用云端存储的方式来存储用户记录，本项目采用的是Bmob云存储来解决的  
云存储：这也是本版本最核心的功能，一次存储，永不丢失，只要一个账号就可以在所有设备上同步自己以前的记录   
登陆注册功能：因为是云端存储所以得提供基本的登陆与注册功能，用来在区分用户的ID  
云同步功能：用户在客户端添加，删除，修改的记录将会与云端进行同步    
图片存储功能：主要是为了提供用户修改头像的功能，用户修改后的头像会上传到云端存储  

##应用截图
登陆与注册界面  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2/S60907-191614.jpg) 
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2/S60907-192227.jpg) 
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2/S60907-205446.jpg)  
下拉刷新及云同步界面  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2/S60907-192417.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2/S60907-192359.jpg)  
用户个人中心界面及修改信息popupWindow界面  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2/S60907-185754.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2/S60907-185819.jpg)  
用户修改头像界面(图片采用云存储)  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2/S60907-185754.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2/S60907-185911.jpg)  
图片选择器及裁剪界面  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2/S60907-215202.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2/S60907-222333.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot_v2/S60907-222411.jpg)  

#Dependence
Butter Knife  
CircleImageView  
Universal-Image-Loader   
EventBus  
Bomb  
okHttp  

该版本对应的博客介绍：http://blog.csdn.net/htq__/article/details/52463442

#V1.0
##功能特色：
界面漂亮性感：采用Materia Design规范，让您用的时候很舒心。  
支持设置卡片颜色：您可以选择5种颜色，换一种颜色，换一种心情  
支持拖拽排序：您可以将您觉得重要的记录拖拽到界面最顶端，让重要信息总是第一眼看到  
支持应用加锁：采用仔定义View实现类似支付宝九宫格的手势锁，保护您的重要数据隐私，麻麻再也不用担心我的隐私被人偷看  
支持拖拽删除：采用仔定义的HTQDragGridView实现拖拽删除功能  
支持皮肤更换，换一个皮肤，换一种态度，支持皮肤透明设置，让宅男腐女在使用时总能看到自己心仪的女神男神

##应用截图
记录卡片界面  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot/S60812-213058.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot/S60812-214328.jpg)

不同色彩卡片界面与仿支付宝手势加锁界面  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot/S60812-213946.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot/S60812-214050.jpg)

拖拽删除与拖拽排序界面  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot/S60812-212938.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot/S60812-213037.jpg)

设置皮肤透明度效果后界面  
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot/S60813-114357.jpg)
![image](https://github.com/HuTianQi/YingBeautyNote/blob/master/BeautyNote_Screenshot/S60813-114522.jpg)

更多界面请看Screenshot文件夹或者fork我的项目运行自行体验，如果喜欢的话记得follow，start一下哦。后期将通过版本迭代的方式逐渐扩充其功能  
博客详细介绍：http://blog.csdn.net/htq__/article/details/52205602  

#Dependence  
Butter Knife  
CircleImageView  
各大App Market下载地址:[腾讯应用宝](http://android.myapp.com/myapp/detail.htm?apkName=com.htq.baidu.com.htq.baidu.coolnote)


#相关链接
【HQ_QQ：一款高仿腾讯QQ的IM通讯App，界面几乎与腾讯QQ一模一样】 [https://github.com/HuTianQi/HTQ_QQ](https://github.com/HuTianQi/HTQ_QQ)  
【CoolWeather:一款天气查询App】 [https://github.com/HuTianQi/CoolWeather](https://github.com/HuTianQi/CoolWeather)


