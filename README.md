# FBAudienceNetwork特定版本的镜像文件
原文件地址为：https://developers.facebook.com/resources/FBAudienceNetwork-x.x.x.zip

# 使用
修改FBAudienceNetwork.podspec.json中的下载源

1.转到 /Users/用户名/.cocoapods/repos/master/Specs

2.搜索FBAudienceNetwork.podspec.json

3.打开对应版本的 FBAudienceNetwork.podspec.json 

4.修改 FBAudienceNetwork.podspec.json
```
"source": {
    "https://raw.githubusercontent.com/HarryNR/FBAudienceNetwork/master/FBAudienceNetwork-6.7.0.zip",
  },
```
5. pod install 直接安装即可
