### 【Mac terminal 修改Git Config】
#### 问题：之前旧的Git账号不用了，新注册了一个Git账号，需要修改。
#### 解答：
```shell
$ git config --list 查看配置
$ git config --global user.name [username] 修改用户名
$ git config --global user.email [email]   修改邮箱
$ git config --global --unset user.name [username] 删除用户名
$ git config --global --unset user.email [email] 删除邮箱
```

### 【Mac 抹掉磁盘选项】
#### 问题：USB抹掉时如何选择
#### 解答：

<img src="./images/n_1.png" width="50%" height="50%" />

* windows下通常格式为 NTFS，想要兼容Mac，选择FAT32 
* MS-DOS (FAT)：如果磁盘的大小为 32 GB 或不足 32 GB 时，选取此项
* ExFAT：如果磁盘的大小超过 32 GB 时，选取此项
* Mac OS 扩展（日志式）：使用 Mac 格式（日志式 HFS Plus）来保护分层文件系统的完整性
* Mac OS 扩展（区分大小写，日志式）：使用 Mac 格式并区分文件夹名称的大小写。例如，名称为“Homework”和“HOMEWORK”的文件夹是两个不同的文件夹。
