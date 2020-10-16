# 介绍 Introduction
Adhosts是一个更新屏蔽广告hosts和科学上网hosts的shell小脚本。
hosts文件均来自互联网。
注意：如无法访问[https://google.com](https://google.com)，则访问[https://www.google.com/ncr](https://www.google.com/ncr)。

Adhosts is a script for updating advertisements-blocking and fanqiang(😂) hosts.

# 使用 Usage

- 安装Installation：

  执行以下命令Excute command below：

  ```shell
  curl -s https://raw.githubusercontent.com/levinit/adhosts/master/adhosts >> /tmp/adhosts.sh && sudo bash /tmp/adhosts.sh 
  ```

  或者下载**adhosts**，并解压缩， `cd adhost-master`，然后执行  `bash adhosts`.

  or Downlod **adhosts** ,  extracting it ,  `cd adhost-master`, and  `bash adhosts`.

- 更新Update hosts：`adhosts` 

- 删除Dlelete adhosts：`sudo rm /usr/local/bin/adhosts`

archlinux [aur](https://aur.archlinux.org/packages/adhosts/)：`yay -S adhosts`。

# Hosts来源 Sources

- 科学上网 cross gfw
  - [googlehosts/hosts](https://github.com/googlehosts/hosts)
- 广告屏蔽 ad block
  - [AdAway/AdAway](https://github.com/AdAway/AdAway)
  - [vokins/yhosts](https://github.com/vokins/yhosts/)
  - ~~[sy618/hosts](https://github.com/sy618/hosts)~~
  - [neoFelhz/neohosts](https://github.com/neoFelhz/neohosts)
