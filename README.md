## 运行项目

通常需要几个步骤：

1. 安装ruby
2. 安装jekyll
3. 设置gem国内镜像
4. 用jeykll打包、运行项目

```
# 设置gem国内镜像
gem sources --remove https://rubygems.org/
gem sources -a https://gems.ruby-china.com/
gem sources -l
```

```
# 打包
jekyll build

# 运行
jekyll server
```
