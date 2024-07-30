## GCP一键启用root帐号命令

登陆网页版 ssh，输入： 

```sh
sudo su
```

输入：

```sh
wget -qO- https://raw.githubusercontent.com/s1mcode/gcp-root-ssh/master/gcp-root-ssh.sh | bash
```

更改 root 密码：

```sh
passwd root
```

