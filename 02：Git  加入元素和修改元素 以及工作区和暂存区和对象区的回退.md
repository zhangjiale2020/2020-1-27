```
1、git 常规命令学习
$ hdafsfjlsafjsafsa       ctrl+a  返回头  Ctrl + e 返回尾  Ctrl+c 返到下一行

2、pwd 获取当前访问的文件夹位置
修改存在文件里内容： echo 'world' > a.txt


修改的方法：
vi 文件名  然后输入  a 插入命令
esc 退出当前目录：
输入：   : set number (显示行号)
		: 9  光标指向第九行

3。设置邮箱和用户名：
	1. Git config --global (基本不用，给计算机一次性设置)
	2. git config --system (给当前用户一次性设置) 本机用户  推介使用第二个 cd`.gitconfig 目录里
	3. git congit --local  (给当前项目一次性设置) 项目
	优先级：3>2>1
4.查看文件内容：
 cat 文件名称：查看文件内的内容
 cd .git (进入隐藏目录中)   
 git config 进入config  然后进行git config --local（添加密码和用户） 
 
 [user]
        name = zjl
        email = 1371720916@qq.com
 删除：1.找到文件 直接删除不要的值，  2、通过Git config --local --unset user.name
5、给当前用户设置邮箱和名字：
/c/Users/

```

<img src="C:\Users\EDZ\AppData\Roaming\Typora\typora-user-images\image-20191223210045833.png" alt="image-20191223210045833" style="zoom:80%;" />

```
6. vi a.txt  (修改文件中的内容)  走到工作区了
7、走到对象区有两种方法： add   commit     
                      <2>  checkout  放弃修改  可以还原到对象区
                      查看 状态： Git status 
                      查看文件内容：cat 文件对象
  从暂存区到工作区；  cache 的命令
8 。提交问题：修改config 文件；    
   只对文件中:[user]
   				name = 'zjl'
   				zhuanghao = 1371720916qq.com
   引号可以不加 并且不改变原来的用户名和账号的名称和账号
9.
```

s