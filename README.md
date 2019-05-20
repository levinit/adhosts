# 介绍 Introduction
Adhosts是一个更新屏蔽广告hosts和科学上网hosts的shell小脚本。
hosts文件均来自互联网。
注意：如无法访问[https://google.com](https://google.com)，则访问[https://www.google.com/ncr](https://www.google.com/ncr)。

Adhosts is a script for updating advertisements-blocking and fanqiang(😂) hosts.

# 使用 Usage

下载**adhosts**，并解压缩得到**adhosts-master**文件夹。
- 首次运行：进入**adhosts-master**，执行`./adhosts` ，adhosts将会被安装到`/usr/bin/`下，并执行首次hosts更新。
- 更新hosts：首次执行执行后，如需更新只需执行`adhosts`  命令即可。
- 删除adhosts：`sudo rm /usr/bin/adhosts`

archlinux用户可从[aur](https://aur.archlinux.org/packages/adhosts/)下载，如使用yaourt：`yaourt -S adhosts`。

注意：
- 在支持运行shell脚本的系统上运行，如各种Unix、Uinx衍生的各种BSD，BSD衍生的MacOS、各种linux发行版。
- 更新hosts将会向/etc/hosts文件写入内容，故而**需要root或sudo权限**的用户执行。

---

Downlod **adhosts** , extracting it , `cd adhost-master`:
- install adhosts: `./adhosts`
- update hosts:  `adhosts` 
- delete adhosts: `sudo rm /usr/bin/adhosts`

archlinux user:`yaourt -S adhosts`. See [adhosts-aur](https://aur.archlinux.org/packages/adhosts/).

Notice:updating hosts need "sudo" or root permission.

# Hosts来源 Sources

- 科学上网 cross gfw
  - [googlehosts/hosts](https://github.com/googlehosts/hosts)
- 广告屏蔽 ad block
  - [AdAway/AdAway](https://github.com/AdAway/AdAway)
  - [vokins/yhosts](https://github.com/vokins/yhosts/)
  - ~~[sy618/hosts](https://github.com/sy618/hosts)~~
  - [neoFelhz/neohosts](https://github.com/neoFelhz/neohosts)
