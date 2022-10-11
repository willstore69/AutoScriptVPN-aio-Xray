# AUTOSC VPN v2

***xray 1.6.0***

***» vmess ws tls & ntls [default port 443 & 80]***

***» vmess tcp http [default port 443]***

***» vless ws tls & ntls [default port 443 & 8880]***

***» vless tcp xtls [default port 443]***

***» trojan ws tls [default port 443]***

***» trojan tcp tls [default port 443]***

***» shadowsocks2022 ws tls [default port 443]***

————————————————————

***» ssh ws ssl [default port 443]***

***» stunnel5 [default port 443,777]***

***» ssh ws [default port 2052]***

***» ovpn tcp,udp,ssl [default port 1194,2200,442]***

***» ovpn ws [default port 2095]***

***» open ssh [default port 22,143]***

***» dropbear [default port 109]***

***» udpgw/badvpn [default port 7100,7200,7300]***

***» squid proxy [default port 3127,8080]***

***» slowdns***

————————————————————

***» l2tp [default port server 1701]***

***» sstp [default port 444]***

————————————————————

# menu change port:

***» change port xray tls***

***» change port xray ntls***

***» change port ssh ws ssl & stunnel5***

***» change port ovpn ssl***

***» change port sstp***

***info : mengubah port xray tls maka seluruh protocol vmess ws tls dll yang menggunakan tls akan ikut terganti***

***info : mengubah port stunnel5 6443 akan mengubah ssh ws ssl juga***

————————————————————

# menu change path:

***» change path vmess ws tls & ntls***

***» change path vmess tcp http***

***» change path vless ws tls & ntls***

***» change path trojan ws tls***

***» change path shadowsocks2022 ws tls***

————————————————————

# menu change uuid/id:

***» change uuid vmess ws tls & ntls***

***» change uuid vmess tcp http***

***» change uuid vless ws tls & ntls***

***» change uuid vless tcp xtls***

***» change uuid trojan ws tls***

***» change uuid trojan tcp tls***

***info : punya buyer yang ingin perpanjang akun vpn tapi gabisa direnew karena expired & dihapus dari server? salah satu manfaat menu ini bisa untuk mengubah uuid/id akun agar sama dengan yang lama***

————————————————————

# menu trial:

***» trial ssh ws ssl,ovpn,slowdns***

***» trial vmess ws tls & ntls***

***» trial vmess tcp http***

***» trial vless ws tls & ntls***

***» trial vless tcp xtls***

***» trial trojan ws tls***

***» trial trojan tcp tls***

***» trial shadowsocks2022 ws tls***

***» trial all list diatas bisa juga lewat bot telegram dengan ketik menu ``auto-sendvpn``***

***info : trial dengan random username otomatis dan masa aktif 1 hari***

————————————————————

# menu detail client exist:

***» detail vmess ws tls & ntls***

***» detail vmess tcp http***

***» detail vless ws tls & ntls***

***» detail vless tcp xtls***

***» detail trojan ws tls***

***» detail trojan tcp tls***

***» detail shadowsocks2022 ws tls***

***info : pernah ngalamin dc/keluar sendiri dari vps setelah membuat akun ?
fungsinya untuk mengecek kembali detail informasi akun vpn yang telah dibuat***

————————————————————

# menu convert to clash

***» convert user vmess ws to clash***

***» convert user vmess tcp http to clash***

***» convert user vless ws to clash***

***» convert user vless tcp xtls to clash***

***» convert user trojan tcp to clash***

***» convert user trojan ws to clash***

***info :***

***jenis config clash : standard + adblock default dari sub.bonds.id***

————————————————————

# menu backup

***» backup via GMAIL***

***» backup via BOT TELEGRAM***

***info : vps mu ngeblock port smtp ? gabisa backup via gmail ? backup via bot telegram solusinya!***

————————————————————

# spec required:

***» os debian 10 or ubuntu 18.04 or ubuntu 20.04***

***» minimum ram 1 gb***

***» minimum cpu 1***

***» dedicated ipv4***

***» kvm***

———————————————————

# price monthly:

***» for 1 ip & 1 month = 20k/$2***

***» for 3 ip & 1 month = 40k/$4***

***» for 5 ip & 1 month = 60k/$6***

# price lifetime:

***» for 1 ip & lifetime = 60k/$6***

***» for 3 ip & lifetime = 90k/$8***

***» for 5 ip & lifetime = 120k/$10***

# contact me

***telegram : https://t.me/user_legend***

<p align="left">
<a href="https://t.me/user_legend" target="blank"><img align="center" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS2SF2L2dLlzXCo08rwQkoN-CSc--18rvf-Qw&usqp=CAU" alt="" height="69" width="69" /></a>
</p>


———————————————————

# syarat & ketentuan [TOS]

***» 1.dengan menyewa disini = anda menyetujui seluruh syarat & ketentuan yang ada***

***» 2.tidak ada trial yang diberikan untuk mencoba, jika ragu bisa skip***

***» 3.jangan backup/restore data vpn dari script lain***

***» 4.gunakan vps yang masih fresh & sebaiknya rebuild/reinstall vps terlebih dahulu sebelum menggunakan autoscript dari saya jika sebelumnya pernah setup script lain***

***» 5.tidak ada pergantian ip address apapun alasannya. tetapi jika anda menyewa 3/5 ip anda bisa menggunakan sisa ip yang belum disetup***

———————————————————

# screenshot autoscript vpn
***menu awal saat login***
![20221012_044045](https://user-images.githubusercontent.com/107354006/195197284-685e6251-bb45-4e22-a939-a6b99bab5e74.jpg)
-
***menu utama part 1***
![20221012_044046](https://user-images.githubusercontent.com/107354006/195197306-26d71cd7-2b6b-47d9-a8c1-5385f66d3e87.jpg)
-
***menu utama part 2***
![20221012_044048](https://user-images.githubusercontent.com/107354006/195197326-f08dcdff-7d47-4afc-bf97-0ae7d803c56a.jpg)
-
***list informasi ip & protocol***
![20221012_045911](https://user-images.githubusercontent.com/107354006/195197122-d59961bc-008a-4812-ad8e-a7d19469869a.jpg)
-
***menu change domain/force domain***
![20221012_045926](https://user-images.githubusercontent.com/107354006/195197157-0ad84905-cf0a-4da4-bdde-64ee85abf97f.jpg)
-
***menu change path***
![20221012_045936](https://user-images.githubusercontent.com/107354006/195197188-23129523-7207-4b11-8dfc-d2735086dbab.jpg)
-
***menu backup via bot telegram***
![20221012_045949](https://user-images.githubusercontent.com/107354006/195197225-cc2b8b27-45ab-4565-80a5-c82e996e0cd7.jpg)
-
***menu convert user ke clash config***
![20221012_050621](https://user-images.githubusercontent.com/107354006/195198384-5a6eeba0-5917-4474-bfce-0d1be1954850.jpg)
-
