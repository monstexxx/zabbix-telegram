## How integrated zabbix with telegram

### Ceate Chatbot via botfather
Create newbot via botfather
![image](https://user-images.githubusercontent.com/29035011/126059100-d105eee5-1a19-4eea-a4ac-402e24a4809a.png)

### Ceate Telegram Group
```
Add bot and botid to telegram group
get telegram group id (/getgroupid@myidbot)
```
![image](https://user-images.githubusercontent.com/29035011/126059439-4270520a-6d43-45bc-b6a7-5749ec687167.png)

### Login to zabbix
Administration -> Media types -> Telegram
![image](https://user-images.githubusercontent.com/29035011/126059525-cf7f2dfe-5aa5-42ce-ab28-3c48a78e938e.png)

### Set zabbix to send to telegram notification
![image](https://user-images.githubusercontent.com/29035011/126059594-878f192d-a556-4449-920c-93336bba6ea4.png)

### Choose host add items and triggers
![image](https://user-images.githubusercontent.com/29035011/126059700-61330f1e-1804-4a29-afd7-8e6824d50deb.png)

### Create Items (ICMP PING)
![image](https://user-images.githubusercontent.com/29035011/126060099-c50c3e79-d24e-48c1-9c6d-5253b4f7b178.png)

###
```
Type (Simple Check)
Key (icmpping)
Host Interface (IP Target)
```
![image](https://user-images.githubusercontent.com/29035011/126059812-44c6d1bc-4f40-4965-a62a-acf740cca06e.png)

### Create Triggers
![image](https://user-images.githubusercontent.com/29035011/126059974-3519f04e-77a8-4c2a-a636-63858fb40aad.png)

### Triggers
![image](https://user-images.githubusercontent.com/29035011/126060047-66572800-84b6-4c81-acd8-029ffacfb301.png)




