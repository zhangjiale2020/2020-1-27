## 第一课：Git 仓库的了解

```

git init  (创建目录)
rm -rf .git (删除所有目录，包括子目录)
Ctrl + l  (清理屏幕)

==》touch hello.txt  (创建一个txt文件)
==》Git   status (查看状态)
==》 Git add hello.txt  (放入暂存处)    2、git add . (包括全部的对象)
==》 暂存区==》工作区：Git rm --cached  
==》 从暂存区到对象区  Git commit 对象 
     2.git commit -m "注释"   3、ESC =》 shift + zz 退出编辑

4.vi hell.txt （修改内容） 则退回工作区

5.git log 查看历史
  git log -1
  git log --pretty=oneline
  git log --pretty=format:"%h - %an ,%an: %s"

commit b5df37e2183070f30bd0dcbae543aac428dec58c 
 
\md5  加密数 用于区分是哪一次提交（并且不重复）


```

<img src="C:\Users\EDZ\AppData\Roaming\Typora\typora-user-images\image-20191223160703431.png" alt="image-20191223160703431" style="zoom:50%;" />

UNstage（工作区）      staged（暂存区）       （commit）对象区

从工作区到暂存区===>>**Git add** hello.txt

从暂存区回退到工作区====>>git cached 对象 

从暂存区到对象区  Git commit 对象   

 