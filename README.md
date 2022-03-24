# 说明 instructions


# 方法 methon

* deb publish
```sh
  cat pgp-key.private | gpg --import
  
  aptly publish update <distribution> 
```

* deb install
```
  curl https://seeed-studio.github.io/seeed-linux-deb-rebuild/pgp-key.public | sudo apt-key add -
  
  apt-get install xxx
```

