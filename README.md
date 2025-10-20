### Eagler Velocity Template

this is a template velocity server with eaglercraft support. It also has nlogin and limbo setup, so its a good base if you're trying to self host a network. you can replace dionysus with whatever version you want, i just chose dionysus because it has really good performance for 1.12.2 anarchy servers which a good amount of people are trying to run for school servers. 

#### Customizing

you can change the text for the login text at ``velocity/nlogin/lang/messages_en.yml``

if you wanna change the pause menu links and logos and whatnot, do that in ``/velocity/plugins/eaglerxserver/pause_info.yml``

iof you wanna change the web page from the walter white one, do it at ``velocity/eaglerweb/web`` or you can remove the eaglerweb plugin entirely. 

#### Forwarding

If you're trying to self host but have no idea what you're doing, i recommend installing tailscale on the device youre selfhosting with, then running funnel on it so it can access the internet without having to port forward. https://tailscale.com/kb/1223/funnel

#### Pico Limbo
the version of picolimbo uploaded is for x86_64 linux os's. get the binary you need for your usecase at https://github.com/Quozul/PicoLimbo/releases

#### Updating
i might be too lazy to update some of this so if you wanna update it for me, upload the updated plugins and replace the versions set here. 

- Velocity: 3.4.0-SNAPSHOT-541  
- ViaBackwards: 5.5.1-SNAPSHOT  
- ViaRewind: 4.0.10  
- ViaRewind-Legacy-Support: 1.5.3  
- ViaVersion: 5.5.1-SNAPSHOT  
- PicoLimbo: V1.6.0  
