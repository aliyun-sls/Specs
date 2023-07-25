# The Aliyun SLS CocoaPods Repo

阿里云日志服务 SLS 官方 CocoaPods 仓库。

## 使用
- Podfile中指定仓库位置，

```
# Master仓库不要遗漏
source 'https://github.com/CocoaPods/Specs.git'
source 'https://github.com/aliyun-sls/Specs.git'
```

- 为工程target添加依赖，例：引入阿里云推送依赖，

```
pod 'AliyunLogProducer/Producer', '~> 3.1.19'
```

## Links
- [Podfile Syntax Reference](https://guides.cocoapods.org/syntax/podfile.html#podfile)
