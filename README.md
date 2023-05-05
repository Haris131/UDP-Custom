# UDP-Custom
 * add new user: useradd -M change_me -s /bin/false -e 2023-12-31 && passwd change_me
 * only supports x64 bit

## installer udp-custom server side already tested on ubuntu 20.04-x64 ##

```
wget "https://raw.githubusercontent.com/Haris131/UDP-Custom/main/udp-custom.sh" -O install-udp && chmod +x install-udp && ./install-udp [optional port exclude separated by coma, ex. 53,5300]
```

# Note: 
 * use optional port exclude when port udp between 1-65535 already use by other udp tunnel, like badvpn, ovpn udp and other.
 * edit path config /root/udp/config.json, after change it then reboot

# Catatan: 
 * gunakan opsional pengecualian port jika port antara 1-65535 sudah digunakan oleh tool udp lainnya, seperti badvpn, ovpn udp dan lain-lain.
 * lokasi utk merubah konfigurasi /root/udp/config.json, setelah dirubah kemudian reboot

# Credit
 * [ePro_Dev_Team](https://t.me/ePro_Dev_Team/141)
