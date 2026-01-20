# Networking Basics #0

This project covers the fundamentals of computer networking, including the OSI model, types of networks, IP/MAC addresses, and TCP/UDP protocols.

## Learning Objectives

- Understand the OSI model and its 7 layers
- Differentiate between LAN, WAN, and the Internet
- Understand MAC and IP addresses
- Know the difference between TCP and UDP
- Understand ports and common port numbers (SSH: 22, HTTP: 80, HTTPS: 443)
- Use `ping` to check network connectivity

## Files

| File | Description |
|------|-------------|
| `0-OSI_model` | Answers about the OSI model |
| `1-types_of_network` | Answers about LAN, WAN, and Internet |
| `2-MAC_and_IP_address` | Answers about MAC and IP addresses |
| `3-UDP_and_TCP` | Answers about TCP and UDP protocols |
| `4-TCP_and_UDP_ports` | Bash script that displays listening ports |
| `5-is_the_host_on_the_network` | Bash script that pings an IP address 5 times |

## Usage

```bash
# Display listening ports (requires sudo for full info)
sudo ./basics_0/4-TCP_and_UDP_ports

# Ping an IP address 5 times
./basics_0/5-is_the_host_on_the_network 8.8.8.8
```

## Author

Holberton School
