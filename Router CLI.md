## 🗂️ Keywords  
Admin  
Config  
Change name  
Unnecessary command  
Set pass  
Del pass  
Go to Interface  
Set IP  
Up link  
Save command of router  
IP Route  
Show Ip Route

---

## 🖧 Cisco Router CLI Commands – Quick Reference

### ✅ Admin
```
Router>enable
```
Or shorthand:
```
en
```

---

### ✅ Config
```
Router#config t
```

---

### ✅ Change name
```
Router(config)#hostname R0
```

---

### ✅ Unnecessary command
```
R0(config)#no ip domain-lookup
```

---

### ✅ Set pass
```
R0(config)#enable secret password
```

---

### ✅ Delete pass
```
R0(config)#no enable secret
```

---

### ✅ Go to Interface
```
R0(config)#interface fa0/0
```

---

### ✅ Set IP
```
R0(config-if)#ip address 192.168.10.1 255.255.255.0
```

---

### ✅ Up link (enable interface)
```
R0(config-if)#no shutdown
```

---

### ✅ Save running config to startup config
```
R0#copy running-config startup-config
```

---

### ✅ IP Route
```
R0(config)#ip route {destination network} {subnet mask} {gateway}
```
- `{destination network}`: network not directly connected (ends with `.0`)  
- `{subnet mask}`: network mask of destination  
- `{gateway}`: next-hop IP address or exit interface

---

### ✅ Show IP Route
```
R0#show ip route
```
