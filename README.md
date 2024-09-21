修改自：
- https://github.com/projectdiscovery
- https://github.com/projectdiscovery


增加了国内CDN IP判断，及大部分主流CDN 域名判断、主流云资产识别


方便修改 naabu cdn 模块
```
go get -u "github.com/eexp/cdncheck"
全局替换
github.com/projectdiscovery/cdncheck
```