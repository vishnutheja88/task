

```shell
sudo yum install -y epel-release
sudo yum install -y --enablerepo=epel python-pip python-paramiko
sudo pip install ansible
```



```shell
ssh-keygen -t rsa
ssh-copy-id -i .ssh/id_rsa.pub root@tomcat-server
```



```shell
cd ansible-tomcat; ./ansible-build.sh
```

