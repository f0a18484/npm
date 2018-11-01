# Xmessenger - private messenger powered by NEM
### Application logic is based on "unconfirmed transactions" with lifetime 12 seconds.
### This means that transaction will be delivered but **never be confirmed and isn't therefore recorded on blockchain**.

- The cost of creation multisig account is 0.5 xem.
- The cost of unconfirmed transaction is 0 xem.

- For initiiting "unconfirmed transaction" you should have some xem.
- The more balance the more message could be send at the same time.  

#### 1. Chat: All messages are encrypted.  
![](img/chat.png)

#### 2. Live: All messages are unencrypted(public channel).  
![](img/live.png)

#### 3. Group: All members of group have private key of the group which one they use to decrypt message.
![](img/group.png) 

- Application **DOESN'T** store any information!
- Application works without server-side!
- After refreshing page, all history will be cleared **forever**!  

![](img/network.png)  





## Powered by  [<img src="img/nemlogo.png" width="100">](https://nem.io)