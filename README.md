# Half-Life-Dedicated-Server

[RO] Informații despre conținutul fișierelor:
[b]Informații generale[b]
<ul>
   <li>Server-ul este „chel”, default fără alte modificări asupra addons-ului.</li>
   <li>Server-ul conține ultimele update-uri luate prin steamcmd și reînlocuit HLDS-ul cu REHLDS.</li>
</ul>

[b]Alte informații[/b]
<ul>
   <li>ReHLDS - 3.4.0.641</li>
   <li>ReGameDLL - 5.7.0.301</li>
   <li>Metamod -R - 1.3.0.121</li>
   <li>AMX Mod X - 1.8.3-dev+5154</li>
</ul>

[b]Parametrii de pornire a server-ului[/b]
taskset -c 1 ./hlds_run -game cstrike +ip ip-ul tău +port 27015 -pingboost 2 +sys_ticrate 1000 +maxplayers 32 +map de_dust2

TASKETSET - C nr. core ( bindarea server-ului pe un core anume, 1,2,3,4,5,6,7,etc.)

[b]Alte plugin-uri
