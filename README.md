# debiancfg

- Passer en root

```su -```

- Install le package sudo

```apt-get install sudo -y```

- Donner les droits à l'utilisteur USER ( A CHANGER )

```usermod aG sudo USER```

- Rebasculer sur USER

```su USER```

- Update &&

```sudo apt-get update```

- Upgrade

```sudo apt-get upgrade```

- Package Net-Tools

```sudo apt-get install net-tool```

- Pouvoir utiliser ifconfig

```alias ifconfig='/sbin/ifconfig'```

- Shell stylé

```sudo apt-get install zsh```

- Git obligé

```sudo apt-get install git```

-- Shell stylé ++

```sh -c "$(wget -O- https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"```
