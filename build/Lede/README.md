# 我的插件配置

## x86_64

```shell
CONFIG_TARGET_x86=y
CONFIG_TARGET_x86_64=y
CONFIG_TARGET_x86_64_DEVICE_generic=y

CONFIG_GRUB_IMAGES=y
CONFIG_PACKAGE_libnetsnmp=y
CONFIG_PACKAGE_luci-compat=y

CONFIG_PACKAGE_openssh-sftp-client=y
CONFIG_PACKAGE_openssh-sftp-server=y
CONFIG_PACKAGE_snmpd=y

#5G信号插件
# CONFIG_PACKAGE_ext-rooter-basic=y

#QMI拨号工具
# CONFIG_PACKAGE_quectel-CM-5G=y #移远
CONFIG_PACKAGE_fibocom-dial=y #广和通

#QMI拨号软件
# CONFIG_PACKAGE_kmod-usb-serial-qualcomm=y
# CONFIG_PACKAGE_kmod-qmi_wwan_q=y
# CONFIG_PACKAGE_kmod-qmi_wwan_f=y
CONFIG_PACKAGE_luci-app-usbmodem=y
# CONFIG_PACKAGE_luci-app-pcimodem=y

#Gobinet拨号软件
# CONFIG_PACKAGE_kmod-gobinet=y
# CONFIG_PACKAGE_luci-app-gobinetmodem=y

# 脚本拨号工具依赖
CONFIG_PACKAGE_grep=y
CONFIG_PACKAGE_procps-ng=y
CONFIG_PACKAGE_procps-ng-ps=y

#更换命令行
CONFIG_PACKAGE_zsh=y

# mt7916 mt7921 mt7922
CONFIG_PACKAGE_hostapd-common=y
CONFIG_PACKAGE_wpad-openssl=y
CONFIG_PACKAGE_wireless-tools=y
CONFIG_PACKAGE_kmod-mac80211=y
CONFIG_PACKAGE_kmod-cfg80211=y
CONFIG_PACKAGE_kmod-mt7615e=y
CONFIG_PACKAGE_kmod-mt7916-firmware=y
CONFIG_PACKAGE_kmod-mt7921e=y
CONFIG_PACKAGE_kmod-mt7922-firmware=y

#系统应用
CONFIG_PACKAGE_luci-app-accesscontrol=y
CONFIG_PACKAGE_luci-app-arpbind=y
CONFIG_PACKAGE_luci-app-autoreboot=y
CONFIG_PACKAGE_luci-app-commands=y
CONFIG_PACKAGE_luci-app-cpufreq=y
CONFIG_PACKAGE_luci-app-ddns=y
CONFIG_PACKAGE_luci-app-diskman=y
CONFIG_PACKAGE_luci-app-eqos=y
CONFIG_PACKAGE_luci-app-fileassistant=y
CONFIG_PACKAGE_luci-app-firewall=y
CONFIG_PACKAGE_luci-app-guest-wifi=y
CONFIG_PACKAGE_luci-app-homebox=y
CONFIG_PACKAGE_luci-app-mwan3=y
CONFIG_PACKAGE_luci-app-mwan3helper=y
CONFIG_PACKAGE_luci-app-netdata=y
CONFIG_PACKAGE_luci-app-nlbwmon=y
CONFIG_PACKAGE_luci-app-ramfree=y
CONFIG_PACKAGE_luci-app-sqm=y
CONFIG_PACKAGE_luci-app-ttyd=y
CONFIG_PACKAGE_luci-app-wrtbwmon=y
CONFIG_PACKAGE_luci-app-wol=y
CONFIG_PACKAGE_luci-app-watchcat=y

# 主题
CONFIG_PACKAGE_luci-app-argon-config=y
CONFIG_PACKAGE_luci-i18n-argon-config-zh-cn=y
CONFIG_PACKAGE_luci-theme-argon=y
CONFIG_PACKAGE_luci-theme-atmaterial_new=y
CONFIG_PACKAGE_luci-theme-bootstrap=y
CONFIG_PACKAGE_luci-theme-edge=y
CONFIG_PACKAGE_luci-theme-ifit=y
CONFIG_PACKAGE_luci-theme-infinityfreedom=y
CONFIG_PACKAGE_luci-theme-material=y
CONFIG_PACKAGE_luci-theme-mcat=y
CONFIG_PACKAGE_luci-theme-design=y
CONFIG_PACKAGE_luci-theme-netgear=y
CONFIG_PACKAGE_luci-theme-rosy=y
CONFIG_PACKAGE_luci-theme-tomato=y

#应用
CONFIG_PACKAGE_luci-app-dockerman=y
CONFIG_PACKAGE_luci-app-adguardhome=y
CONFIG_PACKAGE_luci-app-openclash=y
CONFIG_PACKAGE_luci-app-unblockmusic=y
CONFIG_PACKAGE_luci-app-zerotier=y
CONFIG_PACKAGE_luci-app-uugamebooster=y
```

