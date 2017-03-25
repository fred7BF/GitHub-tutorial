# GitHub实践
GitHub上连接已有仓库的认证，是通过ssh的公开密钥认证方式进行的，运行下面的命令创建密钥
```bash
$ssh-keygen -t rsa -C "youremail@example.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/Users/xxx/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in rsa.
Your public key has been saved in rsa.pub.
＃如果/Users/xxx/.ssh/id_rsa这个文件已经存在，可以用另外一个名称代替，然后用ssh-add ~/xxx命令将私人密钥添加进缓存中。
```
然后将创建的公开密钥添加进账号的SSH keys中，完成以上设置，用ssh -T git@github.com验证，出现以下结果证明连接成功

```bash
Hi xxx! You've successfully authenticated, but GitHub does not provide shell access.
```
