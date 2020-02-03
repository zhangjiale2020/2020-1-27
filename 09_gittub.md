| git push                                                     | 上传代码                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Git pull                                                     | 拉代码                                                       |
| rm -rf *                                                     | 删除目录中所有可见的文件                                     |
| rm -rf  .git                                                 | 删除所有未可见的文件                                         |
| 在gitHub中                                                   | 默认的说明文档readme.md                                      |
| git remote add origin https://github.com/zhangjiale2020/2020-1-27.git  (有时可能缺add 后加git) | 推送地址：在origin 代替后面地址                              |
| git push -u origin master                                    | 将本地和远程关联起来<br />后续不需要就不需要这样了，只需要**git push 了** |
| git push                                                     | 必须文件commit过才可以送到远程仓库。对象区的数据提交到仓库   |
| ssh 配置和https配置类似                                      | 但是需要配置<br />（本地）  私钥 和 （远程）  公钥           |
|                                                              | 可以将公钥存放在两个位置：<br />一个项目Setting中，(它可以使项目和本机直接连接)。二是放在个人账户：setting中（可以让任意项目和本机连接） |
| Git remote show origin                                       | 是查看所存储的仓库，以及分支类型                             |
|                                                              | git 会在本地维护， origin/master分支，并且通过该分支感知GitHub的内容 |

![image-20200127095808963](C:\Users\EDZ\AppData\Roaming\Typora\typora-user-images\image-20200127095808963.png)

![image-20200201174032535](C:\Users\EDZ\AppData\Roaming\Typora\typora-user-images\image-20200201174032535.png)

![image-20200201174853783](C:\Users\EDZ\AppData\Roaming\Typora\typora-user-images\image-20200201174853783.png)

![image-20200201213806198](C:\Users\EDZ\AppData\Roaming\Typora\typora-user-images\image-20200201213806198.png)

| Git branch    | 查看分支               |
| ------------- | ---------------------- |
| cd ..         | 返回上一级             |
| cd -          | 返回上一级             |
| origin/master | 这个一个中间的过渡分支 |
| cd .git       |                        |
| cat head      | 指向对象               |
|               |                        |
|               |                        |
|               |                        |
|               |                        |
|               |                        |
|               |                        |
|               |                        |
|               |                        |

