## ICMP rule

#### Detect any ICMP traffic
```
alert icmp any any -> any any (msg:"ICMP detected"; sid:1000002;)
```

![Screenshot 2024-08-15 085559](https://github.com/user-attachments/assets/6a8cad3e-2584-4c53-bd3b-e74a27513e21)
