# NLA

使用 Nuclei 进行日志分析
辅助蓝队人员快速挖掘WEB日志中的漏洞特征

---
## 已支持
- [x] webshell
- [x] oob
- [x] sqli
- [x] useragent
- [x] nacos
- [x] jeecgboot
- [x] wordpress
- [ ] hikvision
- [ ] jenkins
- [ ] dahua
- [ ] 泛微
- [ ] 致远
- [ ] 金蝶
- [ ] 用友
- [ ] 通达
- [ ] 亿赛通


## 用法
```
nuclei -t /rules -u access.log -file
```
## 效果
![image](img/img1.png)

## 注意事项
nuclei默认情况文件大于5 MB（5242880）将不会处理。遇到大文件请先分割。


## 参考链接:
> https://github.com/ffffffff0x/LOG-HUB
> https://github.com/projectdiscovery/nuclei-templates
> https://github.com/wy876/POC