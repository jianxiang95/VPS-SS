# VPS-SS
deploy VPS and Shadowsocks 

Hello guys, I just want to tell you how to deploy your own SS on VPS. 
Ok,I will give an example with Bandwagon.Of course, Vultr is also good. Here are 9 points.
1.You need to get an account on Bandwagon or Vultr, both of them are great. 
2.Choose an item and pay your money.
3.Click "client area", input your email address and password, click "services----my services"---- "kiwiVM Control Panel” under "Management"---  "main controls"---"stop".
5."Install new OS", choose " debian-7-x86_64”，tick in the small box and then reload.
6.In bandwagon, they will send you an IP address,password and SSH port through email.
7. Open terminal on Macbook, ssh root@ip  # this ip is that vps gives you
8.Input the following codes that involve 3 lines.
1)wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks.sh
2)chmod +x shadowsocks.sh
3)./shadowsocks.sh 2>&1 | tee shadowsocks.log

9.Dowload Shadowsocks.link:https://sourceforge.net/projects/shadowsocksgui/files/dist/          #choose the suitable version

That's it, very simple.
