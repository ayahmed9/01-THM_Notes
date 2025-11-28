# ❓ What is Networking❔
- Networks
  - Any 2 or more devices that are connected together
    - Everything from {etc.}
      - Laptops
      - Phones
      - Security cameras
      - Traffic lights
      - Farming
  - Integrated into everyday life
    - Gathering weather data
    - Delivering electricity
    - Determining right of way on roads

## ❓ What is the Internet❔
- One giant network comprised of many small networks within itself
  - Made up of many small networks joined together
    - Small networks = private networks
    - Networks that join small/private networks = public networks
      - "Internet"
- First iteration in late 1960s
  - Part of ARPANET project
    - First documented network in action
- Invented in 1989 by Tim Berners-Lee
  - World Wide Web (WWW)
  - Became a repository for storing and sharing informatiom

## Identifying Devices on a Network
To communicate and maintain order, devices must be both indentifying and identifiable
- Devices have 2 means of identification
  - IP address
    - Fluid (changeable)
  - MAC address
    - Fixed
    - Similar to serial number

### Internet Protocol (IP) Address
- Identifies a host on a network for a period of time
- Can be associated with another device without changing
  - Can be reassigned [to different device]
  - Cannot be associated with multiple devices on the same network at the same time
    - (Can be associated with multiple devices on the same network at different times)
- Divided into 4 octets
  - Octet &ndash; a group of 8 bits
    - Bit &ndash; binary digits
  - 192.168.1.1
    - Octet #1 = 192
    - Octet #2 = 168
    - Octet #3 = 1
    - Octet #4 = 1
  - Each octet has a numerical range from 0-255
- The value of each octet will summarize to be IP address of device on network
  - Each octet has individual significance
    - Together they signify IP address
- Calculated through IP addressing & subnetting
- Follow a set of standards called "protocols"
  - Backbone of networking
  - Force devices to communicate in the same language
- Devices can be on both private and public networks
  - Location/environment will determine what type of IP address
    - Public IP address
      - Used to identify device directly connected to global Internet
        - Directly connected to ISP without router in between
      - Assigned by Internet Service Provider (ISP) or public IP owners
        - Monthly bill
      - Globally unique
    - Private IP address
      - Used to identify device amongst other devices
      - Assigned by local DHCP servers
      - Locally unique
        - Unique to local/private network
          - Devices on separate networks can have same IP address simultaneously
  - Devices can use private IP addresses to communicate with each other; data sent to Internet from any device will use public IP address
    - Devices must be on same network to use private IP addresses
      - If devices are on separate networks
        - Data must leave one network and traverse the Internet to reach other network
        - Networks communicate instead of devices
          - Networks = postal system/carrier pigeon/messenger
- As more devices become connected it becomes harder to get public IP addresses that are not already in use
  - IP address versions
    - IPv4 = ^
      - 2<sup>32</sup> (4.29 billion) IP addresses
    - IPv6
      - 2<sup>128</sup> (340 trillion+)
      - More efficient due to new methodologies

### Media Access Control (MAC) Address
