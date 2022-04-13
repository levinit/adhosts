# 介绍 Introduction

Adhosts 是一个更新屏蔽广告 hosts 的 shell 小脚本。
hosts 文件均来自互联网。

Adhosts is a script for updating advertisements-blocking hosts.

# 使用 Usage

- 安装 Installation：

  执行以下命令 Excute command below：

  ```shell
  curl -s https://raw.githubusercontent.com/levinit/adhosts/master/adhosts >> /tmp/adhosts.sh && sudo bash /tmp/adhosts.sh
  ```

  或者下载**adhosts**，并解压缩， `cd adhost-master`，然后执行 `bash adhosts`.

  or Downlod **adhosts** , extracting it , `cd adhost-master`, and `bash adhosts`.

- 更新 Update hosts：`adhosts`

- 删除 Dlelete adhosts：`sudo rm /usr/local/bin/adhosts`

archlinux [aur](https://aur.archlinux.org/packages/adhosts/)：`yay -S adhosts`。

# Hosts 来源 Sources

- 广告屏蔽 ad block

  - [AdAway/AdAway](https://github.com/AdAway/AdAway)·

  - [StevenBlack/hosts ](https://github.com/StevenBlack/hosts)

  - [privacy-protection-tools/anti-AD](https://github.com/privacy-protection-tools/anti-AD)
