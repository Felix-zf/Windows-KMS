# Windows-KMS
## Windows搭建kms激活服务  
### VMware Workstation Pro 虛擬機軟體：[点击下载](https://www.vmware.com/products/workstation-pro/workstation-pro-evaluation.html)  
- VMware Workstation16激活密钥：``` ZF71R-DMX85-08DQY-8YMNC-PPHV8  ```  
- Windows官方激活密钥 [点击前往](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj612867(v=ws.11)#windows-10) 
### vlmcsd 部署工具: [点击下载](https://github.com/Wind4/vlmcsd)  
### windows激活命令
```  
slmgr -skms 192.168.1.xx  (替換成你自己的ipv4地址)
slmgr -ipk 密鑰(微軟官方批量激活密鑰獲取)
slmgr /ato  
```  
### office激活命令  
```  
cd C:\Program Files \Microsoft Office\Office16
cscript ospp.vbs /sethst:192.168.1.xx （替換你自己的ipV4）
cscript ospp.vbs /act  
```  
  
  
![](https://www.freedidi.com/wp-content/uploads/2022/10/freedidi_logo.jpg)
