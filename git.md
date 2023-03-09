# 一个人的版本控制

+ 进入要管理的文件夹

+ 执行初始化命令：将git设为文件夹的老大

  ```
  git init
  ```

+ 管理目录下的文件状态

  ```
  git status
  
  // 新增的文件和修改过的文件是红色
  //已经add的被管理的文件是绿色
  //已经生成版本后不显示文件
  ```

+ 管理指定文件

  ``` 
  git add 文件名
  git add .
  //管理目录下的所有文件
  ```

+ 个人信息配置：用户名、邮箱（一次即可）

  ```
    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"
  ```

+ 生成版本

  ``` 
  git commit -m '版本信息'
  ```

+ 查看版本记录

  ```
  git log
  ```

+ 回滚至之后的版本

  ```
  git log //用于查看版本号
  git reset --hard 版本号
  ```

+ 回滚至之前的版本

  ```
  git reflog
  git reset --hard 版本号
  ```




## Day2

+ 生成分支

  ```
  git branch // 查看分支信息
  	master是主干，其余分支可在创建时自由命名
  git branch '分支名' //创建分支
  
  git checkout '分支名' //切换分支
  ```

  