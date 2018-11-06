# 【Mac terminal 修改Git Config】
#### 问题：之前旧的Git账号不用了，新注册了一个Git账号，需要修改。
#### 解答：
```shell
$ git config --list 查看配置
$ git config --global user.name [username] 修改用户名
$ git config --global user.email [email]   修改邮箱
$ git config --global --unset user.name [username] 删除用户名
$ git config --global --unset user.email [email] 删除邮箱
```