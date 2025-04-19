network:
  version: 2
  renderer: networkd
  ethernets:
    ens18:
      addresses:
        [192.168.40.228/20]
      routes:
        - to: default
          via: 192.168.32.1
          metric: 100
      nameservers:
        search: [local]
        addresses: [127.0.0.1]
      dhcp4: false
