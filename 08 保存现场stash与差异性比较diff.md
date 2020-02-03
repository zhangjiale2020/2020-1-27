| git branch -m master master2 | 分支重命名                                             |
| ---------------------------- | ------------------------------------------------------ |
| Git stash                    | 临时保存                                               |
| git stash save 'mystash'     |                                                        |
| Git list                     | 查看保存好的临时场景                                   |
| 恢复现场：                   | 如下                                                   |
| Git stash pop                | 还原现场（将原来保存的删除，用于还原）默认还原最近一次 |
| git stash appli              | 只还原不删除 ,不删除之前的内容                         |
|                              |                                                        |
| git stash drop 左边的名字    | 手工删除现场                                           |
| vi a.txt                     | 手动改冲突文件内容                                     |

stash：保存现场

​				1.建议：在功能未开发完成前，不要commit

​				2.规定：在没有commit之前，不能checkout分支

​				（前提：不在同一个commit的阶段）



<img src="C:\Users\EDZ\AppData\Roaming\Typora\typora-user-images\image-20200114223720416.png" alt="image-20200114223720416"  />

如果还没有将某个功能开发完毕，就要切换分支：

建议：

​			1.保存现场  stash

​			2.切换到主分支

## 标签_——适用于整个项目

| Git  tag v1.0                | 给些好的项目给定版本 |
| ---------------------------- | -------------------- |
| git tag -a v2.0 -m  '新版本' |                      |
| Git tag                      | 查看标签             |
| git git tag -d 标签名        | 删除标签             |
| git tag -l  'v*'             | 查看v版本的所有版本  |
|                              |                      |
| git blame                    | 查看所写的人（追责） |
|                              |                      |

### diff 命令：差异性比较

| diff a.txt  b.txt             | 比较两个文件的内容           |
| ----------------------------- | ---------------------------- |
| diff  -u a.txt  b,txt         | 比较两个文件中的差异性的地方 |
| —                             | 原文件                       |
| +                             | 对比的文件                   |
| **deff 命令的是比较的是文件** |                              |
|                               |                              |
| Git diff                      | 比较的是工作区和暂存区的区别 |
| 工作区 = =》 暂存区           |                              |
| 对象区 ==》暂存区的比较       |                              |
| Git diff shawa值              | 比较对象和工作区的内容不同   |
| git diff hade                 | 比较最新的内容的不同         |

