network:
  version: 2
  renderer: networkd
  ethernets:
    ens18:
      addresses:
        [masinaIP/prefix]
      routes:
        - to: default
          via: lüüsi IP ilma prefixita
          metric: 100
      nameservers:
        search: [local]
        addresses: [127.0.0.1]
      dhcp4: false
