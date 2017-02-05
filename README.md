#SHADOWSOCKS-LEDE-RASP3

this is the shadowsocks-LEDE *ipk* package for raspberry Pi3,if you running LEDE on raspberry Pi3,you can install this software for crossing the chinese great firewall.

* install

	opkg update

	opkg install shadowsocks-libev_2.6.2-1_arm_cortex-a53_neon-vfpv4.ipk
	
	opkg install luci-app-shadowsocks-without-ipset_1.6.0-1_all.ipk
	
then set you shadowsocks message on the luci web.


