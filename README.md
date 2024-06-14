All I did was translate some of the script into English. I probably broke everything in the process. I don’t know what I’m doing. I say that cooking in the kitchen. I say that to my computer too.  -quartzyeti

# And for the quick & lazy...
```
bash <(wget -qO- -o- https://github.com/quartzyeti/233boy-sing-box-English/raw/main/install.sh)
```

# introduce

The best sing-box one-click installation script & management script

# Features

- Quick installation
- Invincible and easy to use
- Zero learning cost
- Automated TLS
- Simplify all processes
- Compatible with sing-box command
- Powerful shortcut parameters
- Supports all common protocols
- One-click to add VLESS-REALITY (default)
- One-click to add TUIC
- Add Trojan with one click
- Add Hysteria2 with one click
- One-click to add Shadowsocks 2022
- One-click add VMess-(TCP/HTTP/QUIC)
- One-click add VMess-(WS/H2/HTTPUpgrade)-TLS
- One-click addition of VLESS-(WS/H2/HTTPUpgrade)-TLS
- One-click add Trojan-(WS/H2/HTTPUpgrade)-TLS
- One-click to enable BBR
- Change the disguised website with one click
- One-click change (port/UUID/password/domain name/path/encryption method/SNI/etc...)
- there are more...

# design concept

Design concept: **High efficiency, ultra-fast, extremely easy to use**

The script is based on the author's own usage needs, with **multiple configurations running simultaneously** as the core design

And specially optimized, add, change, view, delete, these four common functions

You only need one command to complete operations such as adding, changing, viewing, deleting, etc.

For example, adding a configuration takes less than 1 second! It's added in a flash! The same goes for other operations!

The script parameters are very efficient and super easy to use. Please master the use of parameters.

# document

Installation and usage: https://233boy.com/sing-box/sing-box-script/

# help

Use: `sing-box help`

```
sing-box script v1.0 by 233boy
Usage: sing-box [options]... [args]...

Basics:
   v, version shows the current version
   ip returns the IP address of the current host
   pbk is equivalent to sing-box generate reality-keypair
   get-port returns an available port
   ss2022 returns a password that can be used for Shadowsocks 2022

generally:
   a, add [protocol] [args... | auto] Add configuration
   c, change [name] [option] [args... | auto] Change configuration
   d, del [name] delete configuration**
   i, info [name] View configuration
   qr [name] QR code information
   url [name] URL information
   log View log
Change:
   full [name] [...] Change multiple parameters
   id [name] [uuid | auto] Change UUID
   host [name] [domain] Change the domain name
   port [name] [port | auto] Change port
   path [name] [path | auto] Change path
   passwd [name] [password | auto] Change password
   key [name] [Private key | atuo] [Public key] Change key
   method [name] [method | auto] Change the encryption method
   sni [name] [ ip | domain] change serverName
   new [name] [...] Change protocol
   web [name] [domain] Change masquerade website

Advanced:
   dns [...] Set DNS
   dd, ddel [name...] delete multiple configurations**
   fix [name] Fix a configuration
   fix-all fix all configurations
   fix-caddyfile Fix Caddyfile
   fix-config.json
   import import sing-box/v2ray script configuration

manage:
   un, uninstall
   u, update [core | sh | caddy] [ver]
   U, update.sh update script
   s, status running status
   start, stop, restart [caddy] start, stop, restart
   t, test test run
   reinstall reinstall script

test:
   debug [name] displays some debug information, for reference only
   gen [...] is equivalent to add, but only displays JSON content, does not create files, and is used for testing
   no-auto-tls [...] Same as add, but disables automatic configuration of TLS, can be used for *TLS related protocols
other:
   bbr Enable BBR, if supported
   bin [...] runs the sing-box command, for example: sing-box bin help
   [...] [...] Compatible with most sing-box commands, for example: sing-box generate uuid
   h, help Display this help interface

Be careful when using del and ddel. This option will delete the configuration directly; no confirmation is required.
Feedback issues) https://github.com/233boy/sing-box/issues
Documentation (doc) https://233boy.com/sing-box/sing-box-script/
```
