# aimhighergg.com manifest
```
          |-> www.aimhighergg.com/          -> service -> deployment -> pod[wordpress container] 
          |
Ingress ->|-> www.aimhighergg.com/wiki      -> service -> deployment -> pod[mediawiki container]
          |
          |-> www.aimhighergg.com/portfolio -> service -> deployment -> pod[nginx container]
```