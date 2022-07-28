# SM2
## 项目简介
SM2是非对称加密算法

它是基于椭圆曲线密码的公钥密码算法标准，其秘钥长度256bit，包含数字签名、密钥交换和公钥加密，用于替换RSA/DH/ECDSA/ECDH等国际算法。可以满足电子认证服务系统等应用需求，由国家密码管理局于2010年12月17号发布。

SM2采用的是ECC 256位的一种，其安全强度比RSA 2048位高，且运算速度快于RSA。
### 密钥派生函数
![img_6.png](img_6.png)
### 加密算法及流程
#### 加密算法
![img.png](img.png)
#### 加密算法流程
![img_1.png](img_1.png)
### 解密算法及流程
#### 解密算法
![img_2.png](img_2.png)
#### 解密算法流程
![img_3.png](img_3.png)
## 项目代码说明
### 模逆
![img_4.png](img_4.png)
### 密钥派生函数
![img_5.png](img_5.png)
### 椭圆曲线运算
#### 自身相加
![img_7.png](img_7.png
#### 不同点相加
![img_8.png](img_8.png)
#### 和比自己大1的点相加
![img_9.png](img_9.png)
#### 乘法
![img_10.png](img_10.png)
### 加密主函数
![img_11.png](img_11.png)
### 判断该点是否在曲线上
![img_12.png](img_12.png)
### 解密函数
![img_13.png](img_13.png)
## 实验结果
![img_14.png](img_14.png)
### 示例
![img_15.png](img_15.png)
