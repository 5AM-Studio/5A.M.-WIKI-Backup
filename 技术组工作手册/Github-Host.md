---
title: Github Host
description: 因为Github的clone速度缓慢，在这里贴出解决方式
published: true
date: 2019-12-18T01:32:22.528Z
tags: Tech
---

# Github Host
只是DNS污染，域名无法访问。但是IP并没有封杀。所以可以修改hosts即可访问github。修改方式自己百度哦~
```bash
# github.com
52.74.223.119 github.com
13.250.177.223 github.com
13.229.188.59 github.com
13.114.40.48 github.com
140.82.114.3 github.com
192.30.255.112 github.com
140.82.114.4 github.com
140.82.118.3 github.com
192.30.255.113 github.com
140.82.118.4 github.com
140.82.113.3 github.com

# *.githubassets.github.com
185.199.109.154 github.githubassets.com
185.199.110.154 github.githubassets.com
185.199.109.154 github.githubassets.com

# *.githubusercontent.com
151.101.228.133 raw.githubusercontent.com
151.101.108.133 gist.githubusercontent.com
151.101.108.133 cloud.githubusercontent.com
151.101.108.133 avatars0.githubusercontent.com 
151.101.108.133 avatars1.githubusercontent.com 
151.101.108.133 avatars2.githubusercontent.com 
151.101.108.133 avatars3.githubusercontent.com 
151.101.108.133 avatars4.githubusercontent.com 
151.101.108.133 avatars5.githubusercontent.com 
151.101.108.133 avatars6.githubusercontent.com 
151.101.108.133 avatars7.githubusercontent.com
151.101.108.133 avatars8.githubusercontent.com
151.101.108.133 user-images.githubusercontent.com

#下载
#codeload.github.com
52.216.169.189 s3.amazonaws.com
52.216.106.45 s3.amazonaws.com
52.216.147.13 s3.amazonaws.com
219.76.4.4 github-cloud.s3.amazonaws.com
52.216.171.35 github-production-release-asset-2e65be.s3.amazonaws.com
52.216.138.171 github-production-release-asset-2e65be.s3.amazonaws.com

#204.232.175.78 pages.github.com
#204.232.175.94 gist.github.com
#204.232.175.78 documentcloud.github.com
#207.97.227.252 nodeload.github.com

#collector.githubapp.com
192.30.255.116 api.github.com

```
