使用git远程仓库时
需要将你当前的电脑添加到github远程仓库的信任目录中
通过git生成安全证书 $ ssh-keygen -t rsa -C "xxxxxxx@qq.com"
输入命令后直接按回车就会生成一个安全证书
    Generating public/private rsa key pair.
    Enter file in which to save the key (/c/Users/gpy/.ssh/id_rsa)://回车
    Created directory '/c/Users/gpy/.ssh'.
    Enter passphrase (empty for no passphrase)://回车
    Enter same passphrase again://回车
    Your identification has been saved in /c/Users/gpy/.ssh/id_rsa.
    Your public key has been saved in /c/Users/gpy/.ssh/id_rsa.pub.
    The key fingerprint is:
    SHA256:riPQbppe1dY6cbkjtxDesn3chaaAxL0SWPM4MiHSTDg 1914852120@qq.com
    The key's randomart image is:
    +---[RSA 2048]----+
    |   =.            |
    |  E + . o        |
    |   o . = =       |
    |      +.*.o.     |
    |   .  .+S++.   . |
    |  . .. +o*o.  o .|
    |   o.   O.=o + . |
    |   o+ .. O o+ .  |
    | .+o .... o.     |
    +----[SHA256]-----+

根据返回的结果,找到对应的证书文件id_rsa.pub
