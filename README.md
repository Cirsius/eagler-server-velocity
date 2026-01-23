## eagler-server-velocity

this is a template velocity server with eaglercraft support. It also has nlogin, limbo, anticheat, ect, so its a good base if you're trying to self host a network. you can replace dionysus with whatever version you want, i just chose dionysus because it has really good performance for 1.12.2 anarchy servers which a good amount of people are trying to run for school servers.

### Customizing

i added anticheat, so if you want to allow hacking, remove ``velocity/plugins/OriginBlacklist-X.X.X.jar``, and``paper/plugins/LightningGrim-bukkit-X.X.X.jar``. also enabled paper's antixray, so disable that if you want aswell ``paper/paper.yml``

you can change the text for the login text at ``velocity/nlogin/lang/messages_en.yml``

if you wanna change the pause menu links and logos and whatnot, do that in ``/velocity/plugins/eaglerxserver/pause_info.yml``

if you wanna change the web page from the walter white one, do it at ``velocity/eaglerweb/web`` or you can remove the eaglerweb plugin entirely. 

### Forwarding

If you're trying to self host but have no idea what you're doing, i recommend installing tailscale on the device youre selfhosting with, then running funnel on it so it can access the internet without having to port forward. https://tailscale.com/kb/1223/funnel

### Updating
i might be too lazy to update some of this so if you wanna update it for me, upload the updated jars and replace the versions set here. 

**Server Versions**
- Velocity: 3.4.0-SNAPSHOT-561
- Dionysus: 0.1.17
- PicoLimbo: 1.10.1

**Proxy Plugin Versions**
- EaglerXServer: 1.0.8
- EaglerXRewind: 1.5.2+1.0.2
- EaglerWeb: 1.0.0
- EaglerMOTD: 1.0.0
- OriginBlacklist: 2.0.6+d8fa2b1
- SkinsRestorer: 15.9.3
- nLogin: 10.4.25

**Paper Plugin Versions**
- EaglerXBackendRPC: 1.0.0
- ViaVersion: 5.7.1-SNAPSHOT+897
- ViaBackwards: 5.7.1-SNAPSHOT+544
- ViaRewind: 4.0.14-SNAPSHOT+322
- ViaRewind-Legacy-Support: 1.5.5-SNAPSHOT+55
- ViaAprilFools: 4.0.8-SNAPSHOT+132
- LightningGrim: 2.3.73-cd86c14