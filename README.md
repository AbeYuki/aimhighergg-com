# status
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/AbeYuki/aimhighergg-com/tree/main.svg?style=shield)](https://dl.circleci.com/status-badge/redirect/gh/AbeYuki/aimhighergg-com/tree/main)

# aimhighergg.com manifest
```
          |-> www.aimhighergg.com/          -> service -> deployment -> pod[wordpress container] 
          |
Ingress ->|-> www.aimhighergg.com/wiki      -> service -> deployment -> pod[mediawiki container]
          |
          |-> www.aimhighergg.com/portfolio -> service -> deployment -> pod[nginx container]
```