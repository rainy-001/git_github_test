git配置
git config --global user.name "<your name>"
git config --global user.email "<your email>"

git使用流程
本地开发代码
将开发过程修改的代码记录存放到本地的暂存区（git add）
将暂存区的代码更改记录呈递到本地仓库（git commit）
将本地代码改动呈交到远程仓库（git push）


分支
有本地分支和远程分支
如果代码开发了一个独立且复杂的功能需要分支，之后合并

密钥
ssh-keygen -t rsa -b 4096 -C "你的邮箱地址"
密钥会存放在C:\Users\Rain0x\.ssh
带pub的为公钥，在远程仓库配置
另一个为私钥，只存在于这台电脑上
git remote add origin git@gitee.com:Rain0x/git_gitee_test.git(ssh格式的链接)


git init
git remote add origin <仓库的地址>
git config core.ignorecase false 大小写敏感


gitignore.txt
/开头表示和gitignore.txt同目录下的文件夹
*任意字符数量通配符
**任意文件夹通配符
？单字符通配符
！特殊不忽略的某个文件

协作
先git pull
再git push
