**Installed  Ubuntu 16.04.4 LTS**

**Upgrade to Ubuntu 18.04 LTS**

```
$ sudo apt update
$ sudo apt ugprade
$ sudo reboot
$ sudo do-release-upgrade
 
```

 **Installed  Terraform**

```
sudo apt-get install wget
wget https://releases.hashicorp.com/terraform/0.10.7/terraform_0.10.7_linux_386.zip
$ sudo apt-get install unzip
$ unzip terraform_0.10.7_linux_386.zip
sudo mv terraform /usr/local/bin/
```

 **Created new user** 

`add user lina`

**Added into sudo group**

`$ sudo usermod -aG sudo lina`

**Made sudo without password**

`$ sudo visudo `

\#User privilege specification

 `lina ALL=(ALL) NOPASSWD: ALL`

**Installed ZSH** 

`sudo apt install zsh`

**Created Systemd unit**

created try-daemon.service file in the /etc/systemd/system

**Installed LAMP Stack**

```
sudo apt install tasksel
sudo tasksel install lamp-server
```



