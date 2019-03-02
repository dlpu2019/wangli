# github user manual
## install git
### on windows
安装后有gitbash命令行工具作为操作界面.
### on linux
### on mac
## 在github上创建repository
## Clone with SSH
Use an SSH key and passphrase from account.  
github help  
    - Checked for existing SSH keys  
    - Generated a new SSH key  
    - Added a new SSH key to your GitHub account  

## 创建ssh-key
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
### 复制公钥到github

### 测试
ssh -T git@github.com

## 克隆github库到本地
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY  
或者
git clone git@github.com:your-username/your-repository
## 查看远程库的别名
git remote -v

## 查看git管理的文件的状态
git status
## 增加文件
git add 文件名
## 提交到本地库
git commit
### 修改comment
git commit –amend
## 提交到远程库
git push 远程库名

## 查看提交记录
gitk
### gitk中文乱码问题的解决方法
在用户的主目录中的.gitconfig文件中增加:
[gui]
        encoding = utf-8
