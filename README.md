# 介绍

Adhosts是一个更新屏蔽广告hosts和科学上网hosts的小脚本。

hosts文件均来自互联网。

注意：如无法访问google.com，则访问[https://www.google.com/ncr](https://www.google.com/ncr)。

# 使用

- linux

  下载adhosts，并解压缩得到adhosts-master文件夹。

  首次运行：进入adhosts-master，执行`./adhosts` 。

  更新hosts：执行`adhosts`  命令即可（更新hosts将会向/etc/hosts文件写入内容，故而**需要root或sudo权限**的用户执行。）

  删除adhosts：`sudo rm /usr/local/bin/adhosts `

# Hosts来源

- [AdAway/AdAway](https://github.com/AdAway/AdAway)
- [vokins/yhosts](https://github.com/vokins/yhosts/)
- [racaljk/hosts](https://github.com/racaljk/hosts)
- [sy618/hosts](https://github.com/sy618/hosts)
- [neoFelhz](https://github.com/neoFelhz/neohosts)