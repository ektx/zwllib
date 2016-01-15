## Ruby install Error
```sh
> gem install sass

ERROR:  While executing gem ... (Gem::RemoteFetcher::FetchError)
```

修改为taobao镜像:
```sh
# 删除原来的地址
gem sources --r https://rubygems.org/
gem sources -a https://ruby.taobao.org/
```

[taobao镜像](https://ruby.taobao.org/)