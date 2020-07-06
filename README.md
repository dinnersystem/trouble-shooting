# trouble-shooting
常見問題解答集

# 500 Internal Server
Restart nginx & php-fpm

sudo systemctl restart nginx
sudo systemctl restart php7.4-fpm

# 當斷電時

- 合作社那台 POS，他應該要


# 當合作社其他的子 POS，連接不上主 POS

- 不知道發生什麼事(?


# 當伺服器就是不會動時

- 重開
- ps aux | grep node
  - kill node if necessary
- clone_build_instance.sh
