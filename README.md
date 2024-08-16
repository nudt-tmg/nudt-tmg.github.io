
# TMG-NUDT
 - HEXO(mions theme) + GithubPages



## Notes

**该source分支用于保存hexo源码**

- **环境配置**步骤：

1.安装Git，[https://git-scm.com/](https://blog.csdn.net/yaorongke/article/details/119085413)
2.安装NodeJS，https://blog.csdn.net/yaorongke/article/details/119084295
3.安装Hexo，https://hexo.io/zh-cn/
     ```
     npm install hexo-cli -g
     hexo -v
     # 执行成功说明安装完成
     ```


- **仅更新**步骤：
  
   1. fork并clone 仓库
  
   2. 更新内容并提交pull requests
  
      
  
- **更新并编译**步骤：
  
  1. **确保本地源码和source分支源码保持一致，不一致则拉取最新源码**
  
  2. **更新内容后使用以下命令检查更新内容**（需要hexo环境，[具体参考这里](https://zhuanlan.zhihu.com/p/299161193)）
  
     ```shell
     hexo c & hexo g & hexo s
     ```
  
  3. **使用以下命令推送编译的内容到master分支**
  
     ```
     hexo c & hexo d
     ```
  
  4. **同步更新的内容到source分支**
