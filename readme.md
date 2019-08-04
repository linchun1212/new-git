# 测试git上传分支
1. 现在远程见一个分支然后上传
```
git checkout -b feature-branch origin/feature-branch  
```
2. 再本地见一个分支然后传到远程
```
    git checkout -b feature-branch    //创建并切换到分支feature-branch  
    git push origin feature-branch:feature-branch    //推送本地的feature-branch(冒号前面的)分支到远程origin的feature-branch(冒号后面的)分支(没有会自动创建)
```