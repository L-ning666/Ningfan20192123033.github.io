# Ningfan20192123033.github.
期中作业1.仓库代码托管功能
登录 创建仓库过程如上所示
首先我们需要在本地创建一个项目，作为托管项目。安装好Git之后，我们右键项目文件夹的时候会出现以下提示：

![image](https://user-images.githubusercontent.com/84163388/145961904-86537120-1737-490a-9f25-375df0d9af71.png)

 在弹出的git操作窗口中，使用：git init 初始化一个仓库
 
 ![image](https://user-images.githubusercontent.com/84163388/145962080-f79bb840-3eb9-46a8-9203-7c769244a784.png)
 
 之后会产生一个空的仓库，此时的代码只处于工作区，并未提交到暂存区和版本库。

    接下来我们需要执行以下命令来将代码保存到版本库。

  init之后会产生一个空的仓库，此时的代码只处于工作区，并未提交到暂存区和版本库。

    接下来我们需要执行以下命令来将代码保存到版本库。

    git add 文件名 或者git add  .    ：将文件从工作区提交到暂存区

    git commit -m "备注信息" ：将代码从暂存区提交到版本库master

    git status : 查看当前工作区代码的状态

    git log ：查看git操作的日志
    
![2](https://user-images.githubusercontent.com/84163388/145969372-6eafe6e9-db3c-412c-8428-513ee9b97d57.PNG)

    从这里我们可以看到当前的状态，没有被追踪的文件，那么我们需要将这些代码从工作区提交到暂存区

![3](https://user-images.githubusercontent.com/84163388/145969698-17cfeb91-3fd5-40a9-9773-e5450a7fb1fa.PNG)

 现在代码处于暂存区中，我们需要将暂存区的代码提交到master中
 
 ![4](https://user-images.githubusercontent.com/84163388/145969886-2327d840-4fd9-4eb2-979f-edb516cecb5e.PNG)

   
    配置本地ssh然后将ssh配置在github上
ssh的需要通过git生成公钥，并在GitHub上配置公钥，其他的用户才可以从github上下载代码。这里两种方式都会演示到，我们先使用http来托管项目；

    切到http，并将代码的托管路径copy出来，然后使用git push命令来讲代码传到GitHub上
       
       ![image](https://user-images.githubusercontent.com/84163388/145963790-2026ef11-f396-49c6-a8f4-9b852cfb0da7.png)
       
  刷新就实现了代码上传
2.代码下载首先Pycharm连接github账号配置好ssh公钥登录github搜索Python项目如下图所示

![@U~Z)V (3%C9_D}3}HMYCXN](https://user-images.githubusercontent.com/84163388/145964520-87522319-7eb8-49fd-b0b3-cdd4687fd7c8.png)

找到一个Python项目

![9SZN2MTTMUG16MRO{MSRC2E](https://user-images.githubusercontent.com/84163388/145964600-02340cef-550e-4652-8c2c-ee3ed3b34827.png)

找到其他人的ssh网页地址

![@{6609Q94CW7D}TZ G5MNHK](https://user-images.githubusercontent.com/84163388/145964723-e92dc7c0-15af-4261-a664-9c499984fb63.png)

打开pycharm


![LPZ0}36XY(3Z{WO(~R (8](https://user-images.githubusercontent.com/84163388/145964836-841e1841-7cb1-4f8a-bf26-5440cd7a0ef7.png)

找到Git选项选择clone

![_HL8FG33XX0F$}I@P2LBJ(U](https://user-images.githubusercontent.com/84163388/145965092-2561c113-f2ab-4cb8-997a-6b2d9044ce27.png)

输入刚刚的项目ssh地址

![8EDMYZ6Y_M22993E8E34 ZS](https://user-images.githubusercontent.com/84163388/145965283-1fe042e7-42ae-4fa3-8079-488a9d5a477b.png)



![20211214165403](https://user-images.githubusercontent.com/84163388/145965460-81f9eb94-49df-46b9-8324-92181181245b.png)


下载完成查看代码
    
    ![image](https://user-images.githubusercontent.com/84163388/145965636-cbda7e2e-47a8-4a12-b916-c33394f4ad1d.png)
    
    
    ![image](https://user-images.githubusercontent.com/84163388/145965848-18f19104-c856-4e68-af5c-4578e20c601f.png)



搜索功能就是直接在搜索框里面搜索可以搜索其他人的代码，自己的仓库代码还有自己的仓库

而版本管理也是基于上述的过程不断下载然后更新代码上传至github账号仓库里面进行版本管理
我们先由小组讨论，然后分工进行各自的部分先进行查找相应的资料然后实践上传下载等功能再进行功能里面的对象关系进行画图最后书写过程
小组分工：搜索功能顺序图，通信图由宁帆同学

李天成：仓库代码管理的顺序图和通信图由李天成同学分析进行画图，书写博客内容。
李玉峰：仓库版本功能顺序图和通信图及分析并书写过程
宁帆：搜索功能顺序图，通信图
王赢：分析写出代码托管功能的说明过程
邬宇东：分析写出搜索代码功能的说明过程
