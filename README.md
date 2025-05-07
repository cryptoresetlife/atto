# atto
## [打开矿池网站]https://pool.rplant.xyz/#rincoin

* 1 点击创建钱包
  
![image](https://github.com/user-attachments/assets/16576d09-e539-4cc5-b192-da2ced0b5321)


* 2 选择自己对应的操作系统下载
  
![image](https://github.com/user-attachments/assets/90441897-8a83-4fe1-bcbd-30eab685624e)

* 3 解压缩钱包软件，运行rincoin-qt.exe，创建一个钱包

![image](https://github.com/user-attachments/assets/0365a86d-2252-4e2c-83c1-10b3a76693c4)


* 4 点击受取（R）——点击②创建一个新钱包地址
  
![image](https://github.com/user-attachments/assets/66d33d4e-db4d-44a3-8696-48919fc219cc)

* 5 复制钱包地址后点击ok

![image](https://github.com/user-attachments/assets/9e474bf5-f70d-423f-b850-06f18c7ae173)

  
* 6 返回矿池页面，下载挖矿软件

![image](https://github.com/user-attachments/assets/3fa9c96d-cb0d-40d2-8f8b-f17f5fd30e7e)

* 7 返回矿池，填入钱包地址，选择系统，区域。
* 下面会生成挖矿命令，复制到文本，保存为.bat文件（我这边需要把软件名改成cpuminer.exe）
![image](https://github.com/user-attachments/assets/31f99260-9958-4a36-8665-5d8945338ded)


* 替换成自己的钱包地址  
```bash
cpuminer-sse2.exe -a rinhash  -o stratum+tcps://stratum-asia.rplant.xyz:17148 -u rin1qcfwgzyalkpvwzfevhhpn4kmuqspx4mpls5x4wt.rincoin
```
* 运行后，cpu满载...  

![image](https://github.com/user-attachments/assets/363c4264-2587-440a-b934-afe429eeb4c2)

## 验证
* 在矿池页面，点击my miner 填入钱包地址 点击set
  
![image](https://github.com/user-attachments/assets/09d49b19-6e0c-488e-8072-9d326f5a10b3)

* 过一会就会显示出自己的工人。表示成功
![image](https://github.com/user-attachments/assets/2dbaca2f-765d-4268-84f2-c94008513c64)






