# Windows-KMS
## Windows搭建kms激活服务  
### VMware Workstation Pro 虛擬機軟體：[点击下载](https://www.vmware.com/products/workstation-pro/workstation-pro-evaluation.html)  
- VMware Workstation16激活密钥：``` ZF71R-DMX85-08DQY-8YMNC-PPHV8  ```
### vlmcsd 部署工具: [点击下载](https://github.com/Wind4/vlmcsd)  
### windows激活命令
```  
slmgr -skms 192.168.1.xx  (替換成你自己的ipv4地址)
slmgr -ipk 密鑰（微軟官方批量激活密鑰獲取）
slmgr /ato  
```  
### office激活命令  
```  
cd C:\Program Files \Microsoft Office\Office16
cscript ospp.vbs /sethst:192.168.1.xx （替換你自己的ipV4）
cscript ospp.vbs /act  
```
