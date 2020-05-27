## AndServer+Service 打造 Android 服务器调用 so 文件
#### 参考：https://mp.weixin.qq.com/s/Do4rGrMNFGx5HqFKM9vA1g 
#### 代码：https://github.com/NightTeam/HttpSo 
#### 我在这个基础上实现调用抖音libcms.so和秒拍的libte.so
---
#### 2020.5.9
#### 调用秒拍7.2.70 libte.so的Decode方法解密response
#### 调用10.9.0抖音libcms.so生成0404开头x-gorgon，如果写爬虫建议用旧版
#### 我的用法： https://github.com/heyaug/sign-algorithms
![](./png/1.png "")