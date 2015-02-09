# 歐付寶金流串接示範網站 [![Build Status](https://semaphoreapp.com/api/v1/projects/ecd5c771-0608-4689-82ce-75b2a8398124/345386/badge.png)](https://semaphoreapp.com/tonytonyjan/brainana_shop)

本站主旨用於教學使用，並設計最小、可行的購物車系統。

- 使用 [`allpay_client`](https://github.com/tonytonyjan/allpay) 串接歐付寶。
- 使用 [`adminscaffold`](https://github.com/tonytonyjan/admin_scaffold) 產生後台。

## 啟動

```
git clone
cd brainana_shop
bundle
cp config/application.yml.example config/application.yml
bin/rake db:setup db:fixtures:load
rails server
```