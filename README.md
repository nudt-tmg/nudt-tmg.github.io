
# TMG-NUDT
 - HEXO(mions theme) + GithubPages



## Notes

**该source分支用于保存hexo源码**

- **环境配置**步骤：

1.安装Git，[https://git-scm.com/](https://blog.csdn.net/yaorongke/article/details/119085413)

2.安装NodeJS，https://blog.csdn.net/yaorongke/article/details/119084295

3.安装Hexo，https://hexo.io/zh-cn/

     npm install hexo-cli -g
     hexo -v
     # 执行成功说明安装完成


- **仅更新**步骤：
  
   1.将新电脑生成的ssh key添加到GitHub账户上
   2. fork并clone 仓库，打开git bash输入以下命令：
      ```
      git clone https://github.com/nudt-tmg/nudt-tmg.github.io.git
      ```
   4. 更新内容并提交pull requests

      ```
      git init
      git remote add https://github.com/nudt-tmg/nudt-tmg.github.io.git
      git add .
      git commit -m "upload"
      git push -u origin source
      ```
      
  
- **更新并编译**步骤：
  
  1. **确保本地源码和source分支源码保持一致，不一致则拉取最新源码**

     ```
     git pull
     ```
  
  3. **更新内容后使用以下命令检查更新内容**（需要hexo环境，[具体参考这里](https://zhuanlan.zhihu.com/p/299161193)）
  
     ```shell
     npm install npm -g 
     hexo c & hexo g & hexo s
     ```
  
  4. **使用以下命令推送编译的内容到master分支**
  
     ```
     hexo c & hexo d
     ```
  
  5. **同步更新的内容到source分支**



本文参考https://www.jianshu.com/p/0b1fccce74e0
