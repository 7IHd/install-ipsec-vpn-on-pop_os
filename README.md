# Installation notes for ipsec support
Notes derived from [here](https://www.techrepublic.com/article/how-to-add-the-l2tp-vpn-option-to-network-manager-in-linux/)

Update and upgrade beforehand.
```shell
sudo apt-get update
sudo apt-get upgrade
```

Add a repository to apt with the command (I didn't and it worked :shrug:):
```shell
sudo add-apt-repository ppa:nm-l2tp/network-manager-l2t
```

Install it
```shell
sudo apt-get install network-manager-l2tp network-manager-l2tp-gnome
```

Then log out and log back in.
