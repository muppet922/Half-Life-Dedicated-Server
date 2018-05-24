# Half-Life-Dedicated-Server

[RO] Informații despre conținutul fișierelor:

**Informații generale**
   <li>Server-ul este „chel”, default fără alte modificări asupra addons-ului.</li>
   <li>Server-ul conține ultimele update-uri luate prin steamcmd iar HLDS-ul a fost înlocuit cu REHLDS.</li>

hr
**Alte informații**
   <li>ReHLDS - 3.4.0.641</li>
   <li>ReGameDLL - 5.7.0.301</li>
   <li>Metamod -R - 1.3.0.121</li>
   <li>AMX Mod X - 1.8.3-dev+5154</li>


**Parametrii de pornire a server-ului**

```
taskset -c 1 ./hlds_run -game cstrike +ip ip-ul tău +port 27015 -pingboost 2 +sys_ticrate 1000 +maxplayers 32 +map de_dust2
```

TASKETSET - C nr. core ( bindarea server-ului pe un core anume, 1,2,3,4,5,6,7,etc.)

[EN] File content information:

**General information**
   <li>The server is „bold”, default without any modifications to the addons.</li>
   <li>The server contains the latest updates taken by steamcmd and the HLDS has been replaced with REHLDS.</li>
  
**Other information**
   <li>ReHLDS - 3.4.0.641</li>
   <li>ReGameDLL - 5.7.0.301</li>
   <li>Metamod -R - 1.3.0.121</li>
   <li>AMX Mod X - 1.8.3-dev+5154</li>
   
**Startup parameters of the server**

```
taskset -c 1 ./hlds_run -game cstrike +ip ip-ul tău +port 27015 -pingboost 2 +sys_ticrate 1000 +maxplayers 32 +map de_dust2
```

TASKSET - C number of the core (change the number from taskset -c 1 in 2 if you want to bind your server on second core)
