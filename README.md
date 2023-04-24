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
    "https://objects.githubusercontent.com/github-production-release-asset-2e65be/631949073/1bdfcb70-dfb4-4294-b6bd-b583d72f600c?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20230424%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230424T123922Z&X-Amz-Expires=300&X-Amz-Signature=170794008a690c720871e2428bd7a2806adaed28e81dfe5c8ab33fbacdcf19ff&X-Amz-SignedHeaders=host&actor_id=5474615&key_id=0&repo_id=631949073&response-content-disposition=attachment%3B%20filename%3DFBAudienceNetwork-6.9.0.zip&response-content-type=application%2Foctet-stream",
  },
```
5. pod install 直接安装即可
