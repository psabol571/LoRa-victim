# LoRa victim

Example vulnerable application based on https://github.com/lnlp/LMIC-node

In order to be vulnerable, you must modify LMIC library like on below picture: 

![image](https://user-images.githubusercontent.com/56118756/225007606-427e57d8-2002-4f01-9072-bdf759bcd1c8.png)

find label "reset:" and comment out the line that handles resetting the device
