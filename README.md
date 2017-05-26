

## About
这个github仓库，是`eqgrp-free-file.tar.xz` 的免费解压版本， 源文件由“The Shadow Brokers”黑客组织放出。 加密的拍卖版本可以在网上找到和下载。 

Firewall 这个文件夹包含了所有的源文件。 listing.txt则是所有文件的清单。  

This repository contains the decrypted and decompressed contents of the `eqgrp-free-file.tar.xz` file released by "The Shadow Brokers". The contents are supposedly a free sample of the files exfiltrated from the [Equation Group](https://en.wikipedia.org/wiki/Equation_Group), a notorious, highly-sophisticated cyber attack group.

The Shadow Brokers have opened an auction to sell off the remaining files, although the legitimacy of the auction is widely disputed. See the original auction announcement here: https://theshadowbrokers.tumblr.com/post/148871184165/equation-group-cyber-weapons-auction

Only files in the [`Firewall`](Firewall) directory are from the archive. [`listing.txt`](listing.txt) shows a list of all the files in the original archive, along with their file date and timestamps.

## Disclaimers
声明
这个仓库作为“The Shadow Broker”组织的所声称的事实的检验， 同时给那些想学习nb入侵技术的安全爱好者提供研究。 本人不对可能产生的任何后果负责。 

这些源文件和代码不属于我。 代码的作者的版权也不得而知。 如果我的行为侵犯了版权， 请通知我， 我会及时从仓库移除这些代码。 

This repository is provided as an educational resource to researchers wanting to validate the claims of the Shadow Brokers, as well as anyone wanting to study code potentially originating from a powerful threat actor. Needless to say, this repository may contain extremely malicious code, and I (@nneonneo) disclaim any responsibility for what may happen with your use or misuse of this software.

The code does *not* belong to me, but the author of the code is unknown and is very unlikely to step up to enforce any copyright claims. Nevertheless, if takedown is warranted I will gladly remove the repository.


free-file的文件主要涉及的内容是针对防火墙的扫描器、漏洞利用框架等等:
- BLATSTING -- 穷举爆破
- EXPLOITS -- 漏洞利用代码
- OPS -- 攻击操作控制工具包
- SCRIPTS -- 脚本资源引用库
- TOOLS -- 辅助工具包(编码转换、IP格式转换、加密解密装换等等)

