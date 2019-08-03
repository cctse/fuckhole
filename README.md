# fuckhole
各大平台接口中的巨坑。欢迎广大基友来稿

## 微信开发

- [ ] 微信支付统一下单接口签名错误，使用验证工具检测签名通过。  
懵逼指数：:star::star::star::star::star:  
解决方案：重置密钥  
设置路径：微信商户平台(pay.weixin.qq.com)-->账户设置-->API安全-->密钥设置  
升级时间：没打算改过  
- [ ] ...

## 数据库
- [ ] utc存储时间，转换时间结果为空
懵逼指数：:star::star::star:
解决方案：导入时区到数据库中```mysql_tzinfo_to_sql /usr/share/zoneinfo | mysql -u root -p mysql```
升级时间：未知