# Documents
## GitHub 和 Git 工具操作
    仓库            Repository
    收藏            Star
    复制克隆项目     Fork
    发起请求         Pull Request
    关注             Watch
    事务卡片         Issue
    工作区           Workspace    
    暂存区/缓存区    Staging Area       
    本地仓库         Local Repository   
    远程仓库         Remote Repository  

### Git 初始化及仓库创建和操作

#### 一、基本信息设置
    1.设置用户名
    git config --global user.name 'GeekDevelope'

    2.设置用户邮箱
    git config --global user.name 'GeekDeveloper.org@outlook.com'

    3.查看用户设置
    git config --list

#### 二、初始化一个新的 Git 仓库
     git init

#### 三、向仓库中添加文件流程   工作区(Working Directory)   -->   暂存区    -->   Git Repository (Git 仓库)
    1.创建文件，如  README.md
    2.添加文件             git add README.md   或者 git add *.c
    3.提交文件             git commit -m 'Update README.md'
    4.上传代码并合并        git push
    5.下载远程代码并合并    git pull
    6.查看状态             git status

#### 四、上传现有工程

    1.git pull origin main
    2.git push -u origin main

#### 五、分支管理

    1.创建分支            git branch (branch name)
    2.列出分支(本地)      git branch
    3.查看远程分支        git branch -a
    4.切换分支            git checkout -b origin/public-preview
    5.合并分支            git merge
    6.删除分支            git branch -d (branch name)
    7.下载分支            git clone -b 分支名 网址.git      git clone -b master https://github.com/Azure/azure-iot-sdk-c.git

#### 六、Git基本操作

    1.创建仓库命令
    git init              初始化仓库
    git clone             拷贝一份远程仓库

    2.提交与修改
    git add               添加文件到仓库
    git status            查看仓库当前的状态，显示有变更的文件
    git diff              比较文件的不同，即暂存区和工作区的差异
    git commint           提交暂存区到本地仓库
    git reset             回退版本
    git rm                删除工作区文件
    git mv                移动或重命名工作区文件

    3.提交日志
    git log               查看历史提交记录
    git blame <file>      以列表形式查看指定文件的历史修改记录

    4.远程操作
    git remote            远程仓库操作
    git fetch             从远程获取代码库
    git pull              下载运程代码并合并
    git push              上传运程代码并合并


## Cloning the repo

    $ git clone https://github.com/GeekDevelope/Embedded-software.git
    
