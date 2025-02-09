# IPFire
| [![IPFire Logo](/assets/ipfire.png)](https://www.ipfire.org/) |
|:--:| 
| *IPFire Logo* |

## Initial Configuration
Once you have installed IPFire, you will you will need to reboot the system. 
After that, specify your language and keyboard layout.
Next, define your hostname and domain:
| ![Hostname](/assets/ipfire/VirtualBox_IPFire_Hostname.png) |
|:--:| 
| *Hostname Configuration* |

| ![Domain](/assets/ipfire/VirtualBox_IPFire_Domain.png) |
|:--:| 
| *Domain Configuration* |

You will need to define the root and admin passwords. 
Next, you will configure your network settings. 
First, specify if you want to use the basic configuration (Red and Green) or choose an advanced configuration. 
After that, you must define which network interfaces you will use. 
My <span style="color:red">Red interface</span> is set to NAT, and my <span style="color:green">Green interface</span> is set to Internal Network.
| ![NetworkConfiguration](/assets/ipfire/VirtualBox_IPFire_NetworkConfig.png) |
|:--:| 
| *Network Configuration* |

Next, you need to configure each interface.
- <span style="color:green">Green Interface</span>. Select an IP address that will be used to connect to your Admin dashboard. You can also define your network mask.

| ![GreenInterface](/assets/ipfire/VirtualBox_IPFire_GreenInt.png) |
|:--:| 
| *Green Interface* | 

- <span style="color:red">Red Interface</span>. You can configure the Red interface, but it is recommended to select DHCP unless you have specific settings to modify.

| ![RedInterface](/assets/ipfire/VirtualBox_IPFire_RedInt.png) |
|:--:| 
| *Red Interface* |

Finally, you need to configure the DHCP server. First, define the range of IP addresses. After that, you can also add an additional DNS server.
| ![DHCPServer](/assets/ipfire/VirtualBox_IPFire_DHCPServer.png) |
|:--:| 
| *DHCP Server* |

Once completed, you will be able to access the Admin Panel by navigating to  https://192.168.1.1:444.
| ![AdminDashboard](/assets/ipfire/VirtualBox_IPFire_Dashboard.png) |
|:--:| 
| *Admin Dashboard* |

## Firewall Rules
When we select Firewall Rules, we will see the following panel where we can design our rules. I defined some rules, such as blocking internet access from an IP and port forwarding:
| ![FirewallRules](/assets/ipfire/VirtualBox_IPFire_FirewallRules.png) |
|:--:| 
| *Firewall Rules* |
