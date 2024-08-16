
# TMG-NUDT
 - HEXO(mions theme) + GithubPages



## Notes

**该zip分支用于保存hexo源码的压缩包**

- **仅更新**步骤：
  
   1. 下载压缩包并解压
  
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
