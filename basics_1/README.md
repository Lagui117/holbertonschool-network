# Networking Basics #1

This project covers more advanced networking concepts including host file configuration, IP address management, and port listening.

## Learning Objectives

- Understand and modify `/etc/hosts` file
- Display active IPv4 addresses on a machine
- Listen on network ports using netcat

## Files

| File | Description |
|------|-------------|
| `0-change_your_home_IP` | Configures localhost to 127.0.0.2 and facebook.com to 8.8.8.8 |
| `1-show_attached_IPs` | Displays all active IPv4 IPs on the machine |
| `2-port_listening_on_localhost` | Listens on port 98 on localhost |

## Usage

```bash
# Change localhost and facebook.com resolution (requires sudo)
sudo ./0-change_your_home_IP

# Display all active IPv4 addresses
./1-show_attached_IPs

# Listen on port 98 (requires sudo)
sudo ./2-port_listening_on_localhost
```

## Warning

After running `0-change_your_home_IP`, be sure to revert localhost to 127.0.0.1 to avoid breaking your system.

## Author

Holberton School
