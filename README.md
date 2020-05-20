ＮＥＯ ＤＥＶ　Ｈｏｓｔ

![Logo](https://raw.githubusercontent.com/neodevpro/neodevhost/master/logo.png)


The Powerful Friendly Uptodate AD Blocking Hosts<br/>
最新强大而友善的去广告<br/>

[![Build Status](https://img.shields.io/github/workflow/status/neodevpro/neodevhost/CI/master)](https://github.com/neodevpro/neodevhost/actions?workflow=CI)<br/>
[![Last commit](https://img.shields.io/github/last-commit/neodevpro/neodevhost.svg)](https://github.com/neodevpro/neodevhost/commit/master)<br/>
[![license](https://img.shields.io/github/license/neodevpro/neodevhost.svg)](https://github.com/neodevpro/neodevhost/blob/master/LICENSE)

Total ad / tracking block list 屏蔽追踪广告总数: 188356
<br/>
Total whitelist list 白名单总数: 1524
<br/>
Update 更新时间: 2020-05-20

## Introduction 介绍

### UPTODATE 保持最新<br/>
  Merge　everyday　每天同步更新
### POWERFUL　 强大有效<br/>
  To block all ad / tracking  有效拦截广告追踪　
### FRIENDLY　友善使用<br/>
   Easy to use and welcome to report issues　简单使用欢迎回报问题
   
## Supported Platform 支持平台
-Windows<br/>
-Android<br/>
-Linux<br/>
-Mac OS<br/>

### Supported adblocker 广告拦截器
-Pihole<br/>
-Blokada<br/>
-DNS66<br/>
-Adaway<br/>
-gasmask<br/>
-Hostman<br/>

## Download 下载 

### AD host 去广告 [hosts]
> https://raw.githubusercontent.com/neodevpro/neodevhost/master/hosts.txt

### Whitelist 域名白名单 [whitelist]
> https://raw.githubusercontent.com/neodevpro/neodevhost/master/whitelist.txt

## How To Use 如何使用
1.Download both files/copy link of files<br/>
2.Add host and whitelist file/link into adblocker<br/>
3.Update the data source in the app<br/>

1.下载两个文件/复制下载链接<br/>
2.添加文件或者下载链接到广告拦截器<br/>
3.更新数据规则<br/>

## Pihole

For Import and Installation
1.Login to pihole website
2.Go to Groupmanagement > Adlists
3.copy the NEODEV AD host link into "Address:"
4.open terminal
5. Run the following command :
-sudo curl -s https://raw.githubusercontent.com/neodevpro/neodevhost/master/install.sh | bash
-pihole -g
6.Then it will import both NEODEV host and whitelist into your Pihole 

FOR Remove and Uninstall
1.Login to pihole website
2.Go to Groupmanagement > Adlists
3.click the red trash can button
4.open terminal
5. Run the following command :
-sudo curl -s https://raw.githubusercontent.com/neodevpro/neodevhost/master/uninstall.sh | bash
-pihole -g
6.Then it will Remove and Uninstall both NEODEV host and whitelist from your Pihole 


## Sources of AD-hosts data 去广告host源
1.https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Hosts/GoodbyeAds.txt<br/>
2.https://raw.githubusercontent.com/VeleSila/yhosts/master/hosts<br/>
3.https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts<br/>
4.https://raw.githubusercontent.com/Goooler/1024_hosts/master/hosts<br/>
5.https://hosts.nfz.moe/full/hosts<br/>
7.https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts<br/>
8.https://mirror1.malwaredomains.com/files/justdomains <br/>
9.https://s3.amazonaws.com/lists.disconnect.me/simple_tracking.txt<br/>
10.https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt<br/>
11.https://hblock.molinero.xyz/hosts<br/>
12.http://winhelp2002.mvps.org/hosts.txt<br/>
13.https://raw.githubusercontent.com/yous/YousList/master/hosts.txt<br/>
14.https://adaway.org/hosts.txt<br/>
15.https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext<br/>
16.https://raw.githubusercontent.com/ilpl/ad-hosts/master/hosts<br/>


## Sources of Whitelist data 域名白名单源
1.https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/whitelist.txt<br/>
2.https://raw.githubusercontent.com/VeleSila/yhosts/master/whitelist.txt<br/>
3.https://raw.githubusercontent.com/Ultimate-Hosts-Blacklist/whitelist/master/domains.list<br/>
4.https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/optional-list.txt<br/>
5.https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/referral-sites.txt<br/>

